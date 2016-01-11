#### Test 5497026186051be_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/UEI.SmartControl( 5642): Internal timer expired: 1
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
--------- beginning of system
V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{cc0a9ac type 2 when 91122 com.android.providers.calendar} when 91122
I/ActivityManager(  845): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5980 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5980): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 5980): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@13494d1e
D/CalendarProvider2( 5980): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5980): Created com.android.providers.calendar.CalendarAlarmManager@db0671b(com.android.providers.calendar.CalendarProvider2@13494d1e)
D/CalendarProviderBroadcastReceiver( 5980): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5980): [IntentService] WakeLock acquire, start IntentSerivce
I/art     (  845): Explicit concurrent mark sweep GC freed 22948(1183KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.600ms total 195.372ms
D/CalendarProvider2( 5980): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5980): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5980): [getOrCreateCalendarAlarmManager]
D/AndroidRuntime( 5997): 
D/AndroidRuntime( 5997): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5997): CheckJNI is OFF
D/CalendarProvider2( 5980): [IntentService] Release Lock
D/CalendarProvider2( 5980): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  845): Killing 5877:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10011/pid_5877/cgroup.procs: No such file or directory
D/AndroidRuntime( 5997): Calling main entry com.android.commands.am.Am
I/ActivityManager(  845): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  845): setTaskToReturnTo : TaskRecord{133c8244 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  845): setTaskToReturnTo : TaskRecord{133c8244 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  845): AppWindowTokenEx init.. 
D/ContextHelper(  845): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  845): Focus left window: Window{d5996a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5997): Shutting down VM
D/SplitWindow(  845): check instance of lgWin Window{6aeecae u0 Starting com.test.thalitest}
I/ActivityManager(  845): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6028 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 25.811ms
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 23.111ms
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 564us total 41.705ms
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  845): Starting window displayed
I/SystemUI[Framework](  845): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  845): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1360): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/StatusBarManagerServiceEx(  845): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  845): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ae29a27,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1360): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1360):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1360): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1945): Closing mic
D/BarTransitions( 1360): draw background and invalidate : color = 13000000
D/BarTransitions( 1360): draw background and invalidate : color = 16161616
,I/MicrophoneInputStream( 1945): mic_close com.google.android.apps.gsa.speech.audio.u@399bc776
V/AudioRecord( 1945): stop()
D/AudioRecord( 1945): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
,V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
,V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb42a4000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
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
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger(  281): RecordThread: loop stopping
,V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1945): stop()
,V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): releasing 16 from 1945 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem(  845): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb42a4000 exiting
V/AudioSystem( 1360): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1992): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioSystem( 1945): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioSystem( 2055): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioSystem( 3136): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): removeClient_l() pid 1945, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1945): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1945): Hotword detection finished
D/ContextHelper( 6028): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6028): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6028): Time to load native libraries: 3 ms (timestamps 2687-2690)
,I/LibraryLoader( 6028): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6028): Binding Chromium to main looper Looper (main, tid 1) {db0671b}
,I/LibraryLoader( 6028): Expected native library version number "",actual native library version number ""
I/chromium( 6028): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/AlertService( 5846): Beginning updateAlertNotification
,D/AlertService( 5846): No fired or scheduled alerts
,I/NotificationManager( 5846): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(5) by com.android.calendar
I/BrowserStartupController( 6028): Initializing chromium process, singleProcess=true
I/NotificationManager( 5846): com.android.calendar: cancel(6) by com.android.calendar
W/art     ( 6028): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager( 5846): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(11) by com.android.calendar
E/SysUtils( 6028): ApplicationContext is null in ApplicationStatus
I/NotificationManager( 5846): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 5846): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5846): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5846): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5846): No events found starting within 1 week.
,I/ActivityManager(  845): Killing 5846:com.android.calendar/u0a13 (adj 15): empty #11
W/chromium( 6028): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6028): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6028): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6028): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6028): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6028): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6028): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6028): Remote Branch: 
I/Adreno-EGL( 6028): Local Patches: 
I/Adreno-EGL( 6028): Reconstruct Branch: 
,W/libprocessgroup(  845): failed to open /acct/uid_10013/pid_5846/cgroup.procs: No such file or directory
,V/AudioPolicyService(  281): registerClient() client 0xb3c5eb80, uid 10316
,D/BluetoothManagerService(  845): Message: 20
D/BluetoothManagerService(  845): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f29f3e0:true
,D/BluetoothAdapterService(115628535)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1a1b4e85
W/art     ( 6028): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6028): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6028): CordovaWebView is running on device made by: LGE
,W/art     ( 6028): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6028): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6028): Activity.onPostResume() called 
,D/OpenGLRenderer( 6028): Render dirty regions requested: true
I/OpenGLRenderer( 6028): Initialized EGL, version 1.4
D/OpenGLRenderer( 6028): Enabling debug mode 0
,D/Atlas   ( 6028): Validating map...
,D/SplitWindow(  845): check instance of lgWin Window{e121510 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6028): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  845): Killing 5605:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10061/pid_5605/cgroup.procs: No such file or directory
,D/InputDispatcher(  845): Focus entered window: Window{e121510 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  845): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  845): Displayed com.test.thalitest/.MainActivity: +1s233ms
I/Timeline(  845): Timeline: Activity_windows_visible id: ActivityRecord{250c5f2d u0 com.test.thalitest/.MainActivity t220} time:93389
I/Timeline( 6028): Timeline: Activity_idle id: android.os.BinderProxy@2ce6b4a6 time:93398
,W/BindingManager( 6028): Cannot call determinedVisibility() - never saw a connection for the pid: 6028
,W/ActivityManager(  845): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  845): RTC_WAKEUP set : Alarm{2cf61bc5 type 0 when 1452511665235 com.android.providers.contacts} when 1452511665235
V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{209e091a type 2 when 59768 com.google.android.talk} when 59768
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  845): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6109 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/AlarmManager(  845): RTC_WAKEUP set : Alarm{3c9b7628 type 0 when 1452511721244 com.android.vending} when 1452511721244
,D/Finsky  ( 5497): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/JsMessageQueue( 6028): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6109): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  845): android: cancelAsUser(2) by android
,D/libc-netbsd( 5497): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5497): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5497): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5497): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5497): propertyValue:false
D/libc-netbsd( 5497): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5497): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel_SMS( 6109): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6109): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6109): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6109): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6109): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6109): MmsConfig.loadFromResources
E/Babel_SMS( 6109): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6109): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6109): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6109): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6109): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6109): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6109): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6109): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6109): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6109): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6109): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6109): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6109): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6109): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6109): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6109): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6109): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6109): found sensor: Motion Accel, handle=46
,D/jxcore_app_log( 6028): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622858240
D/JX-Cordova( 6028): jxcore cordova android initializing
,W/Settings( 6109): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 6109): CheckpointMarkThreadRoots callback created = 0xb042d8d0
I/Babel_Crash( 6109): startup - clean
I/Babel   ( 6109): deleted: false for 0
,I/art     ( 6109): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,D/libc-netbsd( 5497): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5497): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AudioCapabilities( 6109): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6109): Unsupported mime audio/adpcm
W/AudioCapabilities( 6109): Unsupported mime audio/g726
W/AudioCapabilities( 6109): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6109): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6109): Unsupported mime video/mjpg
,W/VideoCapabilities( 6109): Unsupported mime video/theora
,W/AudioCapabilities( 6109): Unsupported mime audio/evrc
,W/AudioCapabilities( 6109): Unsupported mime audio/qcelp
W/VideoCapabilities( 6109): Unrecognized profile 2130706433 for video/avc
I/art     ( 6028): CheckpointMarkThreadRoots callback created = 0xb04fccc0
D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 94495098562; DSPS: 3187928; Offset : -2803093519
,I/art     ( 6028): CheckpointMarkThreadRoots callback created = 0xb04fcc90
,W/AudioCapabilities( 6109): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6109): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6109): Unsupported mime audio/evrc
,W/VideoCapabilities( 6109): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6109): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6109): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6109): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6109): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6109): Unrecognized profile 2130706433 for video/avc
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  845): android: cancelAsUser(2) by android
,I/qtaguid ( 5497): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5497): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5497): untagSocket(41) failed with errno -22
,D/Finsky  ( 5497): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/vclib   ( 6109): onServiceConnected
,W/Babel   ( 6109): Attempted to change video mute state without an active call.
W/ResourcesManager( 6109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  845): android: cancelAsUser(2) by android
,I/ActivityManager(  845): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6151 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/art     ( 6109): Suspending all threads took: 11.493ms
V/JNIHelp ( 6109): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 6028): Background sticky concurrent mark sweep GC freed 30638(3MB) AllocSpace objects, 10(1398KB) LOS objects, 22% free, 15MB/20MB, paused 9.791ms total 70.953ms
,W/ResourcesManager( 6151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/qtaguid ( 5497): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5497): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5497): untagSocket(41) failed with errno -22
,I/MultiDex( 6151): VM with version 2.1.0 has multidex support
I/MultiDex( 6151): install
I/MultiDex( 6151): VM has multidex support, MultiDex support library is disabled.
W/System  ( 6109): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6109): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6109): com.google.android.talk: cancel(10436) by com.google.android.talk
,V/JNIHelp ( 6151): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6151): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6151): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f67365: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6151): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6151): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6151): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6151): Reading stored module config
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,D/LocationInitializer( 4161): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1730): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6151): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
I/art     ( 5497): CheckpointMarkThreadRoots callback created = 0xb0580340
,D/CAR.SERVICE( 6151): Connecting to CarCallService...
,I/art     ( 5497): CheckpointMarkThreadRoots callback created = 0xb0580300
,I/art     ( 6151): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6151): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6151): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 6151): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  845): Process com.android.gallery3d (pid 5904) has died
,D/CAR.TEL.Service( 6151): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6151): Creating a new PhoneAdapter instance
,W/ActivityManager(  845): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6151): setListener: com.google.android.gms.car.dn@1fb97578
W/ActivityManager(  845): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6151): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6151): Starting CarCallService with initial phone null
I/NotificationManager( 6151): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6151): Package validated; name: com.android.vending
,I/NotificationManager( 5497): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5497): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/art     ( 5497): Suspending all threads took: 9.367ms
,I/ActivityManager(  845): Process com.android.contacts (pid 5925) has died
,W/jxcore-log( 6028): Initializing JXcore engine
,W/jxcore-log( 6028): JXcore engine is ready
W/jxcore-log( 6028): Starting JXcore engine
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  845): android: cancelAsUser(2) by android
,W/.test.thalitest( 6028): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6272]" dev="sockfs" ino=6272 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6028): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6028): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8773]" dev="sockfs" ino=8773 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6028): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 6028): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6028): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24036]" dev="sockfs" ino=24036 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/qtaguid ( 5497): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5497): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5497): untagSocket(41) failed with errno -22
,W/ProcessCpuTracker(  845): Skipping unknown process pid 6115
,W/ProcessCpuTracker(  845): Skipping unknown process pid 6118
W/jxcore-log( 6028): Platform android
W/jxcore-log( 6028): 
W/jxcore-log( 6028): Process ARCH arm
W/jxcore-log( 6028): 
,W/ResourcesManager( 5497): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5497): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5497): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  845): RTC_WAKEUP set : Alarm{28c2e9e2 type 0 when 1452511724572 com.android.vending} when 1452511724572
,D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/Finsky  ( 5497): [669] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5497): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5497): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  845): android: cancelAsUser(2) by android
,D/libc-netbsd( 5497): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5497): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5497): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5497): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
V/AlarmManager(  845): RTC_WAKEUP set : Alarm{15c29d48 type 0 when 1452511725094 com.google.android.googlequicksearchbox} when 1452511725094
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 5497): propertyValue:false
,I/jxcore-log( 6028): JXcore Cordova bridge is ready!
I/jxcore-log( 6028): 
,W/jxcore-log( 6028): JXcore engine is started
I/chromium( 6028): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6028): Skipped 209 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6028): Toggling radios to true
I/jxcore-log( 6028): 
,D/BluetoothAdapter( 6028): enable(): BT is already enabled..!
D/WifiServiceImplEx(  845): setWifiEnabled: true pid=6028, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  845): setWifiEnabled: true pid=6028, uid=10316
,D/WifiServiceImplEx(  845): disconnect pid=6028, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  845): reconnect pid=6028, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6028): Radios toggled
I/jxcore-log( 6028): 
I/jxcore-log( 6028): My device name is: LGE-LG-D722
I/jxcore-log( 6028): 
I/wpa_supplicant( 2820): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 2820): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  845): WifiStateMachine: Leaving Connected state
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  845): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  845): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  845): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  845): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  277): Clearing all IP addresses on wlan0
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): Read error: ssl=0xb0484e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb0484e00: I/O error during system call, Broken pipe
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
E/WifiStateMachine(  845): Start Disconnecting Watchdog 1
D/ConnectivityService(  845): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  845): ignoring duplicate network state non-change
,D/WifiHS20(  845): hidePasspointNotification off =false
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  845): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  845): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:45.757 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:45.766 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2820): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  845): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  845): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  845): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): ValidatedState{ when=-12ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): DefaultState{ when=-19ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): Forcing reevaluation
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/ActivityManager(  845): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6239 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
,I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/ConnectivityService(  845): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  845): disableDataServiceNotify
D/WifiHS20(  845): hidePasspointNotification off =false
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:45.868 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DSQN    (  845): stop dsqn bin
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
D/WifiNetworkAgent(  845): NetworkAgent: NetworkAgent channel lost
,D/WifiHS20(  845): hidePasspointNotification off =false
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:45.881 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  845): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:45.89 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DhcpStateMachine(  845): StoppedState
D/DhcpStateMachine(  845): StoppedState{ when=-102ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  845): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1360): CM callback handler got msg 524292
D/Nat464Xlat(  845): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): Disconnected - quitting
D/CSLegacyTypeTracker(  845): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  845): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
D/Tethering(  845): MasterInitialState.processMessage what=3
D/ConnectivityService(  845): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  845): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  845): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  845): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  845): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1837): |CORE| No family connected
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
V/NetworkPolicy(  845): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServerServiceExt(  845): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateSCANNING
D/Tethering(  845): MasterInitialState.processMessage what=3
D/WIFI    (  845): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  845):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  845): Removing idletimer
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
W/Settings(  845): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1360): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1360): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/TelephonyIcons( 1360): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1360): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6239): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6239): Using schema version: 115
,I/IndexDatabaseHelper( 6239): Index is fine
,I/art     (  845): Explicit concurrent mark sweep GC freed 34112(1640KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.347ms total 165.227ms
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/ActivityManager(  845): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6262 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6262): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6262): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6262): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  845): Process com.lge.qremote (pid 5067) has died
,D/UEI.SmartControl( 5642): Service.onUnbind: IControl
D/UEI.SmartControl( 5642): Service.onDestroy
D/UEI.SmartControl( 5642): Shutdown IRRCPlayer... 
W/irrc_jni( 5642): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5642): ~IrrcClient ++ 
D/irrcClient( 5642): ~IrrcClient -- 
W/irrc_jni( 5642): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5642): Blaster closed
D/UEI.SmartControl( 5642): Blaster closed
D/UEI.SmartControl( 5642): Shut down QS...
D/UEI.SmartControl( 5642): Stopped file observer...
,I/UEI.SmartControl( 5642): QS lib stop result = true
D/UEI.SmartControl( 5642): QS shutdown complete
I/ActivityManager(  845): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6282 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6282): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/wpa_supplicant( 2820): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
D/BluetoothManagerService(  845): Message: 20
D/BluetoothManagerService(  845): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11bd8f92:true
,D/BluetoothAdapterService(115628535)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1a1b4e85
D/BluetoothAdapterService(115628535)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1a1b4e85
D/LocSvc_java(  845): onReceive
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:46.941 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:46.947 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/wpa_supplicant( 2820): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateASSOCIATED
,I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:46.988 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/wpa_supplicant( 2820): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2820): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:46.994 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateFOUR_WAY_HANDSHAKE
I/WifiServiceExtension(  845): setVHTCapabilityType  : false
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt(  845): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  845): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  845): setSecurityType  : 2
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/PCSuite ( 6262): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6262): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6262): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:47.058 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:47.06 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/ConnectivityService(  845): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/ConnectivityService(  845): Got NetworkAgent Messenger
D/ConnectivityService(  845): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  845): NetworkAgent connected
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
E/WifiConfigStore(  845): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
E/WifiConfigStore(  845): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/PCSuite ( 6262): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6262): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6262): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine(  845): Start Dhcp Watchdog 2
D/DhcpStateMachine(  845): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  845): WaitBeforeStartState
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/PCSuite ( 6262): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6262): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6262): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/ConnectivityService(  845): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6239): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
E/WifiStateMachine(  845): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  845): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  845): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e68f7fd target=com.android.internal.util.StateMachine$SmHandler }
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService(  845): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e68f7fd target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  845): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  845): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  845): DHCP Start wake lock is acquired.
D/CommandListener(  277): Setting iface cfg
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
D/CommandListener(  277): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  845): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  845): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  845): setSupplicantStateCOMPLETED
D/ConnectivityService(  845): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  845): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  845): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  845): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  845): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  845): ignoring duplicate network state non-change
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:47.213 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  845): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:47.22 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  845): Adding iface wlan0 to network 101
E/WifiStateMachine(  845): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:47.227 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = true, mWifiLevel = 3
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  845): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  845): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:47.239 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): mWifiConnected = true, mWifiLevel = 3
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1360): Remote
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
E/ConnectivityService(  845): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  845): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  845): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  277): netlink response contains error (File exists)
D/ConnectivityService(  845): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  845): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  845): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  845): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  845): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  845): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  845):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): Connected
D/ConnectivityService(  845):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  845):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  845):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  845): currentScore = 0, newScore = 20
D/ConnectivityService(  845):    accepting network in place of null
D/ConnectivityService(  845): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  845): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: ,false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  845): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): [LWD] Start DNSResolver start to wait
D/Tethering(  845): MasterInitialState.processMessage what=3
D/ConnectivityService(  845): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  845): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  845): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = 1
D/WIFI    (  845): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  845):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  845): validation of new default Network = false
D/ConnectivityService(  845): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  845): enableDataServiceNotify 
D/DSQN    (  845): start dsqn bin
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): [LWD] wait 500ms before dns check
V/NetworkPolicy(  845): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1360): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1360): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  845): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  845): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1360): CM callback handler got msg 524290
I/DSQN    ( 6312): DSQN samuel.seo ver 141203
E/DSQN    ( 6312): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6312): created command queue thread
I/DSQN    ( 6312): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6312): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/UEI.SmartControl( 5642): QS Service created
V/LGMDMManager( 6282): Create singleton instance
,E/UEI.SmartControl( 5642): QS start get config
D/UEI.SmartControl( 5642):  configuring local db...
,D/DhcpStateMachine(  845): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  845): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  845): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6316): version 5.5.6 starting
E/dhcpcd  ( 6316): get_duid: Read-only file system
,I/AudioManager( 6282): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/dhcpcd  ( 6316): wlan0: rebinding lease of 192.168.1.134
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/PCSuite ( 6262): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6262): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
,I/PCSuite ( 6262): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6262): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/UEI.SmartControl( 5642):  ---- Has DB8: true
,D/UEI.SmartControl( 5642): QS start statue = true Error code = 0
D/UEI.SmartControl( 5642): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5642): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5642): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5642): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5642): IrrcClient ++ 
D/irrcClient( 5642): getIrrcService ++ 
D/irrcClient( 5642): getIrrcService -- 
D/irrcClient( 5642): IrrcClient -- 
W/irrc_jni( 5642): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5642): Services init done
I/UEI.SmartControl( 5642): Device manager: loading config....
D/UEI.SmartControl( 5642): QS Service init finished
D/UEI.SmartControl( 5642): QS Service version name: 0.1.73
D/UEI.SmartControl( 5642): QS Service version code: 1073
D/UEI.SmartControl( 5642): Service requested: Control
D/UEI.SmartControl( 5642): Config is loaded...
,D/UEI.SmartControl( 5642):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5642): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5642): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5642): Internal service binding...
D/UEI.SmartControl( 5642): -----IControl: 11
D/UEI.SmartControl( 5642): File observer start...
E/UEI.SmartControl( 5642): IR Port is disabled: false
D/UEI.SmartControl( 5642): Starting file observer...
D/UEI.SmartControl( 5642): Caller: com.lge.qremote
D/UEI.SmartControl( 5642): ------------ IControl registerCallback...
I/UEI.SmartControl( 5642): Registering callback...
D/UEI.SmartControl( 5642): -----IControl: 19
D/UEI.SmartControl( 5642): Caller: com.lge.qremote
I/UEI.SmartControl( 5642): Registering Services Ready callback...
I/UEI.SmartControl( 5642): Notify client services are ready...
D/UEI.SmartControl( 5642): -----IControl: 8
D/UEI.SmartControl( 5642): Caller: com.lge.qremote
I/AudioManager( 6282): getMode name:com.lge.qremote
,I/AudioManager( 6282): getMode name:com.lge.qremote
,I/AudioManager( 6282): getMode name:com.lge.qremote
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): [LWD] DNSResolver start dns
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  845): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6312): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6312): restart monitoring
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
,D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6312): dsqn report finish
D/DSQN    (  845): DSQM DsqnNotification wlan0  1
D/DSQN    (  845): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 11:28:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452511727885], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452511727867]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  845): Validated
D/ConnectivityService(  845): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  845):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  845):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  845): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  845): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  845): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  845): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  845): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  845):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1360): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  845): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  845): set CMD_CAPTIVE_CHECK_COMPLETED
I/ActivityManager(  845): Killing 5760:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10069/pid_5760/cgroup.procs: No such file or directory
,D/TelephonyIcons( 1360): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1360): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ActivityManager(  845): Killing 5403:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  845): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  845): identical MTU - not setting
D/Nat464Xlat(  845): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  845): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  845):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  845): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  845): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  845): enableDataServiceNotify 
D/DSQN    (  845): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1360): CM callback handler got msg 524295
W/libprocessgroup(  845): failed to open /acct/uid_10086/pid_5403/cgroup.procs: No such file or directory
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:48.156 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  845): dsqn is running restart
,I/DSQN    ( 6334): DSQN samuel.seo ver 141203
E/DSQN    ( 6334): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6334): created command queue thread
I/DSQN    ( 6334): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6334): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  845): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/CAR.SERVICE( 6151): mConnectedToCar = false, abort
,E/ActivityThread( 6151): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@112047de that was originally bound here
E/ActivityThread( 6151): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@112047de that was originally bound here
E/ActivityThread( 6151): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6151): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6151): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6151): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6151): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6151): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6151): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6151): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6151): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6151): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6151): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6151): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6151): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6151): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6151): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6151): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6151): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6151): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6151): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6151): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6151): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6151): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6151): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6151): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@333026db that was originally bound here
E/ActivityThread( 6151): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@333026db that was originally bound here
E/ActivityThread( 6151): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6151): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6151): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6151): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6151): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6151): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6151): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6151): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6151): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6151): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6151): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6151): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6151): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6151): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6151): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6151): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6151): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6151): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6151): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6151): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6151): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6151): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  845): Unbind failed: could not find connection for android.os.BinderProxy@2a765fa8
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  845): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  845): onReceive
,D/LocSvc_java(  845): got connectivity action
I/ActivityManager(  845): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6340 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  845): broadcast - no network connections
D/LocSvc_java(  845): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  845): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  845): onReceive
D/LocSvc_java(  845): got connectivity action
D/LocSvc_java(  845): broadcast - no network connections
D/LocSvc_java(  845): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  845): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  845): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  845): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  845): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  845): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  845): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  845): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  845): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  845): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  845): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/MusicStore( 6340): Database version: 120
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6340): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6340): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6340): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/dhcpcd  ( 6316): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/dhcpcd  ( 6316): wlan0: leased 192.168.1.134 for 86400 seconds
,W/ResourcesManager( 6340): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6340): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ProcessCpuTracker(  845): Skipping unknown process pid 6389
,W/ActivityThread( 6340): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6340): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dc06b54: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6340): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6340): GMSCore installation verified
I/ConfigStore( 6340): Config Database version: 1
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  845): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  845): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  845): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  845): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  845): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  845): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  845): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  845): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  845): RunningState
I/MediaRouter( 6340): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6340): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6340): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6340): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  845): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6408 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6340): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6340): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6408): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  845): Killing 5980:com.android.providers.calendar/u0a14 (adj 15): empty #11
,V/WifiInternetCheck(  845): Single check msg out of sync, ignoring.
,I/NotificationManager( 6340): com.google.android.music: cancel(1061) by com.google.android.music
W/libprocessgroup(  845): failed to open /acct/uid_10014/pid_5980/cgroup.procs: No such file or directory
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:28:50.245 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  845): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  845): onReceive
D/LocSvc_java(  845): got connectivity action
D/LocSvc_java(  845): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  845): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  845): getAGpsConnectionInfo connType - 4
I/[SystemUI]QuickSettingsHandler( 1360): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  845): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  845): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6340): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  845): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  845): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGEmail ( 6408): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/NotificationManager( 1945): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/LGEmail ( 6408): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6408): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  845): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6444 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6408): JNI_OnLoad()
I/HubEmail( 6408): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6408): registerNatives()
I/HubEmail( 6408): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6408): registerNativeMethods()
I/HubEmail( 6408): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6408): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  845): Killing 6151:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/Settings( 6408): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup(  845): failed to open /acct/uid_10006/pid_6151/cgroup.procs: No such file or directory
,D/LGDMClient( 6444): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6444): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6444): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6444): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6444): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6444): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  845): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6468 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6444): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6444): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6444): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6444): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6444): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  845): Killing 5497:com.android.vending/u0a36 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6468): onCreate
W/AppUp4:DB( 6468):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6468):  setFingerPrint start
I/AppUp4:DB( 6468):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6468):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6468):  SDK version = 0
I/AppUp4:DB( 6468):  beforefinger == newfinger no write in DB
W/libprocessgroup(  845): failed to open /acct/uid_10036/pid_5497/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6468): AppBoxApplication onCreate()
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
I/NetworkStateForAutoUpdateMonitor( 6468): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6468): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6468): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6468): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6468): onReceive
I/AppUp4:CustModeStarterReceiver( 6468): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6468): Context : android.app.ReceiverRestrictedContext@2d6850b8
D/AppUp4:CustFacade( 6468): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6468): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6468): begin check event
I/AppUp4:CustModeStarterReceiver( 6468): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6468): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6468): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6468): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6468): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  845): Killing 6109:com.google.android.talk/u0a61 (adj 15): empty #11
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  845): propertyValue:false
,D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  845): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  845): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  845): propertyValue:false
W/libprocessgroup(  845): failed to open /acct/uid_10061/pid_6109/cgroup.procs: No such file or directory
,I/DSQN    ( 6334): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6334): restart monitoring
I/DSQN    ( 6334): dsqn report finish
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  845): DSQM DsqnNotification wlan0  1
D/DSQN    (  845): start to monitor internet connection
I/LgeMiscReceiver( 3136): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3136): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3136): networkInfo.isConnected() = false
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/ActivityManager(  845): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6494 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/WifiInternetCheck(  845): isHttpConnectionAvailable - We got a valid response : 204
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/PhoneMonitor( 6494): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6494): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6494): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  845): Killing 6239:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_6239/cgroup.procs: No such file or directory
,I/CheckinService( 4161): Checkin interval check for package: unspecified last checkin: 1452511705478 min interval config: 0 actual interval: 26400
V/DownloadManager( 3207): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3207): DownloadService onCreate
D/PhoneMonitor( 6494): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/NotificationManager( 3207): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/TelephonyAutoProfiling( 6494): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6494): [parse] Load xml
V/TelephonyAutoProfiling( 6494): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6494): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/DownloadManager( 3207): in removeSpuriousFiles
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  845): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6518 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3207): DownloadService onStartCommand
I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 27.966ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.521ms
,V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@225d7e06 on behalf of 3207
I/CheckinService( 4161): Checking schedule, now: 1452511731986 next: 1452511735443
I/CheckinService( 4161): active receiver: disabled
V/DownloadManager( 3207): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 6494): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@1cd8acc7 on behalf of 3207
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.285ms
I/DownloadManager( 3207): in trimDatabase
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@35d062f4 on behalf of 3207
,V/DownloadManager( 3207): DownloadService onDestroy
,I/ActivityManager(  845): Killing 5642:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6282): android.os.DeadObjectException
,W/System.err( 6282): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6282): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6282): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6282): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6282): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6282): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6282): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6282): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6282): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6282): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6282): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6282): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6282): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6282): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6282): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6282): android.os.DeadObjectException
W/System.err( 6282): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6282): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6282): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6282): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6282): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6282): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6282): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6282): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6282): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6282): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6282): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6282): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6282): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6282): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6282): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  845): failed to kill 1 processes for processgroup 5642
,D/WeatherAncestor( 2705): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:52
W/ActivityManager(  845): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{2217662d type 2 when 104691 com.google.android.gms} when 104691
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherAncestor( 2705): connectivity changed - connection : true
D/Weather_cast( 2705): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:52
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  845): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6548 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6557 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  845): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6548): Quickset Services start...
I/UEI.SmartControl( 6548): Manufacture = LGE
,D/UEI.SmartControl( 6548): File observer start...
E/UEI.SmartControl( 6548): IR Port is disabled: false
D/UEI.SmartControl( 6548): Starting file observer...
D/UEI.SmartControl( 6548): Extracting JNI libs...
D/UEI.SmartControl( 6548): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6557): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6548): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6548): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6548): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6548): --- Selecting new region: 2
I/UEI.SmartControl( 6548): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6548): Platform has CIR...
,D/UEI.SmartControl( 6548): NO CIR support, need to check package...
I/UEI.SmartControl( 6548): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6548): QS Service created
E/UEI.SmartControl( 6548): QS start get config
,D/UEI.SmartControl( 6548): Loading JNI Libs...
D/UEI.SmartControl( 6548):  configuring local db...
,I/Babel_SMS( 6557): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6557): MmsConfig.loadMmsSettings
I/Babel_SMS( 6557): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6557): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6557): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6557): MmsConfig.loadFromResources
E/Babel_SMS( 6557): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6557): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6557): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6557): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6557): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6557): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6557): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6557): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6557): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6557): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6557): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6557): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6557): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6557): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6557): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6557): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6557): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6557): found sensor: Motion Accel, handle=46
,W/Settings( 6557): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6557): startup - clean
,I/art     ( 6557): CheckpointMarkThreadRoots callback created = 0xaaf3e5c0
,I/Babel   ( 6557): deleted: false for 0
,D/UEI.SmartControl( 6548):  ---- Has DB8: true
D/UEI.SmartControl( 6548): QS start statue = true Error code = 0
D/UEI.SmartControl( 6548): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6548): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6548): IRRCDataComm has AudioManager!!!!.
I/art     ( 6557): CheckpointMarkThreadRoots callback created = 0xaaf3e5a0
W/irrc_jni( 6548): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6548): IrrcClient ++ 
D/irrcClient( 6548): getIrrcService ++ 
,D/irrcClient( 6548): getIrrcService -- 
D/irrcClient( 6548): IrrcClient -- 
W/irrc_jni( 6548): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6548): Services init done
D/UEI.SmartControl( 6548): QS Service init finished
D/UEI.SmartControl( 6548): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6548): QS Service version code: 1073
D/UEI.SmartControl( 6548): Service requested: Control
I/UEI.SmartControl( 6548): Device manager: loading config....
D/UEI.SmartControl( 6548): Config is loaded...
,D/UEI.SmartControl( 6548):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6548): Notify AllClients services are ready: 0
,I/ActivityManager(  845): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6608 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6548): Request IControl service: devices are loaded...
I/ActivityManager(  845): Killing 6262:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6548): -----IControl: 11
D/UEI.SmartControl( 6548): Caller: com.lge.qremote
D/UEI.SmartControl( 6548): ------------ IControl registerCallback...
I/UEI.SmartControl( 6548): Registering callback...
D/UEI.SmartControl( 6548): -----IControl: 19
D/UEI.SmartControl( 6548): Caller: com.lge.qremote
I/UEI.SmartControl( 6548): Registering Services Ready callback...
I/UEI.SmartControl( 6548): Notify client services are ready...
D/UEI.SmartControl( 6548): -----IControl: 8
D/UEI.SmartControl( 6548): Caller: com.lge.qremote
,W/AudioCapabilities( 6557): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6557): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6557): Unsupported mime audio/g726
W/AudioCapabilities( 6557): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6557): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6557): Unsupported mime video/mjpg
W/VideoCapabilities( 6557): Unsupported mime video/theora
,D/UEI.SmartControl( 6548): Internal service binding...
,W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_6262/cgroup.procs: No such file or directory
W/AudioCapabilities( 6557): Unsupported mime audio/evrc
,W/AudioCapabilities( 6557): Unsupported mime audio/qcelp
W/VideoCapabilities( 6557): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6557): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6557): Unsupported mime audio/qcelp
W/AudioCapabilities( 6557): Unsupported mime audio/evrc
W/VideoCapabilities( 6557): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6557): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6557): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6557): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6557): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6557): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6557): onServiceConnected
,W/Babel   ( 6557): Attempted to change video mute state without an active call.
I/NotificationManager( 6557): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6557): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6557): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6557): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6557): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6557): propertyValue:false
I/Babel   ( 6557): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  845): Killing 6282:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10106/pid_6282/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6608): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6608): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 6608): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6608):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6608):   adb logcat -s GAv4
W/ContextImpl( 6608): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6608): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6608): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6608): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6608): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  845): Explicit concurrent mark sweep GC freed 64924(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.270ms total 156.481ms
,I/WebViewFactory( 6608): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  845): Process com.google.android.music:main (pid 6340) has died
,I/LibraryLoader( 6608): Time to load native libraries: 2 ms (timestamps 6885-6887)
,I/LibraryLoader( 6608): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6608): Binding Chromium to main looper Looper (main, tid 1) {f03ffd5}
I/LibraryLoader( 6608): Expected native library version number "",actual native library version number ""
I/chromium( 6608): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6608): Initializing chromium process, singleProcess=true
,W/art     ( 6608): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6608): ApplicationContext is null in ApplicationStatus
W/chromium( 6608): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6608): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6608): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6608): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6608): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6608): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6608): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6608): Remote Branch: 
I/Adreno-EGL( 6608): Local Patches: 
I/Adreno-EGL( 6608): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb3c5eae0, uid 10079
,W/AudioManagerAndroid( 6608): Requires BLUETOOTH permission
I/NSApplication( 6608): Starting up...
,I/ActivityManager(  845): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6671 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6693 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 6408:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10021/pid_6408/cgroup.procs: No such file or directory
,W/ResourcesManager( 6693): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AlarmManager(  845): RTC_WAKEUP set : Alarm{3906456c type 0 when 1452511735358 com.google.android.googlequicksearchbox} when 1452511735358
,I/ActivityManager(  845): Killing 6444:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_6444/cgroup.procs: No such file or directory
,I/ActivityManager(  845): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6726 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6726): Database version: 120
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6726): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6726): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6726): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6726): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6726): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6726): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6726): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6726): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dc06b54: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6726): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6726): GMSCore installation verified
,I/ConfigStore( 6726): Config Database version: 1
,I/MediaRouter( 6726): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6726): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  845): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6763 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6726): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6726): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6763): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6763): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  845): Killing 6468:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 6763): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  845): failed to open /acct/uid_10011/pid_6468/cgroup.procs: No such file or directory
,I/NotificationManager( 6726): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6763): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6763): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/eas_req ( 6763): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  845): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6796 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6763): JNI_OnLoad()
I/HubEmail( 6763): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6763): registerNatives()
I/HubEmail( 6763): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6763): registerNativeMethods()
I/HubEmail( 6763): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6763): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  845): Killing 6494:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10038/pid_6494/cgroup.procs: No such file or directory
,W/Settings( 6763): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6796): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6796): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6796): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6796): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6796): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  845): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6819 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/LGDMClient( 6796): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6796): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6796): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6796): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6796): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6796): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  845): Killing 6518:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6819): onCreate
W/AppUp4:DB( 6819):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6819):  setFingerPrint start
,I/AppUp4:DB( 6819):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6819):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6819):  SDK version = 0
I/AppUp4:DB( 6819):  beforefinger == newfinger no write in DB
W/libprocessgroup(  845): failed to open /acct/uid_10051/pid_6518/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6819): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6819): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6819): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6819): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6819): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6819): onReceive
I/AppUp4:CustModeStarterReceiver( 6819): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6819): Context : android.app.ReceiverRestrictedContext@2d6850b8
D/AppUp4:CustFacade( 6819): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6819): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6819): begin check event
I/AppUp4:CustModeStarterReceiver( 6819): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6819): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6819): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6819): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6819): handleAsyncCustNotification do not startCustService
I/ActivityManager(  845): Killing 6548:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10089/pid_6548/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3136): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3136): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3136): networkInfo.isConnected() = false
,I/ActivityManager(  845): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6847 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6847): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6847): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6847): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  845): Killing 6557:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6847): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6847): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6847): [parse] Load xml
V/TelephonyAutoProfiling( 6847): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6847): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6847): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  845): failed to open /acct/uid_10061/pid_6557/cgroup.procs: No such file or directory
,I/CheckinService( 4161): Checkin interval check for package: unspecified last checkin: 1452511705478 min interval config: 0 actual interval: 32942
,V/DownloadManager( 3207): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3207): DownloadService onCreate
I/NotificationManager( 3207): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3207): in removeSpuriousFiles
I/ActivityManager(  845): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6872 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4161): Checking schedule, now: 1452511738488 next: 1452511735443
I/CheckinService( 4161): active receiver: enabled
I/art     (  325): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 305us total 31.609ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.269ms
,I/CheckinService( 4161): Preparing to send checkin request
I/EventLogService( 4161): Accumulating logs since 1452511698434
V/DownloadManager( 3207): DownloadService onStartCommand
V/DownloadManager( 3207): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.132ms
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@340aba60 on behalf of 3207
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@339acb19 on behalf of 3207
,I/DownloadManager( 3207): in trimDatabase
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@112047de on behalf of 3207
I/jxcore-log( 6028): Test app app.js loaded
I/jxcore-log( 6028): 
,I/ActivityManager(  845): Process com.google.android.apps.magazines (pid 6608) has died
,V/DownloadManager( 3207): DownloadService onDestroy
,V/AlarmManager(  845): RTC_WAKEUP set : Alarm{2084f406 type 0 when 1452511735443 com.google.android.gms} when 1452511735443
,I/chromium( 6028): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/CheckinRequestBuilder( 4161): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  845): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6900 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 4161): Failed to find provider info for com.google.android.wearable.settings
,V/AlarmManager(  845): RTC_WAKEUP set : Alarm{1d99eac7 type 0 when 1452511738805 com.android.vending} when 1452511738805
D/WeatherAncestor( 2705): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:58
,D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherAncestor( 2705): connectivity changed - connection : true
D/Weather_cast( 2705): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:58
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  845): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6918 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  845): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  845): Explicit concurrent mark sweep GC freed 14203(731KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.120ms total 145.657ms
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 6900): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  845): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6948 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6948): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6948): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6900): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Babel_SMS( 6918): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6918): MmsConfig.loadMmsSettings
W/Settings( 6900): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6900): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/Babel_SMS( 6918): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6918): MmsConfig.loadFromDatabase
I/NotificationManager( 6900): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 6900): Skipping gmscore version check
,W/art     ( 6918): Suspending all threads took: 7.440ms
,E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6918): MmsConfig.loadFromResources
I/art     ( 6918): CheckpointMarkThreadRoots callback created = 0xb042d560
E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6918): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/MultiDex( 6948): VM with version 2.1.0 has multidex support
I/MultiDex( 6948): install
I/MultiDex( 6948): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 6900): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6900): [1] Libraries$2.run: Finished loading 1 libraries.
,D/SensorManager( 6918): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6918): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6918): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6918): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6918): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6918): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6918): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6918): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6918): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6918): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6918): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6918): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6918): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6918): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6918): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6918): found sensor: Motion Accel, handle=46
I/art     ( 6918): CheckpointMarkThreadRoots callback created = 0xb042d550
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@3bd11c8c on behalf of 6900
V/JNIHelp ( 6948): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6918): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6918): startup - clean
D/Finsky  ( 6900): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6900): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityThread( 6948): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6948): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f67365: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6948): Installed default security provider GmsCore_OpenSSL
I/Babel   ( 6918): deleted: false for 0
I/NotificationManager( 6948): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6948): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  845): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6991 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6948): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6948): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/AudioCapabilities( 6918): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6918): Unsupported mime audio/adpcm
W/AudioCapabilities( 6918): Unsupported mime audio/g726
,W/AudioCapabilities( 6918): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6918): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6918): Unsupported mime video/mjpg
W/VideoCapabilities( 6918): Unsupported mime video/theora
,D/WeatherService( 2705): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:29:0
D/WeatherService( 2705): 2 : TimeTick Intent And Screen On
D/WeatherService( 2705): 2 : SDK version : 21
W/ActivityManager(  845): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 2705): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2705): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2705): 2 : Fixed theme : optimus
D/WeatherReflect( 2705): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1360): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1360): called onTimeUpdated()
I/[SystemUI]Clock( 1360): called onTimeUpdated()
,D/lim     ( 2705): 2 : time = 12:29
,I/LgeClockWidgetControlView( 1360): called onTimeUpdated()
I/WeatherReflect( 2705): Model Name : LG-D722
D/WeatherTheme( 2705): 2 : Different view - status_min_formatted : 28 != 29
D/WeatherTheme( 2705): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/[SystemUI]DateView( 1360): called onTimeUpdated()
D/WeatherReflect( 2705): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/NativeLibraryUtils( 6948): Install completed successfully. count=14 extracted=0
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2705): currentPackage=com.lge.sizechangable.weather.theme.optimus
,W/AudioCapabilities( 6918): Unsupported mime audio/evrc
W/AudioCapabilities( 6918): Unsupported mime audio/qcelp
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6918): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6918): Unsupported mime audio/qcelp
W/AudioCapabilities( 6918): Unsupported mime audio/evrc
,D/Weather4x2_optimus( 2705): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2705): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2705): forecast size is 0
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2705): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2705): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2705): setTouchIntent, appWidgetId: 2
I/[SystemUI]DateView( 1360): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1360): handleTimeUpdate
W/VideoCapabilities( 6918): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  845): Process com.google.android.music:main (pid 6726) has died
,D/Theme_WeatherAncestor_optimus( 2705): url is : null
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2705): 2 : update view, appWidgetId: 2
I/VideoCapabilities( 6918): Unsupported profile 4 for video/mp4v-es
,D/WeatherService( 2705): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:29:0
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,D/WVCdm   (  281): Instantiating CDM.
I/WVCdm   (  281): CdmEngine::OpenSession
,I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6918): onServiceConnected
W/Babel   ( 6918): Attempted to change video mute state without an active call.
,W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
D/Finsky  ( 6900): [850] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
I/NotificationManager( 6918): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/Finsky  ( 6900): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6918): propertyValue:false
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=3689562887
I/Babel   ( 6918): connection state changed from UNKNOWN to CONNECTED
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6991): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6991):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6991):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/GAv4    ( 6991): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6991): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6991): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 6948): CheckpointMarkThreadRoots callback created = 0xb053f770
,I/art     ( 6948): CheckpointMarkThreadRoots callback created = 0xb053f760
,I/dex2oat ( 7026): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 6991): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 7026): dex2oat took 141.951ms (threads: 4)
,I/Adreno-EGL( 6948): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6948): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6948): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6948): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6948): Remote Branch: 
I/Adreno-EGL( 6948): Local Patches: 
I/Adreno-EGL( 6948): Reconstruct Branch: 
,I/LibraryLoader( 6991): Time to load native libraries: 2 ms (timestamps 3344-3346)
,I/LibraryLoader( 6991): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6991): Binding Chromium to main looper Looper (main, tid 1) {f03ffd5}
,I/LibraryLoader( 6991): Expected native library version number "",actual native library version number ""
I/chromium( 6991): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6991): Initializing chromium process, singleProcess=true
,W/art     ( 6991): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6991): ApplicationContext is null in ApplicationStatus
W/chromium( 6991): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6991): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6991): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6991): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6991): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6991): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6991): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6991): Remote Branch: 
I/Adreno-EGL( 6991): Local Patches: 
I/Adreno-EGL( 6991): Reconstruct Branch: 
I/Adreno-EGL( 6948): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6948): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6948): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6948): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6948): Remote Branch: 
I/Adreno-EGL( 6948): Local Patches: 
I/Adreno-EGL( 6948): Reconstruct Branch: 
,V/AudioPolicyService(  281): registerClient() client 0xb3c5ebc0, uid 10079
,W/AudioManagerAndroid( 6991): Requires BLUETOOTH permission
I/NSApplication( 6991): Starting up...
I/ActivityManager(  845): Killing 6763:com.lge.email/u0a21 (adj 15): empty #11
,I/art     ( 6693): CheckpointMarkThreadRoots callback created = 0xaaf05dc0
I/art     ( 6693): CheckpointMarkThreadRoots callback created = 0xaaf05db0
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  845): failed to open /acct/uid_10021/pid_6763/cgroup.procs: No such file or directory
,I/ActivityManager(  845): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7059 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  281): CdmEngine::OpenSession
,I/MusicStore( 7059): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7059): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7059): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7059): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7059): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7059): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7059): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dc06b54: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7059): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7059): GMSCore installation verified
I/ConfigStore( 7059): Config Database version: 1
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 114495848345; DSPS: 3843313; Offset : -2803106806
,I/art     ( 5441): Explicit concurrent mark sweep GC freed 2036(76KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 394us total 46.442ms
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MediaRouter( 7059): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7059): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7059): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7059): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  845): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7093 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/WVCdm   (  281): CdmEngine::CloseSession
,I/GHttpClientFactory( 7059): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7059): Using platform SSLCertificateSocketFactory
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  845): Process com.lge.appbox.client (pid 6819) has died
W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=3310703424
W/ResourcesManager( 7093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7093): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7093): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 7059): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7093): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7093): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7093): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 6796): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6796): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6796): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6796): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 6796): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6796): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 7093): JNI_OnLoad()
I/HubEmail( 7093): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7093): registerNatives()
I/HubEmail( 7093): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7093): registerNativeMethods()
I/HubEmail( 7093): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7093): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  845): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7120 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 7093): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 6796): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6796): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6796): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6796): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6796): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  845): Killing 6847:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10038/pid_6847/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7120): onCreate
,W/AppUp4:DB( 7120):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7120):  setFingerPrint start
I/AppUp4:DB( 7120):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7120):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7120):  SDK version = 0
,I/AppUp4:DB( 7120):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7120): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7120): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7120): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7120): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7120): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7120): onReceive
I/AppUp4:CustModeStarterReceiver( 7120): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7120): Context : android.app.ReceiverRestrictedContext@2d6850b8
,D/AppUp4:CustFacade( 7120): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7120): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7120): begin check event
I/AppUp4:CustModeStarterReceiver( 7120): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7120): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7120): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7120): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7120): handleAsyncCustNotification do not startCustService
I/ActivityManager(  845): Killing 6872:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10051/pid_6872/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3136): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3136): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3136): networkInfo.isConnected() = true
D/PhoneState( 3136): setPdpRejectCasuse : false
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  845): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7139 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7139): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7139): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7139): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  845): Killing 6900:com.android.vending/u0a36 (adj 15): empty #11
,D/PhoneMonitor( 7139): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7139): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7139): [parse] Load xml
V/TelephonyAutoProfiling( 7139): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7139): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7139): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  845): failed to open /acct/uid_10036/pid_6900/cgroup.procs: No such file or directory
,V/DownloadManager( 3207): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3207): DownloadService onCreate
I/DownloadManager( 3207): in removeSpuriousFiles
I/NotificationManager( 3207): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@f03ffd5 on behalf of 3207
I/DownloadManager( 3207): in trimDatabase
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@106503ea on behalf of 3207
I/ActivityManager(  845): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7161 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3207): DownloadService onStartCommand
,V/DownloadManager( 3207): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4161): Checkin interval check for package: unspecified last checkin: 1452511705478 min interval config: 0 actual interval: 38118
,V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@1691c451 on behalf of 3207
,V/DownloadManager( 3207): DownloadService onDestroy
,I/ActivityManager(  845): Killing 6918:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10061/pid_6918/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2705): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:29:3
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherAncestor( 2705): connectivity changed - connection : true
D/Weather_cast( 2705): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:29:3
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  845): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7178 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  845): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7178): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MusicWidget( 2678): mDelayedStopHandler : unbind
,I/art     ( 7178): CheckpointMarkThreadRoots callback created = 0xaaf208c0
,I/art     (  845): Explicit concurrent mark sweep GC freed 23626(1062KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.816ms total 174.413ms
,I/art     ( 7178): CheckpointMarkThreadRoots callback created = 0xaaf20890
,I/MusicBrowser( 2055): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2055): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2055): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2055): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2055): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2055): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  845):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2ce6b4a6com.lge.music.MediaPlaybackService$6@7a9aee7
D/MusicBrowser( 2055): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/Babel_SMS( 7178): MmsConfig: mnc/mcc: 0/0
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/Babel_SMS( 7178): MmsConfig.loadMmsSettings
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@eadc064
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2055): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/Babel_SMS( 7178): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7178): MmsConfig.loadFromDatabase
I/MusicBrowser( 2055): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2055): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2055): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2055): reset
,V/MediaPlayer[Native]( 2055): setListener
V/MediaPlayer[Native]( 2055): disconnect
V/MediaPlayer[Native]( 2055): destructor
E/Babel_SMS( 7178): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7178): MmsConfig.loadFromResources
E/Babel_SMS( 7178): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7178): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/AudioFlinger(  281): releasing 19 from 2055 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2055): disconnect
D/MusicBrowser( 2055): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2055): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2055): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2055): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2055): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2055): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2055): [SmartShareManagerClient] unregisterListener: 607390356
W/SmartShareClient( 2055): [SmartShareManagerClient] unregisterListener invalid listener: 607390356
I/SmartShareClient( 2055): [SmartShareManagerClient] terminate service: 2055/MediaPlaybackService/775494954
E/HomeCloudIF( 2055): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2055): [SmartShareManagerClient] unbindService context:android.app.Application@7d9c93d
,V/CloudHub( 2055): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2055): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2055): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2055): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2055): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2055): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
,D/SensorManager( 7178): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7178): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7178): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7178): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7178): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7178): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7178): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7178): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7178): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7178): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7178): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7178): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7178): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7178): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7178): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7178): found sensor: Motion Accel, handle=46
W/Settings( 7178): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7178): startup - clean
I/Babel   ( 7178): deleted: false for 0
,I/ActivityManager(  845): Killing 7059:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/AudioCapabilities( 7178): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7178): Unsupported mime audio/adpcm
W/AudioCapabilities( 7178): Unsupported mime audio/g726
W/AudioCapabilities( 7178): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7178): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7178): Unsupported mime video/mjpg
W/VideoCapabilities( 7178): Unsupported mime video/theora
,I/WVCdm   (  281): CdmEngine::CloseSession
I/WVCdm   (  281): L3 Terminate.
,W/AudioCapabilities( 7178): Unsupported mime audio/evrc
W/AudioCapabilities( 7178): Unsupported mime audio/qcelp
W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7178): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7178): Unsupported mime audio/qcelp
W/AudioCapabilities( 7178): Unsupported mime audio/evrc
W/libprocessgroup(  845): failed to open /acct/uid_10081/pid_7059/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6948): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6948): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6948): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6948): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6948): Remote Branch: 
I/Adreno-EGL( 6948): Local Patches: 
I/Adreno-EGL( 6948): Reconstruct Branch: 
,W/VideoCapabilities( 7178): Unsupported mime video/mp4v-esdp
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/VideoCapabilities( 7178): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7178): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  845): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7214 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 332us total 21.251ms
,I/vclib   ( 7178): onServiceConnected
W/Babel   ( 7178): Attempted to change video mute state without an active call.
,D/libc-netbsd( 7178): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7178): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.325ms
D/libc-netbsd( 7178): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7178): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/CheckinRequestBuilder( 4161): Classify the device as Phone.
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/NotificationManager( 7178): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/System.out( 7178): propertyValue:false
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.387ms
,I/Babel   ( 7178): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  845): Killing 7093:com.lge.email/u0a21 (adj 15): empty #11
W/ResourcesManager( 7214): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/libprocessgroup(  845): failed to open /acct/uid_10021/pid_7093/cgroup.procs: No such file or directory
,D/libc-netbsd( 4161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 4161): propertyValue:false
,D/BluetoothManagerService(  845): Message: 20
D/BluetoothManagerService(  845): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26b138be:true
,D/BluetoothAdapterService(115628535)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1a1b4e85
,D/BluetoothAdapterService(115628535)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1a1b4e85
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4161): Sending checkin request (9739 bytes)
,I/ActivityManager(  845): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7243 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7214): Create singleton instance
,D/UEI.SmartControl( 7243): Quickset Services start...
I/UEI.SmartControl( 7243): Manufacture = LGE
D/UEI.SmartControl( 7243): File observer start...
E/UEI.SmartControl( 7243): IR Port is disabled: false
D/UEI.SmartControl( 7243): Starting file observer...
D/UEI.SmartControl( 7243): Extracting JNI libs...
D/UEI.SmartControl( 7243): --- this system supports 32-bit or 64-bit only
,I/AudioManager( 7214): getMode name:com.lge.qremote
I/CheckinService( 4161): Checkin interval check for package: unspecified last checkin: 1452511705478 min interval config: 0 actual interval: 39706
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,D/LocationInitializer( 4161): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7214): getMode name:com.lge.qremote
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,W/ContextImpl( 3548): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/UEI.SmartControl( 7243): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7243): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7243): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/CheckinRequestBuilder( 4161): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4161): Failed to find provider info for com.google.android.wearable.settings
I/UEI.SmartControl( 7243): --- Selecting new region: 2
,I/UEI.SmartControl( 7243): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7243): Platform has CIR...
D/UEI.SmartControl( 7243): NO CIR support, need to check package...
I/UEI.SmartControl( 7243): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7243): QS Service created
E/UEI.SmartControl( 7243): QS start get config
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7243): Loading JNI Libs...
D/UEI.SmartControl( 7243):  configuring local db...
I/CheckinRequestBuilder( 4161): Classify the device as Phone.
,I/CheckinTask( 4161): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4161): Checking schedule, now: 1452511745569 next: 1453038994564
,I/CheckinService( 4161): active receiver: disabled
,I/CheckinService( 4161): Checking schedule, now: 1452511745601 next: 1453038994564
I/CheckinService( 4161): active receiver: disabled
,D/CheckinService( 4161): Recording last checkin time for package unspecified as 1452511745611
,V/SetupWizard( 7139): Connected to Gservices successfully
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7243):  ---- Has DB8: true
,D/UEI.SmartControl( 7243): QS start statue = true Error code = 0
D/UEI.SmartControl( 7243): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7243): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7243): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7243): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7243): IrrcClient ++ 
D/irrcClient( 7243): getIrrcService ++ 
D/irrcClient( 7243): getIrrcService -- 
D/irrcClient( 7243): IrrcClient -- 
W/irrc_jni( 7243): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7243): Services init done
,I/UEI.SmartControl( 7243): Device manager: loading config....
D/UEI.SmartControl( 7243): QS Service init finished
,D/UEI.SmartControl( 7243): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7243): QS Service version code: 1073
D/UEI.SmartControl( 7243): Config is loaded...
D/UEI.SmartControl( 7243): Service requested: Control
D/UEI.SmartControl( 7243): Internal service binding...
D/UEI.SmartControl( 7243): -----IControl: 11
D/UEI.SmartControl( 7243): Caller: com.lge.qremote
D/UEI.SmartControl( 7243): ------------ IControl registerCallback...
I/UEI.SmartControl( 7243): Registering callback...
D/UEI.SmartControl( 7243): -----IControl: 19
D/UEI.SmartControl( 7243): Caller: com.lge.qremote
,I/UEI.SmartControl( 7243): Registering Services Ready callback...
,I/UEI.SmartControl( 7243): Notify client services are ready...
D/UEI.SmartControl( 7243): -----IControl: 8
D/UEI.SmartControl( 7243): Caller: com.lge.qremote
I/AudioManager( 7214): getMode name:com.lge.qremote
I/ActivityManager(  845): Killing 7120:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7243):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7243): Notify AllClients services are ready: 0
,I/ActivityManager(  845): Killing 6796:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  845): failed to open /acct/uid_10011/pid_7120/cgroup.procs: No such file or directory
,W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_6796/cgroup.procs: No such file or directory
I/AudioManager( 7214): getMode name:com.lge.qremote
,I/AudioManager( 7214): getMode name:com.lge.qremote
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1360): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  845): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1360): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1360): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1360): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1360): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  845): Handling package changes for user 0
,I/ActivityManager(  845): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7318 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7178): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7178): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7178): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7178): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7318): onCreate
W/AppUp4:DB( 7318):  [AppBoxDatabaseHelper] construct
,W/art     ( 7178): Suspending all threads took: 8.597ms
I/AppUp4:DB( 7318):  setFingerPrint start
I/AppUp4:DB( 7318):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7318):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7318):  SDK version = 0
I/AppUp4:DB( 7318):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7318): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7318): onReceive
I/AppUp4:CustModeStarterReceiver( 7318): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7318): Context : android.app.ReceiverRestrictedContext@61fb615
D/AppUp4:CustFacade( 7318): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7318): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7318): begin check event
I/AppUp4:CustModeStarterReceiver( 7318): Event For Nothing, skip.
I/NotificationService(  845): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  845): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  845): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  845): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7339 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  845): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  845): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  845): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@25fc0b63
,W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/System  ( 7178): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7178): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager(  845): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  845): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7339): Total System Memory = 906309632
,I/GalleryUtils( 7339): Application Heap = 96 MB
I/AppConfig( 7339): App Tier : NOT_DEF
D/SystemHelper( 7339): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  845): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7359 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  845): Killing 7161:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  845): Process com.google.android.apps.magazines (pid 6991) has died
,W/libprocessgroup(  845): failed to open /acct/uid_10051/pid_7161/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7359): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7359): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7359): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7359): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  845): applying state to connected service
,I/SystemConfig( 7359): BUILD Country: EU
I/SystemConfig( 7359): BUILD Operator: OPEN
,I/ActivityManager(  845): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7383 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 2055:com.lge.music/u0a28 (adj 15): empty #11
,I/SystemConfig( 7359): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7359): existFile = false
I/SystemConfig( 7359): canReadFile = false
I/SystemConfig( 7359): systemFeature RCS result false
D/SystemConfig( 7359): refreshRcsSupport() :false
V/AudioFlinger(  281): 2055 died, releasing its sessions
,V/AudioFlinger(  281):  pid 1749 @ 0
V/AudioFlinger(  281):  pid 3136 @ 1
V/AudioFlinger(  281):  pid 3136 @ 2
W/libprocessgroup(  845): failed to open /acct/uid_10028/pid_2055/cgroup.procs: No such file or directory
,I/LockScreenSettings( 7383): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7383): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7383): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7383): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7383): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7383): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  845): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7404 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 6671:com.android.chrome/u0a48 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
,W/libprocessgroup(  845): failed to open /acct/uid_10048/pid_6671/cgroup.procs: No such file or directory
I/ActivityManager(  845): Killing 7139:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10038/pid_7139/cgroup.procs: No such file or directory
,I/art     (  845): Explicit concurrent mark sweep GC freed 25023(1272KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.030ms total 186.371ms
,D/Finsky  ( 7404): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7404): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7404): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7404): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7404): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@230055b7 on behalf of 7404
D/Ads     ( 7404): Skipping gmscore version check
D/Finsky  ( 7404): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7404): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7404): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/UEI.SmartControl( 7243): Internal timer expired: 1
,D/PackageBroadcastService( 4161): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7404): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 4161): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4161): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/Icing   ( 4161): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4161): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  845): Killing 7318:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10011/pid_7318/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  845): Killing 7178:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10061/pid_7178/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:29:14.336 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1360): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1360): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1360): On Skip Timer : true
D/charger_monitor(  490): init target 500000
,D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1360): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/charger_monitor(  490): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  845): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1360): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 12:29:17.359 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 134496586879; DSPS: 4498697; Offset : -2803100486
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{728bba1 type 2 when 144058 com.google.android.gms} when 144058
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1452511771983 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  845): ALS enabled for SRE
D/PowerManagerServiceEx(  845): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28135 ms ago)
,D/qdlights(  845): set_light_backlight: 252
,D/qdlights(  845): set_light_backlight: 249
D/qdlights(  845): set_light_backlight: 245
,D/qdlights(  845): set_light_backlight: 242
,D/qdlights(  845): set_light_backlight: 239
,D/qdlights(  845): set_light_backlight: 235
,D/qdlights(  845): set_light_backlight: 232
,D/qdlights(  845): set_light_backlight: 229
,D/qdlights(  845): set_light_backlight: 225
,D/qdlights(  845): set_light_backlight: 222
,D/qdlights(  845): set_light_backlight: 219
,D/qdlights(  845): set_light_backlight: 215
,D/qdlights(  845): set_light_backlight: 212
,D/qdlights(  845): set_light_backlight: 209
,D/qdlights(  845): set_light_backlight: 205
,D/qdlights(  845): set_light_backlight: 202
,D/qdlights(  845): set_light_backlight: 199
,D/qdlights(  845): set_light_backlight: 195
,D/qdlights(  845): set_light_backlight: 192
,D/qdlights(  845): set_light_backlight: 189
,D/qdlights(  845): set_light_backlight: 185
,D/qdlights(  845): set_light_backlight: 182
,D/qdlights(  845): set_light_backlight: 179
,D/qdlights(  845): set_light_backlight: 175
,D/qdlights(  845): set_light_backlight: 172
,D/qdlights(  845): set_light_backlight: 169
,D/qdlights(  845): set_light_backlight: 165
,D/qdlights(  845): set_light_backlight: 162
,D/qdlights(  845): set_light_backlight: 159
,D/qdlights(  845): set_light_backlight: 155
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  845): set_light_backlight: 152
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
D/qdlights(  845): set_light_backlight: 149
,D/qdlights(  845): set_light_backlight: 145
,D/qdlights(  845): set_light_backlight: 142
,D/qdlights(  845): set_light_backlight: 139
,D/qdlights(  845): set_light_backlight: 135
,D/qdlights(  845): set_light_backlight: 132
,D/qdlights(  845): set_light_backlight: 129
,D/qdlights(  845): set_light_backlight: 125
,D/qdlights(  845): set_light_backlight: 122
,D/qdlights(  845): set_light_backlight: 119
,D/qdlights(  845): set_light_backlight: 115
,D/qdlights(  845): set_light_backlight: 112
,D/qdlights(  845): set_light_backlight: 109
,D/qdlights(  845): set_light_backlight: 105
,D/qdlights(  845): set_light_backlight: 102
,D/qdlights(  845): set_light_backlight: 99
,D/qdlights(  845): set_light_backlight: 95
,D/qdlights(  845): set_light_backlight: 92
,D/qdlights(  845): set_light_backlight: 89
,D/qdlights(  845): set_light_backlight: 85
,D/qdlights(  845): set_light_backlight: 82
,D/qdlights(  845): set_light_backlight: 79
,D/qdlights(  845): set_light_backlight: 75
,D/qdlights(  845): set_light_backlight: 72
,D/qdlights(  845): set_light_backlight: 69
,D/qdlights(  845): set_light_backlight: 65
,D/qdlights(  845): set_light_backlight: 62
,D/qdlights(  845): set_light_backlight: 59
,D/qdlights(  845): set_light_backlight: 55
,D/qdlights(  845): set_light_backlight: 52
,D/qdlights(  845): set_light_backlight: 49
,D/qdlights(  845): set_light_backlight: 45
,D/qdlights(  845): set_light_backlight: 42
,D/qdlights(  845): set_light_backlight: 39
,D/qdlights(  845): set_light_backlight: 35
,D/qdlights(  845): set_light_backlight: 32
,D/qdlights(  845): set_light_backlight: 29
,D/qdlights(  845): set_light_backlight: 25
,D/qdlights(  845): set_light_backlight: 22
,D/qdlights(  845): set_light_backlight: 19
,D/qdlights(  845): set_light_backlight: 15
,D/qdlights(  845): set_light_backlight: 12
,D/qdlights(  845): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 154497309372; DSPS: 5154080; Offset : -2803079844
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  845): ALS enabled for SRE
D/PowerManagerServiceEx(  845): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35129 ms ago)
,I/PowerManagerService(  845): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  845): ALS enabled for SRE
D/PowerManagerServiceEx(  845): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35137 ms ago)
W/ContextImpl(  845): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  845): Sleeping (uid 1000)...
D/LPWGController(  845): [updateScreenState] screen on = false
D/LPWGController(  845): disable proximity sensor
D/LPWGController(  845): enable proximity sensor
,I/SensorManager(  845): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@19a4a39e] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  845): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
,D/sensors_hal_SAM(  845): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  845): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  845): activate: handle is 48, enable
V/sensors_hal_Ctx(  845): activate sensors is 1400000000000
D/sensors_hal_Thresh(  845): enable: handle=48
I/sensors_hal_SAM(  845): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  845): waitForResponse: timeout=1000
V/sensors_hal_SAM(  845): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  845): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  845): enable: Received response: 0
D/PowerManagerServiceEx(  845): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35180 ms ago)
I/Adreno-EGL(  845): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  845): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  845): Build Date: 03/02/15 Mon
I/Adreno-EGL(  845): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  845): Remote Branch: 
I/Adreno-EGL(  845): Local Patches: 
I/Adreno-EGL(  845): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (626 us)
,I/Sensors (  416): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  845): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  845): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  845): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  845): processInd: handle 48, count=1
V/sensors_hal_Thresh(  845): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  845): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  845): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  845): poll: count: 256
I/sensors_hal_Ctx(  845): poll: released wakelock sensor_ind
D/sensors_hal_Util(  845): waitForResponse: timeout=0
D/LPWGController(  845): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  845): current mode = 1  value = 1 1
I/LPWGController(  845): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  845): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1360): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  845): set_light_backlight: 0
,I/SensorManager(  845): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  845): activate: handle is 46, disable
V/sensors_hal_Ctx(  845): activate sensors is 1000000000000
D/sensors_hal_LP2(  845): enable: handle=46
D/sensors_hal_LP2(  845): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  845): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  845): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  845): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  845): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  845): Display changed displayId=0
,D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  845): Excessive delay in setPowerMode(): 169ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  845): Got set_interactive hint
,D/KeyguardViewMediator( 1360): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1360): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1360): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1360): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1360): unregisterProximitySensor
,D/WifiServerServiceExt(  845): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1360): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  845): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 845
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  281): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
,D/KeyguardUpdateMonitor( 1360): handleTimeUpdate
D/GpsLocationProvider(  845): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1802): lockStatus = 0
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1802): RESTART MSG
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/SplitWindow(  845): check instance of lgWin Window{14b9de95 u0 SearchPanel}
,D/Ulp_jni (  845): JNI:system_update. Event-0
,D/InputDispatcher(  845): Window went away: Window{1d74fc92 u0 SearchPanel}
,I/[SystemUI]Clock( 1360): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1360): time changed, timezoneChanged : false
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2705): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:29:44
,D/WeatherService( 2705): 2 : ACTION screen on
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2705): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2705): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:29:44
,W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): ACTION_SCREEN_ON
D/AppCleanupService( 4006): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 845
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
D/WifiController(  845): CMD_SCREEN_OFF 
D/WifiController(  845): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  845): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2705): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:29:44
D/WeatherService( 2705): 2 : ACTION screen off
,D/WeatherService( 2705): 2 : TimeTick Receiver Unregister
D/WeatherService( 2705): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:29:44
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  845): ACTION_SCREEN_OFF
I/Sensors (  416): sns_pwr.c(301):releasing wakelock
D/AppCleanupService( 4006): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4006): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1360): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{31335baa type 2 when 160971 com.android.systemui} when 160971
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1360): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1360): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1360): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1360): called onTimeUpdated()
I/[SystemUI]Clock( 1360): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1360): called onTimeUpdated()
I/[SystemUI]DateView( 1360): called onTimeUpdated()
I/[SystemUI]DateView( 1360): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1360): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 174498085822; DSPS: 5809466; Offset : -2803097815
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,D/PowerManagerServiceEx(  845): acquireWakeLockInternal: lock=675808155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=845
,V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{3ca4f338 type 2 when 186907 com.google.android.gms} when 186907
I/ActivityManager(  845): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7534 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1360): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1360): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1360): On Skip Timer : true
,D/charger_monitor(  490): init target 500000
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1360): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1360): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  845): battery changed pluggedType: 2
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DigitalAppWidgetProvider( 7534): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7534): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@61fb615
D/PowerManagerServiceEx(  845): releaseWakeLockInternal: lock=675808155 [*alarm*], flags=0x0
,I/ActivityManager(  845): Killing 7339:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10023/pid_7339/cgroup.procs: No such file or directory
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 42534(2MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 13MB/22MB, paused 1.593ms total 99.968ms
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 855 seconds from now (1452511815256)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  845): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AlarmManager(  845): RTC_WAKEUP set : Alarm{3aab4f49 type 0 when 1452511806968 com.google.android.gms} when 1452511806968
,V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{88f304e type 2 when 188057 android} when 188057
I/EventLogService( 4161): Aggregate from 1452511738777 (log), 1452510006839 (data)
,D/LocationManagerService(  845): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  845): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  845): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  845): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 194499038574; DSPS: 6464857; Offset : -2803091238
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 214499800963; DSPS: 7120242; Offset : -2803090538
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1360): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1360): called onTimeUpdated()
I/[SystemUI]Clock( 1360): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1360): called onTimeUpdated()
I/[SystemUI]DateView( 1360): called onTimeUpdated()
I/[SystemUI]DateView( 1360): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1360): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 234500775904; DSPS: 7775634; Offset : -2803092238
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1360): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1360): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1360): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1360): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1360): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  845): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 254501545272; DSPS: 8431019; Offset : -2803085497
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 274502215576; DSPS: 9086401; Offset : -2803087023
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1360): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1360): called onTimeUpdated()
I/[SystemUI]Clock( 1360): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1360): called onTimeUpdated()
I/[SystemUI]DateView( 1360): called onTimeUpdated()
I/[SystemUI]DateView( 1360): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1360): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 294502990725; DSPS: 9741787; Offset : -2803105096
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1360): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1360): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1360): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1360): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1360): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  845): battery changed pluggedType: 2
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1360): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1360): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  845): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1360): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1360): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1360): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1360): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1360): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1360): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1360): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  845): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  845): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  845): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 314503664363; DSPS: 10397169; Offset : -2803102949
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6028): --= Surplus to requirements =--
I/jxcore-log( 6028): 
I/jxcore-log( 6028): ****TEST TOOK:  ms ****
I/jxcore-log( 6028): 
I/jxcore-log( 6028): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6028): 
,D/AndroidRuntime( 7611): 
D/AndroidRuntime( 7611): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7611): CheckJNI is OFF
,D/AndroidRuntime( 7611): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  845): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  845): Killing 6028:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  845): WIN DEATH: Window{e121510 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  845): Focus left window: Window{e121510 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  845): Window went away: Window{e121510 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  845): Skipping PackageSetting{3967dcac com.example.hello/10317} due to missing metadata
,I/ActivityManager(  845):   Force finishing activity ActivityRecord{250c5f2d u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  845): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
,W/ActivityManager(  845): Spurious death for ProcessRecord{35ada3b2 6028:com.test.thalitest/u0a316}, curProc for 6028: null
,I/ActivityManager(  845): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  845):   Force finishing activity ActivityRecord{250c5f2d u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  845): Duplicate finish request for ActivityRecord{250c5f2d u0 com.test.thalitest/.MainActivity t220 f}
,D/KeyguardModel( 1360): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/art     ( 1945): Explicit concurrent mark sweep GC freed 9831(664KB) AllocSpace objects, 4(96KB) LOS objects, 39% free, 12MB/20MB, paused 5.488ms total 71.781ms
I/InputReader(  845): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
I/art     ( 4161): Explicit concurrent mark sweep GC freed 4894(294KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/18MB, paused 812us total 104.173ms
,W/System.err( 3548): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/SQLiteConnectionPool( 4161): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/System.err( 3548): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3548): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3548): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3548): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3548): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3548): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3548): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3548): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3548): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3548): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3548): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  845): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7643 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
,I/[SystemUI]QSlideListController( 1360): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1360): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1360): createShortcutInfo...
,D/KeyguardModel( 1360): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1360): createShortcutInfo...
W/ResourceType( 1360): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
W/PackageManager( 1360): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1360): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1360): createShortcutInfo...
W/ResourceType( 1360): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1360): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1360): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1360): createShortcutInfo...
W/ResourceType( 1360): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1360): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/KeyguardModel( 1360): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1360): createShortcutInfo...
I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1360): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1360): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1360): handleShortcutListChanged...
,W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1360): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1360): createShortcutInfo...
D/KeyguardModel( 1360): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1360): createShortcutInfo...
,W/ResourceType( 1360): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1360): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1360): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1360): createShortcutInfo...
W/ResourceType( 1360): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1360): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1360): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1360): createShortcutInfo...
W/ResourceType( 1360): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1360): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemUI[Framework](  845): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/ResourcesManager( 7643): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7643): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/PhoneWindowManagerEx(  845): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  845): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  845): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ae29a27,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  845): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/ResourcesManager( 7643): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/PhoneWindowManagerEx(  845): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  845): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  845): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ae29a27,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  845): Focus entered window: Window{d5996a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1360): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1360): createShortcutInfo...
,D/KeyguardModel( 1360): handleShortcutListChanged...
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  845): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  845): Got RemoteException sending setActive(false) notification to pid 6028 uid 10316
,I/art     (  845): Explicit concurrent mark sweep GC freed 62707(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.382ms total 247.272ms
I/art     (  845): WaitForGcToComplete blocked for 228.578ms for cause Explicit
,I/LGEmail ( 7643): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7643): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  845): Timeline: Activity_windows_visible id: ActivityRecord{682e3f0 u0 com.lge.launcher2/.Launcher t219} time:330604
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/administrator(  845): Handling package changes for user 0
,W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1618): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
I/PackageChangeReceiver( 7643): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/art     (  845): Explicit concurrent mark sweep GC freed 6333(396KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.032ms total 362.680ms
I/ActivityManager(  845): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7669 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 7359:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10018/pid_7359/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/AppUp4:AppBoxCP( 7669): onCreate
W/AppUp4:DB( 7669):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7669):  setFingerPrint start
I/AppUp4:DB( 7669):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7669):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7669):  SDK version = 0
I/AppUp4:DB( 7669):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7669): AppBoxApplication onCreate()
D/AndroidRuntime( 7611): Shutting down VM
I/NotificationService(  845): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  845): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  845): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/PhoneStatusBar( 1360): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1360): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1360):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1360): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  845): removeObsoleteFile: deleting file=220_task.xml
,D/AppUp4:PreloadHelper( 7669): added Exclude : com.test.thalitest
,I/ActivityManager(  845): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7686 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  845): Killing 6948:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  845): failed to open /acct/uid_10006/pid_6948/cgroup.procs: No such file or directory
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager(  845): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Timeline( 1875): Timeline: Activity_idle id: android.os.BinderProxy@297b63c1 time:331328
,I/art     ( 1875): Explicit concurrent mark sweep GC freed 27092(1486KB) AllocSpace objects, 19(2MB) LOS objects, 39% free, 15MB/25MB, paused 1.212ms total 56.039ms
,W/ResourceType(  845): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7686): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7686): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7686): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7686): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7686): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 7686): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 7686): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 7686): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7686): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7686): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 7686): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 7686): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 7686): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 7686): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 7686): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 7686): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 7686): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7686): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7686): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7686): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7686): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7686): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7686): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7686): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/AndroidRuntime( 7686): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7686): FATAL EXCEPTION: main
E/AndroidRuntime( 7686): Process: com.android.settings, PID: 7686
E/AndroidRuntime( 7686): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7686): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 7686): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 7686): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 7686): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 7686): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7686): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7686): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7686): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 7686): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7686): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7686): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 7686): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 7686): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 7686): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 7686): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7686): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7686): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 7686): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 7686): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 7686): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 7686): 	... 11 more

```
