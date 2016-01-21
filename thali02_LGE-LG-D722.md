#### Test 56672827b6f75d5_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/NotificationManager( 1771): com.google.android.gms: cancel(0) by com.google.android.gms
D/CalendarProvider2( 6105): [IntentService] Release Lock
I/AudioManager( 5082): getMode name:com.lge.qremote
D/CalendarProvider2( 6105): CalendarProviderIntentService.onDestroy()
W/GCoreFlp( 1771): No location to return for getLastLocation()
W/FusedLocationProvider( 1771): location=null
I/AudioManager( 5082): getMode name:com.lge.qremote
I/AudioManager( 5082): getMode name:com.lge.qremote
--------- beginning of system
I/ActivityManager(  841): Killing 5896:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/CAR.SERVICE( 6073): com.google.android.projection.gearhead isn't installed.
W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_5896/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Killing 5954:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_5954/cgroup.procs: No such file or directory
D/CAR.TEL.Service( 6073): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6073): Creating a new PhoneAdapter instance
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6073): setListener: com.google.android.gms.car.dn@301fc739
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6073): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6073): Starting CarCallService with initial phone null
I/NotificationManager( 6073): com.google.android.gms: cancel(10436) by com.google.android.gms
D/CAR.SERVICE( 6073): Package validated; name: com.android.vending
I/NotificationManager( 5602): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5602): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/AndroidRuntime( 6150): 
D/AndroidRuntime( 6150): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6150): CheckJNI is OFF
V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  841): android: cancelAsUser(2) by android
I/qtaguid ( 5602): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5602): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5602): untagSocket(41) failed with errno -22
D/AndroidRuntime( 6150): Calling main entry com.android.commands.am.Am
I/ActivityManager(  841): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ResourcesManager( 5602): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5602): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ActivityManager(  841): setTaskToReturnTo : TaskRecord{2b39b518 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  841): setTaskToReturnTo : TaskRecord{2b39b518 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
W/ResourcesManager( 5602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WindowStateEx(  841): AppWindowTokenEx init.. 
D/ContextHelper(  841): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  841): Focus left window: Window{3d59e64a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6150): Shutting down VM
I/[LGHome]EVENT( 1950): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  841): check instance of lgWin Window{127cb473 u0 Starting com.test.thalitest}
D/Finsky  ( 5602): [1] DailyHygiene.access$600: Logging device features
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
I/ActivityManager(  841): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6172 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{29db312e type 0 when 1453394643259 com.android.vending} when 1453394643259
I/[LGHome]EVENT( 1950): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1950): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  841): Starting window displayed
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1a4e5123,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = b000000
D/BarTransitions( 1370): draw background and invalidate : color = f0e0e0e
,D/DeviceConnectionService( 1771): client connected with version: 8296000
I/HotwordDetector( 2028): Closing mic
D/Finsky  ( 5602): [675] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/MicrophoneInputStream( 2028): mic_close com.google.android.apps.gsa.speech.audio.u@278246d8
V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AudioRecord( 2028): stop()
D/AudioRecord( 2028): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
I/NotificationManager(  841): android: cancelAsUser(2) by android
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3876000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/Finsky  ( 5602): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5602): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3876000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 2028): stop()
V/AudioRecord( 2028): stop()
V/AudioRecord( 2028): stop()
D/ContextHelper( 6172): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioFlinger(  278): releasing 16 from 2028 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioSystem( 2116): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2028): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3477): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  841): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem( 1802): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb3876000 exiting
V/AudioSystem( 2080): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
I/HotwordRecognitionRnr( 2028): Stopping hotword detection.
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 2028, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 2028): Hotword detection finished
D/libc-netbsd( 5602): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5602): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5602): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5602): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 5602): propertyValue:false
I/WebViewFactory( 6172): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6172): Time to load native libraries: 2 ms (timestamps 3997-3999)
I/LibraryLoader( 6172): Expected native library version number "",actual native library version number ""
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 94027477884; DSPS: 3178890; Offset : -2991713122
I/GAV2    ( 5839): Thread[GAThread,5,main]: No campaign data found.
V/WebViewChromiumFactoryProvider( 6172): Binding Chromium to main looper Looper (main, tid 1) {8ada640}
I/LibraryLoader( 6172): Expected native library version number "",actual native library version number ""
I/chromium( 6172): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6172): Initializing chromium process, singleProcess=true
W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6172): ApplicationContext is null in ApplicationStatus
W/chromium( 6172): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/ActivityManager(  841): Killing 5774:com.android.contacts/u0a18 (adj 15): empty #11
E/libEGL  ( 6172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6172): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6172): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6172): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6172): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6172): Remote Branch: 
I/Adreno-EGL( 6172): Local Patches: 
I/Adreno-EGL( 6172): Reconstruct Branch: 
I/ActivityManager(  841): Killing 5979:com.android.gallery3d/u0a23 (adj 15): empty #12
V/AudioPolicyService(  278): registerClient() client 0xb551cba0, uid 10316
W/libprocessgroup(  841): failed to open /acct/uid_10018/pid_5774/cgroup.procs: No such file or directory
W/libprocessgroup(  841): failed to open /acct/uid_10023/pid_5979/cgroup.procs: No such file or directory
D/BluetoothManagerService(  841): Message: 20
,D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b59f78:true
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6172): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6172): CordovaWebView is running on device made by: LGE
,W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6172): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 6172): Activity.onPostResume() called 
,D/OpenGLRenderer( 6172): Render dirty regions requested: true
I/OpenGLRenderer( 6172): Initialized EGL, version 1.4
D/OpenGLRenderer( 6172): Enabling debug mode 0
,D/Atlas   ( 6172): Validating map...
,D/SplitWindow(  841): check instance of lgWin Window{38e4ca7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6172): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  841): Focus entered window: Window{38e4ca7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  841): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  841): Displayed com.test.thalitest/.MainActivity: +1s246ms
I/Timeline(  841): Timeline: Activity_windows_visible id: ActivityRecord{254f9b71 u0 com.test.thalitest/.MainActivity t222} time:94716
I/Timeline( 6172): Timeline: Activity_idle id: android.os.BinderProxy@32a3a20f time:94726
,W/BindingManager( 6172): Cannot call determinedVisibility() - never saw a connection for the pid: 6172
,I/ActivityManager(  841): Process com.google.android.music:main (pid 6024) has died
,D/AlertService( 5924): Beginning updateAlertNotification
,D/AlertService( 5924): No fired or scheduled alerts
I/NotificationManager( 5924): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 5924): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5924): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 5924): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5924): No events found starting within 1 week.
,D/JsMessageQueue( 6172): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  841): Killing 5924:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10013/pid_5924/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/jxcore_app_log( 6172): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622833664
I/chromium( 6172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 6172): CheckpointMarkThreadRoots callback created = 0x9c1cc440
,I/art     ( 6172): CheckpointMarkThreadRoots callback created = 0x9c1cc410
,D/UEI.SmartControl( 6007): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  841): Killing 5697:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_5697/cgroup.procs: No such file or directory
,W/jxcore-log( 6172): Initializing JXcore engine
,W/jxcore-log( 6172): JXcore engine is ready
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/Thread-747( 6254): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5803]" dev="sockfs" ino=5803 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-747( 6254): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-747( 6254): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8322]" dev="sockfs" ino=8322 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-747( 6254): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-747( 6254): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-747( 6254): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28220]" dev="sockfs" ino=28220 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6172): Starting JXcore engine
,D/CAR.SERVICE( 6073): mConnectedToCar = false, abort
E/ActivityThread( 6073): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@194783a6 that was originally bound here
E/ActivityThread( 6073): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@194783a6 that was originally bound here
E/ActivityThread( 6073): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6073): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6073): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6073): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6073): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6073): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6073): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6073): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6073): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6073): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6073): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6073): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6073): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6073): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6073): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6073): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6073): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6073): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6073): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6073): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6073): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6073): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6073): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1b139300 that was originally bound here
E/ActivityThread( 6073): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1b139300 that was originally bound here
E/ActivityThread( 6073): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6073): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6073): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6073): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6073): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6073): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6073): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6073): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6073): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6073): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6073): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6073): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6073): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6073): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6073): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6073): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6073): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6073): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6073): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6073): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6073): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  841): Unbind failed: could not find connection for android.os.BinderProxy@2c66299f
W/jxcore-log( 6172): Platform android
W/jxcore-log( 6172): 
,W/jxcore-log( 6172): Process ARCH arm
W/jxcore-log( 6172): 
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/jxcore-log( 6172): JXcore Cordova bridge is ready!
I/jxcore-log( 6172): 
W/jxcore-log( 6172): JXcore engine is started
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{136aceb5 type 0 when 1453394648574 com.google.android.googlequicksearchbox} when 1453394648574
,I/jxcore-log( 6172): Toggling radios to true
I/jxcore-log( 6172): 
D/BluetoothAdapter( 6172): enable(): BT is already enabled..!
,D/WifiServiceImplEx(  841): setWifiEnabled: true pid=6172, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  841): setWifiEnabled: true pid=6172, uid=10316
,D/WifiServiceImplEx(  841): disconnect pid=6172, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  841): reconnect pid=6172, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6172): Radios toggled
I/jxcore-log( 6172): 
I/jxcore-log( 6172): My device name is: LGE-LG-D722
I/jxcore-log( 6172): 
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  841): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1876): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  841): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  841): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1771): Read error: ssl=0xaaee1800: I/O error during system call, Connection timed out
V/NativeCrypto( 1771): SSL shutdown failed: ssl=0xaaee1800: I/O error during system call, Broken pipe
D/ConnectivityService(  841): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): ValidatedState{ when=-2ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=-19ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Forcing reevaluation
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  841): hidePasspointNotification off =false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  841): ignoring duplicate network state non-change
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:08.783 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,I/ActivityManager(  841): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  841): Start Disconnecting Watchdog 1
D/WifiHS20(  841): hidePasspointNotification off =false
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-SCAN-STARTED 
D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/ConnectivityService(  841): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  841): disableDataServiceNotify
D/DSQN    (  841): stop dsqn bin
D/WifiHS20(  841): hidePasspointNotification off =false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:08.891 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:08.892 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
D/ConnectivityService(  841): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  841): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  841): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  841): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  841): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1913): |CORE| No family connected
V/NetworkPolicy(  841): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  841): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  841): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1913): |CORE| No family connected
I/QCNEJ   ( 1913): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  841): Removing idletimer
D/Tethering(  841): MasterInitialState.processMessage what=3
D/Tethering(  841): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1913): |CORE| sendDefaultNwMsg: default = -1
D/WifiNetworkAgent(  841): NetworkAgent: NetworkAgent channel lost
,D/TelephonyNetworkFactory-1( 1802): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1802):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:08.927 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  841): hidePasspointNotification off =false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:08.935 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateDISCONNECTED
D/WIFI    (  841): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateSCANNING
D/DhcpStateMachine(  841): StoppedState
D/DhcpStateMachine(  841): StoppedState{ when=-92ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
W/ResourcesManager( 6295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no, resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6295): Using schema version: 115
,I/IndexDatabaseHelper( 6295): Index is fine
I/ActivityManager(  841): Process com.google.android.apps.plus (pid 5566) has died
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
I/ActivityManager(  841): Process com.android.providers.calendar (pid 6105) has died
,I/ActivityManager(  841): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6323 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6323): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6323): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6323): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
I/PCSuite ( 6323): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6323): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6323): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6349 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/wpa_supplicant( 2682): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  841): onReceive
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.022 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.025 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,I/wpa_supplicant( 2682): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateFOUR_WAY_HANDSHAKE
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.066 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.069 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/wpa_supplicant( 2682): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/WifiServiceExtension(  841): setVHTCapabilityType  : false
I/WifiServerServiceExt(  841): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  841): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  841): setSecurityType  : 2
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.173 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.175 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,D/ConnectivityService(  841): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  841): Got NetworkAgent Messenger
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  841): NetworkAgent connected
W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Setting iface cfg
E/WifiStateMachine(  841): Start Dhcp Watchdog 2
D/DhcpStateMachine(  841): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  841): WaitBeforeStartState
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@beed896 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@beed896 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  841): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  841): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  841): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  841): DHCP Start wake lock is acquired.
D/CommandListener(  273): Setting iface cfg
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  841): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateCOMPLETED
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  841): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  841): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.342 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  841): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.347 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  841): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  841): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.362 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  841): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  841): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  841): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:10.375 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  841): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  273): netlink response contains error (File exists)
D/ConnectivityService(  841): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  841): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  841): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/Nat464Xlat(  841): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  841): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  841): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  841): currentScore = 0, newScore = 20
D/ConnectivityService(  841):    accepting network in place of null
D/ConnectivityService(  841): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1802): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1802):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  841): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  841): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  841): MasterInitialState.processMessage what=3
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  841): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService(  841): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  841): validation of new default Network = false
D/ConnectivityService(  841): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  841): enableDataServiceNotify 
D/DSQN    (  841): start dsqn bin
W/QCNEJ   ( 1913): |CORE| No family connected
I/QCNEJ   ( 1913): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1913): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  841): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
I/DSQN    ( 6379): DSQN samuel.seo ver 141203
E/DSQN    ( 6379): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6379): created command queue thread
I/DSQN    ( 6379): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6379): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/NetworkPolicy(  841): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] wait 500ms before dns check
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/Babel_SMS( 6349): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6349): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6349): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6349): MmsConfig.loadFromDatabase
D/DhcpStateMachine(  841): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  841): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  841): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6390): version 5.5.6 starting
E/dhcpcd  ( 6390): get_duid: Read-only file system
,E/Babel_SMS( 6349): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6349): MmsConfig.loadFromResources
E/Babel_SMS( 6349): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6349): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/dhcpcd  ( 6390): wlan0: rebinding lease of 192.168.1.134
D/SensorManager( 6349): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6349): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6349): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6349): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6349): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6349): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6349): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6349): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6349): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6349): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6349): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6349): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6349): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6349): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6349): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6349): found sensor: Motion Accel, handle=46
W/Settings( 6349): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  841): Explicit concurrent mark sweep GC freed 56446(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.472ms total 194.129ms
,I/Babel_Crash( 6349): startup - clean
I/dhcpcd  ( 6390): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6390): wlan0: leased 192.168.1.134 for 86400 seconds
,I/art     ( 6349): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/Babel   ( 6349): deleted: false for 0
,I/art     ( 6349): CheckpointMarkThreadRoots callback created = 0xb042d880
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
W/AudioCapabilities( 6349): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6323): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6323): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6323): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6349): Unsupported mime audio/adpcm
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
W/AudioCapabilities( 6349): Unsupported mime audio/g726
I/PCSuite ( 6323): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6323): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6323): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6349): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6349): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6349): Unsupported mime video/mjpg
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6349): Unsupported mime video/theora
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6295): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] DNSResolver start dns
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
W/AudioCapabilities( 6349): Unsupported mime audio/evrc
W/AudioCapabilities( 6349): Unsupported mime audio/qcelp
,I/DSQN    ( 6379): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6379): restart monitoring
W/VideoCapabilities( 6349): Unrecognized profile 2130706433 for video/avc
I/DSQN    ( 6379): dsqn report finish
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  841): DSQM DsqnNotification wlan0  1
D/DSQN    (  841): start to monitor internet connection
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
W/AudioCapabilities( 6349): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6349): Unsupported mime audio/qcelp
W/AudioCapabilities( 6349): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 16:44:11 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453394651026], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453394651002]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Validated
D/ConnectivityService(  841): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  841): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  841): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  841): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  841): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  841): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1802): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
D/TelephonyNetworkFactory-1( 1802):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6349): Unsupported mime video/mp4v-esdp
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
,I/VideoCapabilities( 6349): Unsupported profile 4 for video/mp4v-es
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6349): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6349): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6349): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  841): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  841): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  841): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  841): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  841): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  841): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  841): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  841): RunningState
W/VideoCapabilities( 6349): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 6323): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/vclib   ( 6349): onServiceConnected
,W/Babel   ( 6349): Attempted to change video mute state without an active call.
D/PCSuite ( 6323): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager( 6349): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
,I/PCSuite ( 6323): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6323): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  841): Killing 5799:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10069/pid_5799/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  841): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,I/QCNEJ   ( 1913): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:11.44 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  841): identical MTU - not setting
D/Nat464Xlat(  841): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  841): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  841): enableDataServiceNotify 
D/DSQN    (  841): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524295
D/DSQN    (  841): dsqn is running restart
,I/DSQN    ( 6424): DSQN samuel.seo ver 141203
,E/DSQN    ( 6424): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6424): created command queue thread
I/DSQN    ( 6424): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6424): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{3203bf4c type 2 when 101959 com.google.android.gms} when 101959
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1771): propertyValue:false
,I/DSQN    ( 6424): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6424): restart monitoring
D/LGDataListener(  273): argv[0]=dsqncommand
,D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6424): dsqn report finish
D/DSQN    (  841): DSQM DsqnNotification wlan0  1
D/DSQN    (  841): start to monitor internet connection
D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6436 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  841): onReceive
D/LocSvc_java(  841): got connectivity action
,D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  841): broadcast - no network connections
D/LocSvc_java(  841): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  841): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  841): onReceive
D/LocSvc_java(  841): got connectivity action
D/LocSvc_java(  841): broadcast - no network connections
D/LocSvc_java(  841): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  841): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  841): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  841): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  841): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  841): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  841): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  841): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  485): init target 500000
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,I/MusicStore( 6436): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  841): Process com.google.android.gms:car (pid 6073) has died
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6436): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6436): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6436): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6436): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c21ee65: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6436): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6436): GMSCore installation verified
,I/ConfigStore( 6436): Config Database version: 1
,I/ActivityManager(  841): Process com.google.android.gm (pid 5839) has died
,I/MediaRouter( 6436): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6436): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6436): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6436): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6479 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6436): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6436): Using platform SSLCertificateSocketFactory
I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  841): Process com.google.android.gms (pid 3958) has died
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 22
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/ResourcesManager( 6479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6479): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6479): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  841): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6503 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/WifiInternetCheck(  841): Single check msg out of sync, ignoring.
,I/QCNEJ   ( 1913): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:44:13.37 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  841): onReceive
D/LocSvc_java(  841): got connectivity action
D/LocSvc_java(  841): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  841): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  841): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  841): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  841): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 6436): type=WIFI subType= reason=null isConnected=true
W/ResourcesManager( 6503): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6503): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6503): VM with version 2.1.0 has multidex support
I/MultiDex( 6503): install
I/MultiDex( 6503): VM has multidex support, MultiDex support library is disabled.
,D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGEmail ( 6479): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6479): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/NotificationManager( 2028): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  841): Process com.android.vending (pid 5602) has died
,V/JNIHelp ( 6503): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/eas_req ( 6479): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/ActivityThread( 6503): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6503): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3eb0c218: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6503): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6503): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6503): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6535 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/NotificationManager( 6436): com.google.android.music: cancel(1061) by com.google.android.music
,I/HubEmail( 6479): JNI_OnLoad()
I/HubEmail( 6479): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6479): registerNatives()
I/HubEmail( 6479): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6479): registerNativeMethods()
I/HubEmail( 6479): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6479): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6479): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6535): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6535): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/NativeLibraryUtils( 6503): Install completed successfully. count=14 extracted=0
D/LGDMClient( 6535): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6535): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6535): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6535): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6562 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6535): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6535): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6535): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6535): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6535): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6562): onCreate
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AppUp4:DB( 6562):  [AppBoxDatabaseHelper] construct
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
I/AppUp4:DB( 6562):  setFingerPrint start
I/AppUp4:DB( 6562):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6562):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6562):  SDK version = 0
I/AppUp4:DB( 6562):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6562): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6562): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6562): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6562): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6562): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6562): onReceive
I/AppUp4:CustModeStarterReceiver( 6562): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6562): Context : android.app.ReceiverRestrictedContext@30177979
D/AppUp4:CustFacade( 6562): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6562): isSimDevice : true
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
D/AppUp4:CustModeStarterReceiver( 6562): begin check event
I/System.out(  841): propertyValue:false
I/AppUp4:CustModeStarterReceiver( 6562): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6562): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/AppUp4:CustModeStarterReceiver( 6562): call method handleAsyncCustNotification.
,D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AppUp4:CustModeStarterReceiver( 6562): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6562): handleAsyncCustNotification do not startCustService
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/ActivityManager(  841): Killing 6349:com.google.android.talk/u0a61 (adj 15): empty #11
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
,V/WifiInternetCheck(  841): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_6349/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3477): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3477): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3477): networkInfo.isConnected() = false
,I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6590 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 294us total 24.876ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 33.873ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.230ms
,D/PhoneMonitor( 6590): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6590): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6590): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  841): Killing 6295:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6295/cgroup.procs: No such file or directory
,V/DownloadManager( 2856): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 2856): DownloadService onCreate
,I/DownloadManager( 2856): in removeSpuriousFiles
I/NotificationManager( 2856): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/PhoneMonitor( 6590): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 2856): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@1a4b2dcd on behalf of 2856
V/TelephonyAutoProfiling( 6590): [loadFeatureFromXml] *** start feature loading from xml
,I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6628 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 2856): DownloadService onStartCommand
,D/TelephonyAutoProfiling( 6590): [parse] Load xml
V/TelephonyAutoProfiling( 6590): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6590): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 2856): in trimDatabase
V/DownloadManager( 2856): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@10e715d0 on behalf of 2856
V/DownloadManager( 2856): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@9e9d9c9 on behalf of 2856
,D/PhoneMonitor( 6590): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinService( 6503): Checkin interval check for package: unspecified last checkin: 1453394630787 min interval config: 0 actual interval: 24590
I/CheckinService( 6503): Disabling old GoogleServicesFramework version
,V/DownloadManager( 2856): DownloadService onDestroy
,D/WeatherAncestor( 2711): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:15
I/CheckinService( 6503): Checking schedule, now: 1453394655458 next: 1453394660717
I/CheckinService( 6503): active receiver: disabled
D/UpdateThreadPoolManager( 2711): 2 : This is isUpdating : false
D/WeatherAncestor( 2711): connectivity changed - connection : true
D/Weather_cast( 2711): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2711): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:15
D/WeatherService( 2711): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6655 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2711): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2711): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2711): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  841): Killing 6007:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5082): android.os.DeadObjectException
,W/System.err( 5082): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5082): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5082): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5082): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5082): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5082): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5082): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5082): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5082): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5082): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5082): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5082): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5082): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5082): android.os.DeadObjectException
W/System.err( 5082): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5082): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5082): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5082): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5082): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5082): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5082): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5082): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5082): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5082): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5082): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5082): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5082): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  841): failed to kill 1 processes for processgroup 6007
,W/ActivityManager(  841): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6678 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6678): Quickset Services start...
I/UEI.SmartControl( 6678): Manufacture = LGE
,D/UEI.SmartControl( 6678): File observer start...
,E/UEI.SmartControl( 6678): IR Port is disabled: false
D/UEI.SmartControl( 6678): Starting file observer...
D/UEI.SmartControl( 6678): Extracting JNI libs...
D/UEI.SmartControl( 6678): --- this system supports 32-bit or 64-bit only
,I/Babel_SMS( 6655): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6655): MmsConfig.loadMmsSettings
I/Babel_SMS( 6655): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6655): MmsConfig.loadFromDatabase
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,E/Babel_SMS( 6655): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6655): MmsConfig.loadFromResources
E/Babel_SMS( 6655): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6655): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/UEI.SmartControl( 6678): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6678): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6678): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/SensorManager( 6655): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6655): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6655): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6655): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6655): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6655): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6655): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6655): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6655): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6655): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6655): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6655): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6655): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6655): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6655): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6655): found sensor: Motion Accel, handle=46
I/UEI.SmartControl( 6678): --- Selecting new region: 2
I/UEI.SmartControl( 6678): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6678): Platform has CIR...
,D/UEI.SmartControl( 6678): NO CIR support, need to check package...
I/UEI.SmartControl( 6678): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6678): QS Service created
W/Settings( 6655): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6655): startup - clean
E/UEI.SmartControl( 6678): QS start get config
I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6172): 
,I/art     ( 6655): CheckpointMarkThreadRoots callback created = 0xb042d4d0
,I/Babel   ( 6655): deleted: false for 0
,D/UEI.SmartControl( 6678): Loading JNI Libs...
,D/UEI.SmartControl( 6678):  configuring local db...
I/art     ( 6655): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/ActivityManager(  841): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6718 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6655): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6655): Unsupported mime audio/adpcm
W/AudioCapabilities( 6655): Unsupported mime audio/g726
,W/AudioCapabilities( 6655): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6655): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6655): Unsupported mime video/mjpg
W/VideoCapabilities( 6655): Unsupported mime video/theora
,W/AudioCapabilities( 6655): Unsupported mime audio/evrc
,W/AudioCapabilities( 6655): Unsupported mime audio/qcelp
W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6655): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6655): Unsupported mime audio/qcelp
W/AudioCapabilities( 6655): Unsupported mime audio/evrc
,W/VideoCapabilities( 6655): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6655): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  841): Process com.google.android.music:main (pid 6436) has died
W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6655): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6655): onServiceConnected
W/Babel   ( 6655): Attempted to change video mute state without an active call.
,D/UEI.SmartControl( 6678):  ---- Has DB8: true
D/UEI.SmartControl( 6678): QS start statue = true Error code = 0
D/UEI.SmartControl( 6678): QS version = v2.7.11.1_RC1
,I/NotificationManager( 6655): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/UEI.SmartControl( 6678): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6678): IRRCDataComm has AudioManager!!!!.
,D/libc-netbsd( 6655): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6655): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6655): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6655): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6655): propertyValue:false
W/irrc_jni( 6678): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6678): IrrcClient ++ 
D/irrcClient( 6678): getIrrcService ++ 
D/irrcClient( 6678): getIrrcService -- 
D/irrcClient( 6678): IrrcClient -- 
W/irrc_jni( 6678): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6678): Services init done
,I/UEI.SmartControl( 6678): Device manager: loading config....
D/UEI.SmartControl( 6678): QS Service init finished
D/UEI.SmartControl( 6678): QS Service version name: 0.1.73
D/UEI.SmartControl( 6678): QS Service version code: 1073
D/UEI.SmartControl( 6678): Service requested: Control
D/UEI.SmartControl( 6678): Config is loaded...
,D/UEI.SmartControl( 6678):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6678): Notify AllClients services are ready: 0
I/Babel   ( 6655): connection state changed from UNKNOWN to CONNECTED
,D/UEI.SmartControl( 6678): Request IControl service: devices are loaded...
,I/ActivityManager(  841): Killing 6323:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6678): -----IControl: 11
D/UEI.SmartControl( 6678): Caller: com.lge.qremote
D/UEI.SmartControl( 6678): ------------ IControl registerCallback...
I/UEI.SmartControl( 6678): Registering callback...
D/UEI.SmartControl( 6678): -----IControl: 19
D/UEI.SmartControl( 6678): Caller: com.lge.qremote
I/UEI.SmartControl( 6678): Registering Services Ready callback...
I/UEI.SmartControl( 6678): Notify client services are ready...
D/UEI.SmartControl( 6678): -----IControl: 8
D/UEI.SmartControl( 6678): Caller: com.lge.qremote
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6323/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6678): Internal service binding...
,I/art     (  841): Explicit concurrent mark sweep GC freed 44279(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.218ms total 167.281ms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/GAv4    ( 6718): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6718):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6718):   adb logcat -s GAv4
,W/GAv4    ( 6718): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6718): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6718): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  841): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6753 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{44e7288 type 0 when 1453394657508 com.android.vending} when 1453394657508
,I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6172): 
,D/Finsky  ( 6753): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6172): 
I/WebViewFactory( 6718): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  841): Process com.lge.email (pid 6479) has died
,I/LibraryLoader( 6718): Time to load native libraries: 2 ms (timestamps 8295-8297)
I/LibraryLoader( 6718): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6718): Binding Chromium to main looper Looper (main, tid 1) {28583432}
I/LibraryLoader( 6718): Expected native library version number "",actual native library version number ""
I/chromium( 6718): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/Finsky  ( 6753): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/BrowserStartupController( 6718): Initializing chromium process, singleProcess=true
,W/art     ( 6718): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6718): ApplicationContext is null in ApplicationStatus
W/Settings( 6753): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6753): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6753): com.android.vending: cancel(-1050172287) by com.android.vending
,I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6172): 
,W/chromium( 6718): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
V/DownloadManager( 2856): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,E/libEGL  ( 6718): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6718): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6718): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6718): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6718): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6718): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6718): Remote Branch: 
I/Adreno-EGL( 6718): Local Patches: 
I/Adreno-EGL( 6718): Reconstruct Branch: 
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@34fb53ef on behalf of 6753
D/Ads     ( 6753): Skipping gmscore version check
,D/Finsky  ( 6753): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6753): [1] Libraries$2.run: Finished loading 1 libraries.
I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6172): 
D/Finsky  ( 6753): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6172): 
I/jxcore-log( 6172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6172): 
,D/Finsky  ( 6753): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/AudioPolicyService(  278): registerClient() client 0xb57e74c0, uid 10079
,W/AudioManagerAndroid( 6718): Requires BLUETOOTH permission
I/NSApplication( 6718): Starting up...
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
I/ActivityManager(  841): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6831 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{1d15d4e8 type 0 when 1453394658413 com.google.android.googlequicksearchbox} when 1453394658413
,D/Finsky  ( 6753): [815] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6753): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  841): Killing 5082:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10106/pid_5082/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6855 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6535:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6535/cgroup.procs: No such file or directory
,W/ResourcesManager( 6855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6172): Test app app.js loaded
I/jxcore-log( 6172): 
,I/chromium( 6172): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6172): BLE advertisement is supported
I/jxcore-log( 6172): 
,I/iu.SyncManager( 6503): SYNC; picasa accounts
,D/NetworkLogImpl( 6503): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6503): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  841): Killing 6562:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/iu.UploadsManager( 6503): num queued entries: 0
I/iu.UploadsManager( 6503): num updated entries: 0
I/iu.SyncManager( 6503): NEXT; no task
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_6562/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6897 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Process com.google.android.talk (pid 6655) has died
,I/MusicStore( 6897): Database version: 120
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6897): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6897): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6897): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c21ee65: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6897): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6897): GMSCore installation verified
I/ConfigStore( 6897): Config Database version: 1
,I/MediaRouter( 6897): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6897): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6897): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NetworkMonitor( 6897): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6928 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6897): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6897): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6928): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6928): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6928): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 6897): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 6928): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6928): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6928): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6928): JNI_OnLoad()
I/HubEmail( 6928): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6928): registerNatives()
,I/HubEmail( 6928): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6928): registerNativeMethods()
I/HubEmail( 6928): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6928): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink,
I/ActivityManager(  841): Killing 6590:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_6590/cgroup.procs: No such file or directory
W/Settings( 6928): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6951): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6951): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6951): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6951): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6951): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6951): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6975 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 299us total 34.004ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.565ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.770ms
,I/ActivityManager(  841): Process com.google.android.apps.magazines (pid 6718) has died
,W/ContextImpl( 6951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6951): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6951): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6951): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6951): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6951): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 6975): onCreate
,W/AppUp4:DB( 6975):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6975):  setFingerPrint start
,I/AppUp4:DB( 6975):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6975):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6975):  SDK version = 0
I/AppUp4:DB( 6975):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6975): AppBoxApplication onCreate()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NetworkStateForAutoUpdateMonitor( 6975): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6975): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6975): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6975): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6975): onReceive
I/AppUp4:CustModeStarterReceiver( 6975): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6975): Context : android.app.ReceiverRestrictedContext@30177979
D/AppUp4:CustFacade( 6975): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6975): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6975): begin check event
,I/AppUp4:CustModeStarterReceiver( 6975): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6975): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6975): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6975): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6975): handleAsyncCustNotification do not startCustService
I/ActivityManager(  841): Killing 6628:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_6628/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3477): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3477): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3477): networkInfo.isConnected() = false
,I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7004 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7004): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7004): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7004): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  841): Killing 6678:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/PhoneMonitor( 7004): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7004): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7004): [parse] Load xml
,V/TelephonyAutoProfiling( 7004): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7004): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7004): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_6678/cgroup.procs: No such file or directory
,V/DownloadManager( 2856): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 2856): DownloadService onCreate
I/NotificationManager( 2856): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 2856): in removeSpuriousFiles
,V/DownloadManager( 2856): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@3aad4985 on behalf of 2856
I/DownloadManager( 2856): in trimDatabase
V/DownloadManager( 2856): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@2a0d03da on behalf of 2856
I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7032 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 2856): DownloadService onStartCommand
V/DownloadManager( 2856): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@b77cee8 on behalf of 2856
I/CheckinService( 6503): Checkin interval check for package: unspecified last checkin: 1453394630787 min interval config: 0 actual interval: 30980
I/CheckinService( 6503): Checking schedule, now: 1453394661780 next: 1453394660717
I/CheckinService( 6503): active receiver: enabled
,V/DownloadManager( 2856): DownloadService onDestroy
I/CheckinService( 6503): Preparing to send checkin request
I/EventLogService( 6503): Accumulating logs since 1453394622729
,D/WeatherAncestor( 2711): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:21
,D/UpdateThreadPoolManager( 2711): 2 : This is isUpdating : false
D/WeatherAncestor( 2711): connectivity changed - connection : true
D/Weather_cast( 2711): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2711): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:21
D/WeatherService( 2711): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7055 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2711): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2711): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2711): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7055): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 6503): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6503): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (  841): Explicit concurrent mark sweep GC freed 24847(1194KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.209ms total 145.801ms
,I/NotificationManager( 6503): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Babel_SMS( 7055): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7055): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7055): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7055): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7055): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7055): MmsConfig.loadFromResources
E/Babel_SMS( 7055): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7055): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7055): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7055): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7055): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7055): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7055): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7055): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7055): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7055): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7055): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7055): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7055): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
,D/SensorManager( 7055): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7055): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7055): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7055): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7055): found sensor: Motion Accel, handle=46
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/Settings( 7055): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7055): startup - clean
I/CheckinRequestBuilder( 6503): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 6503): Failed to find provider info for com.google.android.wearable.settings
,I/Babel   ( 7055): deleted: false for 0
I/art     ( 7055): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/art     ( 7055): CheckpointMarkThreadRoots callback created = 0xb042d830
,I/ActivityManager(  841): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7093 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7055): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7055): Unsupported mime audio/adpcm
W/AudioCapabilities( 7055): Unsupported mime audio/g726
W/AudioCapabilities( 7055): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7055): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7055): Unsupported mime video/mjpg
,W/VideoCapabilities( 7055): Unsupported mime video/theora
W/AudioCapabilities( 7055): Unsupported mime audio/evrc
,W/AudioCapabilities( 7055): Unsupported mime audio/qcelp
W/VideoCapabilities( 7055): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7055): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7055): Unsupported mime audio/qcelp
W/AudioCapabilities( 7055): Unsupported mime audio/evrc
I/art     ( 3677): Explicit concurrent mark sweep GC freed 2613(101KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 417us total 73.658ms
,W/VideoCapabilities( 7055): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7055): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7055): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7055): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7055): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7055): Unrecognized profile 2130706433 for video/avc
I/MusicWidget( 2684): mDelayedStopHandler : unbind
,I/vclib   ( 7055): onServiceConnected
,W/Babel   ( 7055): Attempted to change video mute state without an active call.
I/NotificationManager( 7055): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 7055): propertyValue:false
I/MusicBrowser( 2116): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2116): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2116): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2116): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2116): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2116): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2116): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2116): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/Babel   ( 7055): connection state changed from UNKNOWN to CONNECTED
I/MediaFocusControl(  841):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@388cb2e9com.lge.music.MediaPlaybackService$6@3ba15b6e
,I/ActivityManager(  841): Killing 6753:com.android.vending/u0a36 (adj 15): empty #11
D/MusicBrowser( 2116): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,W/libprocessgroup(  841): failed to open /acct/uid_10036/pid_6753/cgroup.procs: No such file or directory
,I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/ActivityManager(  841): Process com.google.android.music:main (pid 6897) has died
,I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2116): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@40d3435
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2116): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2116): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2116): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2116): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/MusicBrowser( 2116): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2116): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2116): [MediaPlaybackService.java:6706:stop()] oooooo 
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/MediaPlayer[Native]( 2116): reset
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
V/MediaPlayer[Native]( 2116): setListener
V/MediaPlayer[Native]( 2116): disconnect
V/MediaPlayer[Native]( 2116): destructor
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/AudioFlinger(  278): releasing 19 from 2116 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2116): disconnect
D/MusicBrowser( 2116): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2116): [SmartShareManagerClient] smartshare client supported version code: 305010
I/GAv4    ( 7093): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7093):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7093):   adb logcat -s GAv4
I/SmartShareClient( 2116): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2116): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2116): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2116): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2116): [SmartShareManagerClient] unregisterListener: 849584655
W/SmartShareClient( 2116): [SmartShareManagerClient] unregisterListener invalid listener: 849584655
I/SmartShareClient( 2116): [SmartShareManagerClient] terminate service: 2116/MediaPlaybackService/886504899
E/HomeCloudIF( 2116): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2116): [SmartShareManagerClient] unbindService context:android.app.Application@11a6c29c
V/CloudHub( 2116): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2116): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
W/GAv4    ( 7093): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/CloudHub( 2116): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2116): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2116): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2116): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/GAv4    ( 7093): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7093): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  841): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7126 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7126): VM with version 2.1.0 has multidex support
I/MultiDex( 7126): install
,I/MultiDex( 7126): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,W/ActivityThread( 7126): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7126): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13852682: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7126): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7126): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7126): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7126): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7126): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WebViewFactory( 7093): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 7093): Time to load native libraries: 2 ms (timestamps 3693-3695)
I/LibraryLoader( 7093): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7093): Binding Chromium to main looper Looper (main, tid 1) {28583432}
,I/LibraryLoader( 7093): Expected native library version number "",actual native library version number ""
I/chromium( 7093): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7093): Initializing chromium process, singleProcess=true
,W/art     ( 7093): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7093): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  841): Process com.lge.email (pid 6928) has died
D/NativeLibraryUtils( 7126): Install completed successfully. count=14 extracted=0
,W/chromium( 7093): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7093): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7093): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7093): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7093): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7093): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7093): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7093): Remote Branch: 
I/Adreno-EGL( 7093): Local Patches: 
I/Adreno-EGL( 7093): Reconstruct Branch: 
D/WVCdm   (  278): Instantiating CDM.
I/WVCdm   (  278): CdmEngine::OpenSession
,I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,V/AudioPolicyService(  278): registerClient() client 0xb57e7440, uid 10079
,W/AudioManagerAndroid( 7093): Requires BLUETOOTH permission
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/NSApplication( 7093): Starting up...
W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=2423985159
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 114028369127; DSPS: 3834279; Offset : -2991706576
,I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7181 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7126): CheckpointMarkThreadRoots callback created = 0xb04cbe10
,I/art     ( 7126): CheckpointMarkThreadRoots callback created = 0xb04cbe00
,I/MusicStore( 7181): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WVCdm   (  278): CdmEngine::OpenSession
,V/JNIHelp ( 7181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7181): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c21ee65: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7181): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7181): GMSCore installation verified
,I/ActivityManager(  841): Process com.lge.appbox.client (pid 6975) has died
,I/ConfigStore( 7181): Config Database version: 1
,I/MediaRouter( 7181): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7181): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7181): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7181): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7214 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7181): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7181): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7214): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7214): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 7181): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7214): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7214): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7214): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 6951): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6951): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6951): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/HubEmail( 7214): JNI_OnLoad()
I/HubEmail( 7214): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7214): registerNatives()
I/HubEmail( 7214): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7214): registerNativeMethods()
I/HubEmail( 7214): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7214): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/LGDMClient( 6951): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 6951): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6951): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7240 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7214): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 6951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6951): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6951): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6951): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6951): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6951): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  841): Killing 7004:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7240): onCreate
W/AppUp4:DB( 7240):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7240):  setFingerPrint start
I/AppUp4:DB( 7240):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7240):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7240):  SDK version = 0
I/AppUp4:DB( 7240):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_7004/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7240): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7240): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7240): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7240): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7240): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7240): onReceive
I/AppUp4:CustModeStarterReceiver( 7240): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7240): Context : android.app.ReceiverRestrictedContext@30177979
D/AppUp4:CustFacade( 7240): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7240): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7240): begin check event
I/AppUp4:CustModeStarterReceiver( 7240): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7240): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7240): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7240): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7240): handleAsyncCustNotification do not startCustService
I/ActivityManager(  841): Killing 7032:com.lge.drmservice/u0a51 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_7032/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3477): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3477): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3477): networkInfo.isConnected() = true
D/PhoneState( 3477): setPdpRejectCasuse : false
I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7259 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7259): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7259): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7259): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  841): Killing 7093:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 7259): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7259): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7259): [parse] Load xml
V/TelephonyAutoProfiling( 7259): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7259): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7259): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=408649036
W/libprocessgroup(  841): failed to open /acct/uid_10079/pid_7093/cgroup.procs: No such file or directory
,V/DownloadManager( 2856): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 2856): DownloadService onCreate
I/NotificationManager( 2856): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 2856): in removeSpuriousFiles
V/DownloadManager( 2856): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@5f3d1e7 on behalf of 2856
I/DownloadManager( 2856): in trimDatabase
V/DownloadManager( 2856): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7285 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 2856): DownloadService onStartCommand
,I/CheckinService( 6503): Checkin interval check for package: unspecified last checkin: 1453394630787 min interval config: 0 actual interval: 35254
V/DownloadManager( 2856): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager(  841): Killing 2116:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  278): 2116 died, releasing its sessions
V/AudioFlinger(  278):  pid 1802 @ 0
V/AudioFlinger(  278):  pid 3477 @ 1
V/AudioFlinger(  278):  pid 3477 @ 2
,I/art     (  841): Explicit concurrent mark sweep GC freed 17605(813KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.825ms total 218.154ms
,V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@1350243d on behalf of 2856
,V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@28583432 on behalf of 2856
W/libprocessgroup(  841): failed to open /acct/uid_10028/pid_2116/cgroup.procs: No such file or directory
D/WeatherAncestor( 2711): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:26
,V/DownloadManager( 2856): DownloadService onDestroy
D/UpdateThreadPoolManager( 2711): 2 : This is isUpdating : false
D/WeatherAncestor( 2711): connectivity changed - connection : true
D/Weather_cast( 2711): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2711): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:26
D/WeatherService( 2711): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2711): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2711): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2711): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  841): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7313 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 20.852ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.670ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.550ms
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7313): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7313): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7313): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7313):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7313):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7313): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7313): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7313): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7313): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7313): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7313): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7313): Time to load native libraries: 2 ms (timestamps 7013-7015)
,I/LibraryLoader( 7313): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7313): Binding Chromium to main looper Looper (main, tid 1) {28583432}
I/LibraryLoader( 7313): Expected native library version number "",actual native library version number ""
I/chromium( 7313): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7313): Initializing chromium process, singleProcess=true
W/art     ( 7313): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7313): ApplicationContext is null in ApplicationStatus
W/chromium( 7313): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7313): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7313): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7313): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7313): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7313): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7313): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7313): Remote Branch: 
I/Adreno-EGL( 7313): Local Patches: 
I/Adreno-EGL( 7313): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb281dba0, uid 10079
,W/AudioManagerAndroid( 7313): Requires BLUETOOTH permission
I/NSApplication( 7313): Starting up...
,I/ActivityManager(  841): Killing 7181:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10081/pid_7181/cgroup.procs: No such file or directory
,D/WearableService( 1771): callingUid 10006, callindPid: 1771
,E/MDM     ( 1771): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1771): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6503): Restart initialization of location
V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1771): com.google.android.gms: cancel(0) by com.google.android.gms
,D/GCM     ( 1771): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GCoreFlp( 1771): No location to return for getLastLocation()
W/FusedLocationProvider( 1771): location=null
I/ActivityManager(  841): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7387 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/IcingInternalCorpora( 6503): getNumBytesRead when not calculated.
,W/ResourcesManager( 7387): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf6f2f5:true
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7412 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7387): Create singleton instance
,I/AudioManager( 7387): getMode name:com.lge.qremote
,E/MDM     ( 1771): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6503): Restart initialization of location
D/AuthorizationBluetoothService( 1771): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1771): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7387): getMode name:com.lge.qremote
W/GCoreFlp( 1771): No location to return for getLastLocation()
W/FusedLocationProvider( 1771): location=null
,W/ContextImpl( 3252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/UEI.SmartControl( 7412): Quickset Services start...
,I/UEI.SmartControl( 7412): Manufacture = LGE
D/UEI.SmartControl( 7412): File observer start...
E/UEI.SmartControl( 7412): IR Port is disabled: false
D/UEI.SmartControl( 7412): Starting file observer...
D/UEI.SmartControl( 7412): Extracting JNI libs...
D/UEI.SmartControl( 7412): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7412): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7412): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7412): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7412): --- Selecting new region: 2
I/UEI.SmartControl( 7412): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7412): Platform has CIR...
,D/UEI.SmartControl( 7412): NO CIR support, need to check package...
I/UEI.SmartControl( 7412): Model: LG-D722 uses JNI
I/WVCdm   (  278): CdmEngine::CloseSession
D/UEI.SmartControl( 7412): QS Service created
I/WVCdm   (  278): L3 Terminate.
,E/UEI.SmartControl( 7412): QS start get config
,D/UEI.SmartControl( 7412): Loading JNI Libs...
,D/UEI.SmartControl( 7412):  configuring local db...
I/dex2oat ( 7452): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/dex2oat ( 7452): dex2oat took 218.318ms (threads: 4)
,I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
,D/UEI.SmartControl( 7412):  ---- Has DB8: true
D/UEI.SmartControl( 7412): QS start statue = true Error code = 0
D/UEI.SmartControl( 7412): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7412): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7412): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7412): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7412): IrrcClient ++ 
D/irrcClient( 7412): getIrrcService ++ 
D/irrcClient( 7412): getIrrcService -- 
,D/irrcClient( 7412): IrrcClient -- 
W/irrc_jni( 7412): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7412): Services init done
I/UEI.SmartControl( 7412): Device manager: loading config....
D/UEI.SmartControl( 7412): QS Service init finished
D/UEI.SmartControl( 7412): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7412): QS Service version code: 1073
D/UEI.SmartControl( 7412): Config is loaded...
D/UEI.SmartControl( 7412): Service requested: Control
D/UEI.SmartControl( 7412): Internal service binding...
D/UEI.SmartControl( 7412): -----IControl: 11
D/UEI.SmartControl( 7412): Caller: com.lge.qremote
D/UEI.SmartControl( 7412): ------------ IControl registerCallback...
I/UEI.SmartControl( 7412): Registering callback...
,D/UEI.SmartControl( 7412): -----IControl: 19
D/UEI.SmartControl( 7412): Caller: com.lge.qremote
I/UEI.SmartControl( 7412): Registering Services Ready callback...
I/UEI.SmartControl( 7412): Notify client services are ready...
D/UEI.SmartControl( 7412): -----IControl: 8
D/UEI.SmartControl( 7412): Caller: com.lge.qremote
D/UEI.SmartControl( 7412):  ----- QS SDK is ready!!!
,I/AudioManager( 7387): getMode name:com.lge.qremote
I/UEI.SmartControl( 7412): Notify AllClients services are ready: 0
I/ActivityManager(  841): Killing 6951:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/ActivityManager(  841): Killing 7214:com.lge.email/u0a21 (adj 15): empty #12
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6951/cgroup.procs: No such file or directory
,W/libprocessgroup(  841): failed to open /acct/uid_10021/pid_7214/cgroup.procs: No such file or directory
I/AudioManager( 7387): getMode name:com.lge.qremote
I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
,I/AudioManager( 7387): getMode name:com.lge.qremote
,I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
,I/art     ( 6855): CheckpointMarkThreadRoots callback created = 0xb042d390
,I/art     ( 6855): CheckpointMarkThreadRoots callback created = 0xb042d380
I/CheckinRequestBuilder( 6503): Classify the device as Phone.
,D/libc-netbsd( 6503): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6503): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6503): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6503): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6503): propertyValue:false
,D/libc-netbsd( 6503): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6503): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6503): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6503): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6503): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6503): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinTask( 6503): Sending checkin request (9688 bytes)
I/art     ( 6503): Background sticky concurrent mark sweep GC freed 20848(1477KB) AllocSpace objects, 21(336KB) LOS objects, 13% free, 11MB/12MB, paused 9.366ms total 64.487ms
,I/CheckinRequestBuilder( 6503): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6503): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 6503): Classify the device as Phone.
,I/CheckinTask( 6503): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6503): Checking schedule, now: 1453394670134 next: 1453921919127
I/CheckinService( 6503): active receiver: disabled
,I/CheckinService( 6503): Checking schedule, now: 1453394670197 next: 1453921919127
I/CheckinService( 6503): active receiver: disabled
,D/CheckinService( 6503): Recording last checkin time for package unspecified as 1453394670206
V/SetupWizard( 7259): Connected to Gservices successfully
,D/GCM     ( 1771): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1913): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/ResourcesManager( 7055): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:CustModeStarterReceiver( 7240): onReceive
,I/AppUp4:CustModeStarterReceiver( 7240): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7240): Context : android.app.ReceiverRestrictedContext@30177979
D/AppUp4:CustFacade( 7240): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7240): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7240): begin check event
I/AppUp4:CustModeStarterReceiver( 7240): Event For Nothing, skip.
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7055): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  841): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7501 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/administrator(  841): Handling package changes for user 0
V/JNIHelp ( 7055): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7501): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7501): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7501): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 7055): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7055): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7501): Total System Memory = 906309632
,I/GalleryUtils( 7501): Application Heap = 96 MB
D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
,I/AppConfig( 7501): App Tier : NOT_DEF
D/SystemHelper( 7501): region [EU], country [EU], operator [OPEN], sub-operator []
,I/NotificationService(  841): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  841): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  841): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7522 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/BackupManagerService(  841): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/BackupManagerService(  841): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  841): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32e49776
,W/ResourcesManager( 7522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7522): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7522): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7522): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7522): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourceType(  841): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  841): Killing 7313:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/ActivityManager(  841): Killing 7285:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  841): failed to open /acct/uid_10079/pid_7313/cgroup.procs: No such file or directory
,W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_7285/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1771): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 7522): BUILD Country: EU
I/SystemConfig( 7522): BUILD Operator: OPEN
,I/art     (  841): Explicit concurrent mark sweep GC freed 28937(1461KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.085ms total 145.616ms
,D/LocationProviderProxy(  841): applying state to connected service
I/ActivityManager(  841): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7546 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6831:com.android.chrome/u0a48 (adj 15): empty #11
,I/SystemConfig( 7522): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7522): existFile = false
I/SystemConfig( 7522): canReadFile = false
I/SystemConfig( 7522): systemFeature RCS result false
D/SystemConfig( 7522): refreshRcsSupport() :false
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  841): failed to open /acct/uid_10048/pid_6831/cgroup.procs: No such file or directory
,I/LockScreenSettings( 7546): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7546): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7546): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7546): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7546): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7546): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 2028): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  841): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7568 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Process com.lge.qremote (pid 7387) has died
,I/UpdateIcingCorporaServi( 2028): UpdateCorporaTask done [took 105 ms] updated apps [took 105 ms] 
,D/UEI.SmartControl( 7412): Internal timer expired: 1
,D/UEI.SmartControl( 7412): Service.onUnbind: IControl
D/UEI.SmartControl( 7412): Service.onDestroy
D/UEI.SmartControl( 7412): Shutdown IRRCPlayer... 
W/irrc_jni( 7412): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7412): ~IrrcClient ++ 
D/irrcClient( 7412): ~IrrcClient -- 
W/irrc_jni( 7412): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7412): Blaster closed
D/UEI.SmartControl( 7412): Blaster closed
D/UEI.SmartControl( 7412): Shut down QS...
,D/UEI.SmartControl( 7412): Stopped file observer...
,I/UEI.SmartControl( 7412): QS lib stop result = true
D/UEI.SmartControl( 7412): QS shutdown complete
D/Finsky  ( 7568): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7568): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7568): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7568): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7568): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 2856): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2856): created cursor android.database.sqlite.SQLiteCursor@1b139300 on behalf of 7568
,D/Finsky  ( 7568): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7568): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7568): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7568): Skipping gmscore version check
,D/Finsky  ( 7568): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 6503): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  841): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7620 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 6503): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 7620): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     ( 3677): Explicit concurrent mark sweep GC freed 3127(126KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 386us total 34.236ms
,I/Icing   ( 6503): Storage manager: low false usage 1.73MB avail 2.36GB capacity 4.06GB
,I/ActivityManager(  841): Process com.google.android.gms.unstable (pid 7126) has died
,D/BluetoothManagerService(  841): Message: 20
,D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@303e9d9d:true
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/UEI.SmartControl( 7412): QS Service created
,E/UEI.SmartControl( 7412): QS start get config
,V/LGMDMManager( 7620): Create singleton instance
D/UEI.SmartControl( 7412):  configuring local db...
,I/AudioManager( 7620): getMode name:com.lge.qremote
,I/Icing   ( 6503): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 6503): CheckpointMarkThreadRoots callback created = 0x9a588990
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7412):  ---- Has DB8: true
,D/UEI.SmartControl( 7412): QS start statue = true Error code = 0
D/UEI.SmartControl( 7412): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7412): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7412): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7412): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7412): IrrcClient ++ 
D/irrcClient( 7412): getIrrcService ++ 
,D/irrcClient( 7412): getIrrcService -- 
D/irrcClient( 7412): IrrcClient -- 
W/irrc_jni( 7412): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7412): Services init done
I/UEI.SmartControl( 7412): Device manager: loading config....
D/UEI.SmartControl( 7412): QS Service init finished
D/UEI.SmartControl( 7412): QS Service version name: 0.1.73
D/UEI.SmartControl( 7412): QS Service version code: 1073
D/UEI.SmartControl( 7412): Service requested: Control
D/UEI.SmartControl( 7412): Config is loaded...
I/art     ( 6503): CheckpointMarkThreadRoots callback created = 0xaaff6ef0
,D/UEI.SmartControl( 7412):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7412): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7412): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7412): Internal service binding...
D/UEI.SmartControl( 7412): -----IControl: 11
D/UEI.SmartControl( 7412): File observer start...
E/UEI.SmartControl( 7412): IR Port is disabled: false
D/UEI.SmartControl( 7412): Starting file observer...
D/UEI.SmartControl( 7412): Caller: com.lge.qremote
D/UEI.SmartControl( 7412): ------------ IControl registerCallback...
I/UEI.SmartControl( 7412): Registering callback...
D/UEI.SmartControl( 7412): -----IControl: 19
D/UEI.SmartControl( 7412): Caller: com.lge.qremote
I/UEI.SmartControl( 7412): Registering Services Ready callback...
I/UEI.SmartControl( 7412): Notify client services are ready...
D/UEI.SmartControl( 7412): -----IControl: 8
D/UEI.SmartControl( 7412): Caller: com.lge.qremote
I/AudioManager( 7620): getMode name:com.lge.qremote
,I/AudioManager( 7620): getMode name:com.lge.qremote
,I/Icing   ( 6503): Internal init done: storage state 0
,I/Icing   ( 6503): Post-init done
I/Icing   ( 6503): updateResources: need to parse f{com.google.android.gms}
,I/AudioManager( 7620): getMode name:com.lge.qremote
I/CheckinService( 6503): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 6503): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 6503): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6503): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  841): Killing 7259:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_7259/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/charger_monitor(  485): init target 500000
,D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,D/WifiController(  841): battery changed pluggedType: 2
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  841): Killing 7055:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_7055/cgroup.procs: No such file or directory
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7412): Internal timer expired: 2
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 134029207661; DSPS: 4489667; Offset : -2991722144
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{38ee33c2 type 2 when 137216 android} when 137216
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{1b3d55d3 type 2 when 141106 com.google.android.gms} when 141106
,V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1771): Vacuum at: now=1453394691113 tag=VacuumService
,W/InstanceID/Rpc( 6503): Found 10006
,I/art     ( 1771): Explicit concurrent mark sweep GC freed 37280(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 1.533ms total 106.671ms
,I/PhenotypeConfigurator( 1771): Scheduling Phenotype for one-off execution 14043 seconds from now (1453394691644)
,D/GetConfigurationSnapshotOperation( 1771): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PhenotypeFlagCommitter( 1771): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1771): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1771): propertyValue:false
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1771): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1771): propertyValue:false
D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/NotificationManager( 1771): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  841): ALS enabled for SRE
,D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27354 ms ago)
D/qdlights(  841): set_light_backlight: 252
,D/qdlights(  841): set_light_backlight: 249
,D/qdlights(  841): set_light_backlight: 245
,D/qdlights(  841): set_light_backlight: 242
,D/qdlights(  841): set_light_backlight: 239
,D/qdlights(  841): set_light_backlight: 235
,D/qdlights(  841): set_light_backlight: 232
,D/qdlights(  841): set_light_backlight: 229
,D/qdlights(  841): set_light_backlight: 225
,D/qdlights(  841): set_light_backlight: 222
,D/qdlights(  841): set_light_backlight: 219
,D/qdlights(  841): set_light_backlight: 215
,D/qdlights(  841): set_light_backlight: 212
,D/qdlights(  841): set_light_backlight: 209
,D/qdlights(  841): set_light_backlight: 205
,D/qdlights(  841): set_light_backlight: 202
,D/qdlights(  841): set_light_backlight: 199
,D/qdlights(  841): set_light_backlight: 195
,D/qdlights(  841): set_light_backlight: 192
,D/qdlights(  841): set_light_backlight: 189
,D/qdlights(  841): set_light_backlight: 185
,D/qdlights(  841): set_light_backlight: 182
,D/qdlights(  841): set_light_backlight: 179
,D/qdlights(  841): set_light_backlight: 175
,D/qdlights(  841): set_light_backlight: 172
,D/qdlights(  841): set_light_backlight: 169
,D/qdlights(  841): set_light_backlight: 165
,D/qdlights(  841): set_light_backlight: 162
,D/qdlights(  841): set_light_backlight: 159
,D/qdlights(  841): set_light_backlight: 155
,D/qdlights(  841): set_light_backlight: 152
,D/qdlights(  841): set_light_backlight: 149
,D/qdlights(  841): set_light_backlight: 145
,D/qdlights(  841): set_light_backlight: 142
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  841): set_light_backlight: 139
,D/qdlights(  841): set_light_backlight: 135
,D/qdlights(  841): set_light_backlight: 132
,D/qdlights(  841): set_light_backlight: 129
,D/qdlights(  841): set_light_backlight: 125
,D/qdlights(  841): set_light_backlight: 122
,D/qdlights(  841): set_light_backlight: 119
,D/qdlights(  841): set_light_backlight: 115
,D/qdlights(  841): set_light_backlight: 112
,D/qdlights(  841): set_light_backlight: 109
,D/qdlights(  841): set_light_backlight: 105
,D/qdlights(  841): set_light_backlight: 102
,D/qdlights(  841): set_light_backlight: 99
,D/qdlights(  841): set_light_backlight: 95
,D/qdlights(  841): set_light_backlight: 92
,D/qdlights(  841): set_light_backlight: 89
,D/qdlights(  841): set_light_backlight: 85
,D/qdlights(  841): set_light_backlight: 82
,D/qdlights(  841): set_light_backlight: 79
,D/qdlights(  841): set_light_backlight: 75
,D/qdlights(  841): set_light_backlight: 72
,D/qdlights(  841): set_light_backlight: 69
,D/qdlights(  841): set_light_backlight: 65
,D/qdlights(  841): set_light_backlight: 62
,D/qdlights(  841): set_light_backlight: 59
,D/qdlights(  841): set_light_backlight: 55
,D/qdlights(  841): set_light_backlight: 52
,D/qdlights(  841): set_light_backlight: 49
,D/qdlights(  841): set_light_backlight: 45
,D/qdlights(  841): set_light_backlight: 42
,D/qdlights(  841): set_light_backlight: 39
,D/qdlights(  841): set_light_backlight: 35
,D/qdlights(  841): set_light_backlight: 32
,D/qdlights(  841): set_light_backlight: 29
,D/qdlights(  841): set_light_backlight: 25
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,D/qdlights(  841): set_light_backlight: 22
D/qdlights(  841): set_light_backlight: 19
,D/qdlights(  841): set_light_backlight: 15
,D/qdlights(  841): set_light_backlight: 12
,D/qdlights(  841): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=795360827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,D/WeatherService( 2711): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:45:0
,D/WeatherService( 2711): 2 : TimeTick Intent And Screen On
D/WeatherService( 2711): 2 : SDK version : 21
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2711): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2711): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2711): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2711): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2711): 2 : This is isUpdating : false
D/WeatherService( 2711): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2711): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2711): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2711): 2 : Fixed theme : optimus
D/WeatherReflect( 2711): 2 : Map key string is -2
,D/lim     ( 2711): 2 : time = 17:45
,I/WeatherReflect( 2711): Model Name : LG-D722
D/WeatherTheme( 2711): 2 : Different view - status_min_formatted : 44 != 45
D/WeatherTheme( 2711): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2711): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2711): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2711): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
,I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/Weather4x2_optimus( 2711): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2711): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2711): forecast size is 0
,D/Theme   ( 2711): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2711): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2711): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2711): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2711): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2711): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2711): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2711): url is : null
D/Theme   ( 2711): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2711): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2711): 2 : update view, appWidgetId: 2
,D/WeatherService( 2711): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:45:0
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=795360827 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  841): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7752 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/DigitalAppWidgetProvider( 7752): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7752): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1c26c572
I/ActivityManager(  841): Killing 7240:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_7240/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 154029872913; DSPS: 5145049; Offset : -2991728278
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34341 ms ago)
I/PowerManagerService(  841): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34353 ms ago)
W/ContextImpl(  841): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  841): Sleeping (uid 1000)...
D/LPWGController(  841): [updateScreenState] screen on = false
D/LPWGController(  841): disable proximity sensor
D/LPWGController(  841): enable proximity sensor
,I/SensorManager(  841): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@efaa958] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  841): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  841): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  841): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  841): activate: handle is 48, enable
V/sensors_hal_Ctx(  841): activate sensors is 1400000000000
D/sensors_hal_Thresh(  841): enable: handle=48
I/sensors_hal_SAM(  841): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  841): waitForResponse: timeout=1000
V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  841): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  841): enable: Received response: 0
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34394 ms ago)
I/Adreno-EGL(  841): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  841): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  841): Build Date: 03/02/15 Mon
I/Adreno-EGL(  841): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  841): Remote Branch: 
I/Adreno-EGL(  841): Local Patches: 
I/Adreno-EGL(  841): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (151 us)
,I/Sensors (  432): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  841): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  841): processInd: handle 48, count=1
V/sensors_hal_Thresh(  841): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  841): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  841): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  841): poll: count: 256
I/sensors_hal_Ctx(  841): poll: released wakelock sensor_ind
D/sensors_hal_Util(  841): waitForResponse: timeout=0
D/LPWGController(  841): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  841): current mode = 1  value = 1 1
I/LPWGController(  841): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  841): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  841): set_light_backlight: 0
,I/SensorManager(  841): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  841): activate: handle is 46, disable
V/sensors_hal_Ctx(  841): activate sensors is 1000000000000
D/sensors_hal_LP2(  841): enable: handle=46
D/sensors_hal_LP2(  841): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  841): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  841): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  841): Display changed displayId=0
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  841): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1802): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  841): Excessive delay in setPowerMode(): 194ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  841): Got set_interactive hint
D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1328): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1328): notifyScreenOffLocked
D/SmartCoverViewMediator( 1328): handleNotifyScreenOFF
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,D/WifiServerServiceExt(  841): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 841
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
I/WifiServerServiceExt(  841): set CMD_KT_SCAN_INTERVAL
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
,D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  841): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/SplitWindow(  841): check instance of lgWin Window{2928317 u0 SearchPanel}
,I/QCNEJ   ( 1913): |CORE| sendScreenState: state:true
,D/InputDispatcher(  841): Window went away: Window{57e05ce u0 SearchPanel}
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,I/LEDService( 1876): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1876): stopPatternFlashing()
D/LNfcService( 1859): action : android.intent.action.SCREEN_ON
,D/qdlights( 1876): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1876): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1876): set_light_notifications: 0,0,0,0,3
I/LEDService( 1876): updateLightsLocked : turn off led
D/qdlights( 1876): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1876): RESTART MSG
I/Cliptray Service( 1876): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/NfcServiceNXP( 1859): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1859): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1859): isRequireNfcCRouting() return true
D/LNfcService( 1859): isHCERoutingtoHost() return : true
D/NfcService( 1859): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): newParams.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): screenState= 3
D/NfcService( 1859): Discovery configuration equal, not updating.
D/Cliptray Service( 1876): lockStatus = 0
D/Ulp_jni (  841): JNI:system_update. Event-0
,V/PhoneApp( 1802): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  841): ACTION_SCREEN_ON
D/WeatherService( 2711): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:45:5
D/WeatherService( 2711): 2 : ACTION screen on
D/WeatherService( 2711): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2711): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2711): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:45:5
,D/AppCleanupService( 3794): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 841
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  841): CMD_SCREEN_OFF 
D/WifiController(  841): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  841): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1913): |CORE| sendScreenState: state:false
,I/LEDService( 1876): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1876): stopPatternFlashing()
D/qdlights( 1876): set_light_notifications: 0,0,0,0,3
I/LEDService( 1876): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1876): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1876): clear
I/LEDService( 1876): updateLightsLocked : turn on led
D/LNfcService( 1859): action : android.intent.action.SCREEN_OFF
E/LEDService( 1876): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1876): Can't handle this request of patternId:0
D/LEDHandler( 1876): RESTART MSG
I/Cliptray Service( 1876): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1859): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1950): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1802): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): ACTION_SCREEN_OFF
,D/WeatherService( 2711): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:45:5
D/WeatherService( 2711): 2 : ACTION screen off
D/WeatherService( 2711): 2 : TimeTick Receiver Unregister
D/WeatherService( 2711): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:45:5
D/AppCleanupService( 3794): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3794): AppUsageStatsSaveTask
,E/NxpNfcJni( 1859): getReconnectState = 0x0
,D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1859): getDefaultRoute
D/LNfcService( 1859): isRequireNfcCRouting() return true
D/LNfcService( 1859): isHCERoutingtoHost() return : true
D/NfcService( 1859): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): newParams.techmask= mTechMask: 0
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): screenState= 1
E/NxpNfcJni( 1859): getReconnectState = 0x0
,I/Sensors (  432): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{371d0304 type 2 when 160242 com.android.systemui} when 160242
,D/PhoneUtils( 1802): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1802): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1802): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1802): getCallState : 0
,D/PhoneUtils( 1802): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1802): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1802): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 174031002178; DSPS: 5800446; Offset : -2991728685
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{275db0ed type 2 when 185795 com.google.android.gms} when 185795
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1771): disconnect managed GoogleApiClient
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{131abb22 type 2 when 189962 android} when 189962
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 194031762066; DSPS: 6455831; Offset : -2991731555
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 214032509557; DSPS: 7111215; Offset : -2991716225
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 234033251634; DSPS: 7766599; Offset : -2991706726
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 254033940011; DSPS: 8421982; Offset : -2991720202
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 274034614691; DSPS: 9077364; Offset : -2991716726
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 294035377913; DSPS: 9732749; Offset : -2991716860
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/HeadsetStateMachine( 2080): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1876): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1876): Battery Level Remaining: 100%
D/LEDHandler( 1876): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 314036123217; DSPS: 10388133; Offset : -2991703718
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1876): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6172): TAP version 13
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # multiplex can send data
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 1 String should be length:200
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # enqueue and run in order
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 2 firstPromise setTimeout expected 0 and got 0
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 3 firstPromise result expected 10 and got 10
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 4 firstPromise testValue expected 10 and got 10
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 5 secondPromise setTimeout expected 10 and got 10
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 6 secondPromise result expected 100 and got 100
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 7 secondPromise testValue expected 100 and got 100
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 8 thirdPromise in promise expected 100 and got 100
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 9 thirdPromise result expected 1000 and got 1000
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 10 thirdPromise result expected 1000 and got 1000
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # basic
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 11 sane
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # another
I/jxcore-log( 6172): 
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 12 sane
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 13 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 14 null
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 15 (unnamed assert)
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 16 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 17 should not throw
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 18 (unnamed assert)
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 19 (unnamed assert)
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 20 should not throw
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 21 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 22 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 23 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # failed to get mobile documents path
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 24 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 25 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 26 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 27 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #init should register the networkChanged event
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 28 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startBroadcasting should throw on null device name
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 29 should throw
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 30 should throw
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 31 should throw
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 32 should throw
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startBroadcasting should throw on negative port
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 33 should throw
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startBroadcasting should throw on too large port
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 34 should throw
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 35 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 36 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 37 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 38 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 39 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 40 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 41 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 42 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 43 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 44 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 45 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 46 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 47 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
,I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/jxcore-log( 6172): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 48 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 49 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 50 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 51 should be equal
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 52 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 53 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880280.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880280.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 2080): [BTUI] createSocketChannel FD=87 mFd=85
I/bt-btif ( 2080): BTA_JvRfcommStartServer
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880280.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/art     (  841): Explicit concurrent mark sweep GC freed 55895(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.577ms total 152.597ms
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880280.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880280.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880280.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880280.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880280.6172
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 6172): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/LGWifiP2pService(  841): InactiveState{ when=-4ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@24ca7e4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
D/LGWifiP2pService(  841): P2pEnabledState{ when=-7ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@24ca7e4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  841): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): add a new client
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880589.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880589.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
,D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880589.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  841): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
D/LGWifiP2pService(  841): InactiveState{ when=-12ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-12ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880589.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880589.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880589.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880589.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  841): remove client information from framework
D/LGWifiP2pService(  841): InactiveState{ when=-33ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/LGWifiP2pService(  841): InactiveState{ when=-34ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-34ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e0b7a9cc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e0b7a9cc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880589.6172
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
I/jxcore-log( 6172): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/WfdsMonitor( 1876): Event [CTRL-EVENT-SCAN-STARTED ]
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.t,haliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880647.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  841): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880647.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880647.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880647.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880647.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880647.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880647.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ef2cca96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ef2cca96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880647.6172
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  841): discovery change broadcast true
I/jxcore-log( 6172): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/LGWifiP2pService(  841): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/jxcore-log( 6172): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880688.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880688.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880688.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880688.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880688.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880688.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880688.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b2d4dacc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b2d4dacc target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
D/LGWifiP2pService(  841): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
D/LGWifiP2pService(  841): add a new client
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880688.6172
,I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6172): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
I/bt-btif ( 2080): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/LGWifiP2pService(  841): discovery change broadcast true
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/LGWifiP2pService(  841): remove client information from framework
I/jxcore-log( 6172): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
D/LGWifiP2pService(  841): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880721.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880721.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880721.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880721.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880721.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880721.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880721.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f86ea9e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f86ea9e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880721.6172
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  841): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): discovery change broadcast false
I/jxcore-log( 6172): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
,D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
I/jxcore-log( 6172): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880759.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880759.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880759.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880759.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880759.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880759.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880759.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6a0dc90e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6a0dc90e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880759.6172
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  841): discovery change broadcast true
I/jxcore-log( 6172): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 2080): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/LGWifiP2pService(  841): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
,D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/jxcore-log( 6172): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880791.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880791.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880791.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880791.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880791.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880791.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880791.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5fa74616 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5fa74616 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
D/LGWifiP2pService(  841): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880791.6172
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
I/jxcore-log( 6172): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): set,State: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
,D/LGWifiP2pService(  841): InactiveState{ when=-3ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-3ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880830.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880830.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
,I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880830.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880830.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880830.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880830.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880830.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d94acca2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d94acca2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880830.6172
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/LGWifiP2pService(  841): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6172): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): Peer,DiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  841): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880871.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880871.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880871.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880871.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880871.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880871.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880871.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9cf2dcd8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9cf2dcd8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880871.6172
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
D/LGWifiP2pService(  841): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiP,eerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
I/jxcore-log( 6172): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  841): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
I/bt-btif ( 2080): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/bt-btif ( 2080): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841,): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
D/LGWifiP2pService(  841): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
I/jxcore-log( 6172): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880903.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880903.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880903.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394880903.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394880903.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394880903.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394880903.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a1dc4d60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a1dc4d60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394880903.6172
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 6172): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  841): discovery change broadcast true
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
D/LGWifiP2pService(  841): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/LGWifiP2pService(  841): remove client information from framework
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
I/jxcore-log( 6172): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 6172): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 334036892168; DSPS: 11043519; Offset : -2991728275
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394883882.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394883882.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
,I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394883882.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394883882.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394883882.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394883882.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394883882.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
,D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9f59c00e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9f59c00e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast true
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1876): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394883882.6172
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
,D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
I/jxcore-log( 6172): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
,I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394884639.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394884639.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394884639.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394884639.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394884639.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394884639.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394884639.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
,D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b15f64c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b15f64c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1876): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  841): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394884639.6172
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6172): start: OK
I/jxcore-log( 6172): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 6172): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 6172): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 6172): ok 78 Should not connect to a bad peer
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 6172): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394885168.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394885168.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6172): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2080): BTA_JvCreateRecordByUser
I/bt-btif ( 2080): BTA_JvRfcommStartServer
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): start: OK
I/io.jxcore.node.ConnectionHelper( 6172): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394885168.6172
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): createAdvertiseData: From: 1453394885168.6172 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6172): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6172): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6172): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6172): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453394885168.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): start: {"pi":"F8:95:C7:87:85:54","pn":"1453394885168.6172","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453394885168.6172","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Waiting for incoming connections...
,D/LGWifiP2pService(  841): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d70b01d0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d70b01d0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState add service
D/LGWifiP2pService(  841): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): start: Starting P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast true
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1876): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453394885168.6172
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1876): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): P2P device discovery stopped successfully
D/LGWifiP2pService(  841): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: RESTARTING
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/io.jxcore.node.ConnectionHelper( 6172): start: OK
I/jxcore-log( 6172): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 6172): 
D/io.jxcore.node.ConnectionHelper( 6172): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 6172): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 6172): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6172): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 6172): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 6172): 
I/io.jxcore.node.ConnectionHelper( 6172): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6172): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6172): onServerStopped
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stop: Stopping peer discovery...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothLeScanner( 6172): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6172): stop: Stopping services
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service
D/LGWifiP2pService(  841): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6172): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6172): setState: NOT_INITIALIZED
,D/LGWifiP2pService(  841): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6172): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6172): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6172): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6172): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6172): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6172): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 83 should be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 84 should not be equal
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # setup
I/jxcore-log( 6172): 
I/jxcore-log( 6172): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): # teardown
I/jxcore-log( 6172): 
,I/jxcore-log( 6172): ok 85 irrelevant messages should be ignored
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 86 relevant messages should not be ignored
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ok 87 messages from this device should be ignored
I/jxcore-log( 6172): 
I/jxcore-log( 6172): Tests Complete
I/jxcore-log( 6172): 
,I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 6172): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 6172): 
,I/chromium( 6172): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 6172): Toggling radios to false
I/jxcore-log( 6172): 
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  841): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1239bcee mBinding = false
I/chromium( 6172): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  841): Message: 2
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothManagerService(  841): Sending off request.
D/LocationManagerService(  841): getAllProviders()=[passive, gps, network]
,D/Ulp_jni (  841): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  841): JNI:system_update. Event-4
D/WifiServiceImplEx(  841): setWifiEnabled: false pid=6172, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  841): setWifiEnabled: false pid=6172, uid=10316
D/BluetoothAdapterService(887547500)( 2080): disable() called...
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothAdapterState( 2080): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2080): Setting state to 13
I/BluetoothAdapterState( 2080): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(887547500)( 2080): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothAdapterProperties( 2080): onBluetoothDisable()
,I/BluetoothAdapterState( 2080): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/BluetoothManagerService(  841): Message: 60
D/BluetoothManagerService(  841): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  841): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/bt-btif ( 2080): HAL bt_hal_cbacks->adapter_properties_cb
,D/LGBluetoothAPIService( 1876): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1370): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
I/BluetoothMapService( 2080): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2080): STATE_TURNING_OFF
,D/LocationManagerService(  841): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  841): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
V/BluetoothMapService( 2080): Handler(): got msg=4
D/BluetoothMapService( 2080): MAP Service closeService in
D/BluetoothMapMasInstance( 2080): MAP Service shutdown
D/Ulp_jni (  841): JNI:system_update. Event-4
,I/jxcore-log( 6172): Radios toggled
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ****TEST TOOK:  ms ****
I/jxcore-log( 6172): 
I/jxcore-log( 6172): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6172): 
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
E/WifiStateMachine(  841): WifiStateMachine: Leaving Connected state
V/BluetoothMapMasInstance( 2080): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2080): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2080): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 2080): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2080): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2080): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2080): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2080): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGBluetoothMapAdapter( 2080): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2080): MAP Service closeService out
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
D/DhcpStateMachine(  841): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  841): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7894 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothAdapterProperties( 2080): Scan Mode:20
D/BluetoothAdapterState( 2080): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2080): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
,E/bt-btif ( 2080): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2080): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2080): BTA_JvDeleteRecord
I/bt-btif ( 2080): BTA_JvRfcommStopServer
W/bt-btif ( 2080): invalid rfc slot id: 2
D/IOP_DB_BT( 2080): db_close: nbr users 0
D/IOP_DB_BT( 2080): db_close: free database
D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2080): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2080): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2080): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2080): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2080): enum_config(L344): out, value:x
D/btif_config_util( 2080): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2080): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2080): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2080): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2080): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2080): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
,D/btif_config_util( 2080): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2080): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2080): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2080): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2080): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2080): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2080): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
,D/btif_config_util( 2080): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:$
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
W/bt-btif ( 2080): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:A5-1
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
,D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
,D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:,
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer,
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:#
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
,D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
,D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks,
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
,D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
,D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
V/NativeCrypto( 1771): Read error: ssl=0xaaee2200: I/O error during system call, Connection timed out
,D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
,D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:XT1072
I/jxcore-log( 6172): Toggling radios to false
I/jxcore-log( 6172): 
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
E/bt-btif ( 2080): btif_hf_upstreams_evt: wrong handle = 24937 
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:a
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2080): enum_config(L302): section ,name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:S5-1
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
V/BluetoothPbapService( 2080): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
W/bt-obex ( 2080): Ignore event 10 in state 1
I/bt-btif ( 2080): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2080): ops_state_cb(L223):  ops_state_cb state:3
W/bt-obex ( 2080): Ignore event 10 in state 1
,D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:	a
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:G4-1
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/OppService( 2080): onOpsStateChange() :3
D/OppService( 2080): Recieved MESSAGE_OPS_DISABLE
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  841): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1239bcee mBinding = false
,D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:a
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/BluetoothManagerService(  841): Message: 2
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/BluetoothManagerService(  841): Sending off request.
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): en,um_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Glob,alTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:A
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:	a
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Note3-1
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:A3-1
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:XT1039
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
V/NativeCrypto( 1771): SSL shutdown failed: ssl=0xaaee2200: I/O error during system call, Broken pipe
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:	a
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
E/bt-btif ( 2080): bta_gattc_deregister Deregister Failedm unknown client cif
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
D/BluetoothAdapterService(887547500)( 2080): disable() called...
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Nexus 5
D/BluetoothAdapterService( 2080): disable() : BT State is not STATE_ON. Can't disable BT
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
E/BluetoothManagerService(  841): IBluetooth.disable() returned false
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:"
D/WifiHS20(  841): hidePasspointNotification off =false
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Note4-1
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
,D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:G3-1
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:	a
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:48:06.548 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:A
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:���
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:#
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:onem9-1
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:H
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:?C
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Tab4
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2080): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2080): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:�h�
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:��h
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:J���J�hrD�hrD�
D/btif_config_util( 2080): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:��P
D/btif_config_util( 2080): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2080): enum_config(L344): out, value:�
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:A3-1
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
,D/btif_config_util( 2080): enum_config(L344): out, value:Z
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:$��
D/btif_config_util( 2080): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:`��
D/btif_config_util( 2080): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:���
D/btif_config_util( 2080): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:�_
D/btif_config_util( 2080): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:4g�
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:��f
D/btif_config_util( 2080): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/btif_config_util( 2080): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 2080): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2080): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 2080): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2080): enum_config(L344): out, value:��\
D/btif_config_util( 2080): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2080): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 2080): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2080): enum_config(L344): out, value:
D/WifiServiceImplEx(  841): setWifiEnabled: false pid=6172, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  841): setWifiEnabled: false pid=6172, uid=10316
I/jxcore-log( 6172): Radios toggled
I/jxcore-log( 6172): 
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  841): hidePasspointNotification off =false
D/ConnectivityService(  841): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10006
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Forcing reevaluation
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:48:06.639 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent(  841): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  841): InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pDisablingState
D/LGWifiP2pService(  841): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): p2p socket connection lost
D/LGWifiP2pService(  841): P2pDisabledState
D/WifiScanningService(  841): SCAN_AVAILABLE : 1
,D/WifiScanningService(  841): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  841): SCAN_AVAILABLE : 1
D/RttService(  841): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServiceExtension( 1876): isInternetCheckAvailable return false
D/WfdsService( 1876): WifiP2pState is changed : false
D/WfdsService( 1876): WfdsEnabledState: Receive the WFDS_DISABLE message
,D/LGWifiP2pService(  841): P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsJNI ( 1876): doCommand: P2P_STOP_FIND
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,D/WfdsService( 1876): Set the WFDS Monitor: false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.p2p.STATE_CHANGED at null
,D/DhcpStateMachine(  841): StoppedState
D/DhcpStateMachine(  841): StoppedState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1876): WFDS Monitor is stopped
D/CtrlSupplicant( 1876): Received on exit socket, terminate
E/CtrlSupplicant( 1876): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1876): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1876): WfdsMonitorThread is received the interrupt - closing
D/WfdsService( 1876): STATE : WfdsDisabledState - enter
D/WfdsService( 1876): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1876): Clear Discovery Method Map: ScanAlwaysMode false
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/ConnectivityService(  841): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  841): disableDataServiceNotify
D/DSQN    (  841): stop dsqn bin
D/WifiHS20(  841): hidePasspointNotification off =false
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:48:06.696 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  841): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:48:06.711 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  841): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/WifiServerServiceExt(  841): WIFI_STATE_CHANGED_ACTION [0]
D/CSLegacyTypeTracker(  841): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  841): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsSession:Controller( 1876): DefaultState - msg [9441355] is not handled
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524292
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.WIFI_STATE_CHANGED at null
V/NetworkPolicy(  841): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1913): |CORE| No family connected
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  841): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  841): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1913): |CORE| No family connected
I/QCNEJ   ( 1913): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
,D/WIFI    (  841): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  841): MasterInitialState.processMessage what=3
D/NetworkManagementService(  841): Removing idletimer
W/Settings(  841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateDISCONNECTED
D/Tethering(  841): MasterInitialState.processMessage what=3
E/ConnectivityService(  841): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1913): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1802): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1802):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 10
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/Netd    (  273): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2682): monitor socket send errors count : 1
I/wpa_supplicant( 2682): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1876-2\x00 that cannot receive messages
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/wpa_supplicant( 2682): USIM:  scard_deinit function
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  841): InitialState.processMessage what=4
,D/Tethering(  841): sendTetherStateChangedBroadcast 0, 0, 0
,W/ResourcesManager( 7894): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7894): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7894): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7894): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7894): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/AndroidRuntime( 7908): 
D/AndroidRuntime( 7908): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7908): CheckJNI is OFF
,D/WifiOffDelayIfNotUsed(  841): stopMonitoring
D/WfdsService( 1876): Supplicant Connection state is changed : false
D/WfdsService( 1876): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1876): Set the WFDS Monitor: false
D/WfdsMonitor( 1876): WFDS Monitor is stopped
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 17:48:07.018 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/WifiServerServiceExt(  841): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  841): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  841): batteryPsActivateMsgHandler : this is not treated
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1771): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/IndexDatabaseHelper( 7894): Using schema version: 115
,I/IndexDatabaseHelper( 7894): Index is fine
,I/ActivityManager(  841): Process com.android.contacts (pid 7522) has died
,I/ActivityManager(  841): Process com.android.gallery3d (pid 7501) has died
,W/ContextImpl( 7894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 2080): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2080): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2080): ***********state = 13
,V/BluetoothPbapReceiver( 2080): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 2080): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2080): state: 13
V/BluetoothPbapService( 2080): Pbap Service closeService in
V/BluetoothPbapService( 2080): successfully stopped pbap service
V/BluetoothPbapService( 2080): Pbap Service closeService out
V/BluetoothPbapService( 2080): Pbap Service onDestroy
V/BluetoothPbapService( 2080): Pbap Service closeService in
V/BluetoothPbapService( 2080): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2080): [BTUI] cleanup
V/WiFiOffLoadBroadcast( 7894): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/AndroidRuntime( 7908): Calling main entry com.android.commands.pm.Pm
D/WiFiOffLoadBroadcast( 7894): MCCMNC not supported: null
D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30cb8425:true
,D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
,D/BluetoothManagerService(  841): Message: 30
,I/ActivityManager(  841): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  841): Killing 6172:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  841): WIN DEATH: Window{38e4ca7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  841): Focus left window: Window{38e4ca7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  841): Window went away: Window{38e4ca7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  841): Skipping PackageSetting{3777ad52 com.example.hello/10317} due to missing metadata
,W/bt_userial( 2080): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2080): hw_epilog_process
W/bt-l2cap( 2080): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2080): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2080): ag scb idx 1 not allocated
E/bt-btif ( 2080): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2080): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2080): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2080): ag scb idx 1 not allocated
E/bt-btif ( 2080): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2080): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2080): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_vendor( 2080): device fd = 70 close
E/bt_vendor( 2080): [BTUI] Proto is enabled. Set Proto disable!!
,I/ActivityManager(  841):   Force finishing activity ActivityRecord{254f9b71 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  841): Display changed displayId=0
,D/DSDPConnection( 1802): Display #0 changed.
W/ActivityManager(  841): Spurious death for ProcessRecord{3d987bc6 6172:com.test.thalitest/u0a316}, curProc for 6172: null
,I/ActivityManager(  841): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  841):   Force finishing activity ActivityRecord{254f9b71 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  841): Duplicate finish request for ActivityRecord{254f9b71 u0 com.test.thalitest/.MainActivity t222 f}
I/GKI_LINUX( 2080): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 2080): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2080): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 2080): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2080): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2080): Unable to read settings
D/BtSettings.ProfileConfig( 2080): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2080): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2080): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2080): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2080): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2080): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2080): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2080): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2080): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2080): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2080): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1771): Ignoring removeGeofence because network location is disabled.
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/HeadsetService( 2080): Received stop request...Stopping profile...
I/[LGHome]EVENT( 1950): [Launcher.java:5203:onStart()]onStart
W/System.err( 3252): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3252): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3252): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3252): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
,W/System.err( 3252): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3252): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3252): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3252): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3252): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/QCNEJ   ( 1913): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2080): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/LGBluetoothHfpAdapter( 2080): [BTUI] LGBluetoothHfpAdapter cleanup
,D/HeadsetStateMachine( 2080): Exit Disconnected: -1
W/LGBluetoothHeadsetServiceJni( 2080): Cleaning up Bluetooth Handsfree callback object
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
W/BluetoothAdapterService( 2080): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2080): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2080): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2080): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 2080): Stopping profile services that were post enabled
D/A2dpService( 2080): Received stop request...Stopping profile...
D/A2dpStateMachine( 2080): Exit Disconnected: -1
D/BluetoothManagerService(  841): Message: 30
,D/LocalBluetoothProfileManager( 7894): Adding local MAP profile
D/BluetoothMap( 7894): Create BluetoothMap proxy object
D/BluetoothManagerService(  841): Message: 30
D/LGBluetoothA2dpAdapter( 2080): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 2080): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2080): [BTUI] terminate
,D/BluetoothManagerService(  841): Message: 31
I/[LGHome]EVENT( 1950): [Launcher.java:776:onResume()]onResume
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/BluetoothHeadset( 1802): Proxy object disconnected
D/HidService( 2080): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/HealthService( 2080): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/PanService( 2080): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/BluetoothManagerService(  841): Message: 30
D/BluetoothHeadset( 1802): Proxy object disconnected
D/BtGatt.DebugUtils( 2080): handleDebugAction() action=null
D/BtGatt.GattService( 2080): Received stop request...Stopping profile...
D/BtGatt.GattService( 2080): stop()
I/[LGHome]EVENT( 1950): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/BtGatt.AdvertiseManager( 2080): advertise clients cleared
I/art     ( 2028): Explicit concurrent mark sweep GC freed 10047(668KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 1.631ms total 151.202ms
D/BluetoothHeadset( 1802): Proxy object disconnected
D/LGBluetoothGattAdapter( 2080): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/BluetoothMapService( 2080): Received stop request...Stopping profile...
D/BluetoothMapService( 2080): stop()
D/LocalBluetoothProfileManager( 7894): LocalBluetoothProfileManager construction complete
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/BluetoothMapEmailAppObserver( 2080): deinitObservers()
D/BluetoothMapEmailAppObserver( 2080): removeReceiver()
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,D/SapService( 2080): Received stop request...Stopping profile...
D/SapService( 2080): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2080): [BTUI] LGBluetoothSapAdapter cleanup
I/[LGHome]LGActivityUtil( 1950): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LGBluetoothSapManager( 2080): [BTUI] terminateSapManager
I/[LGHome]EVENT( 1950): [Launcher.java:929:onResume()]onResume end
D/LGBluetoothFeatureConfig( 7894):  get() - isFeatureLoaded : false
,I/Activity( 1950): Activity.onPostResume() called 
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/HeadsetStateMachine( 2080): Unbinding service...
D/HeadsetPhoneState( 2080): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2080): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2080): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2080): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 2080): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2080): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2080): [BTUI] LGBluetoothHfpAdapter cleanup
D/LgeBluetoothSimManager( 1802): [BTUI] SAP_DISABLE_EVT
D/**BluetoothFTPService( 2080): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2080): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2080): closeFtpServerNative
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/**OppService( 2080): Received stop request...Stopping profile...
D/OppService( 2080): Stopping Bluetooth OppService
D/OppService( 2080): cleanup OPP Service
W/BluetoothOPPServiceJni( 2080): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2080): Cleaning up Bluetooth OPP callback object
,D/OppService( 2080): remove callbacks and handler
D/LGBluetoothOppAdapter( 2080): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2080): cleanup done
D/BluetoothAdapterService( 2080): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e6e66c
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 2080): cleanupNative
I/GKI_LINUX( 2080): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2080): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2080): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1950): [Launcher.java:986:onPause()]onPause
W/BluetoothHidServiceJni( 2080): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 2080): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2080): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2080): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2080): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2080): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2080): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2080): Handler(): got msg=4
D/BluetoothMapService( 2080): MAP Service closeService in
D/LGBluetoothMapAdapter( 2080): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2080): MAP Service closeService out
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
,D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2080): cleanup()
D/BluetoothMapService( 2080): MAP Service closeService in
D/LGBluetoothMapAdapter( 2080): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2080): MAP Service closeService out
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2080): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2080): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2080): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2080): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 2080): cleanup FTP Service
V/BluetoothFTPServiceJni( 2080): closeFtpServerNative
,V/BluetoothFTPServiceJni( 2080): cleanupNative
W/BluetoothFTPServiceJni( 2080): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2080): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2080): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2080): cleanup done
D/BluetoothAdapterService(887547500)( 2080): handleMessage() - Message: 1
,D/BluetoothAdapterService(887547500)( 2080): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2080): isTurningOnRadio()=false
D/BluetoothAdapterState( 2080): isTurningOffRadio()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2080): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2080): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(887547500)( 2080): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 2080): cleanup OPP Service
D/OppService( 2080): remove callbacks and handler
D/LGBluetoothOppAdapter( 2080): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2080): cleanup done
D/BluetoothAdapterState( 2080): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2080): Setting state to 10
I/BluetoothAdapterState( 2080): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(887547500)( 2080): updateAdapterState() - Broadcasting state to 1 receivers.
I/BluetoothAdapterState( 2080): Entering OffState
D/BluetoothManagerService(  841): Message: 60
D/BluetoothManagerService(  841): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  841): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothMap( 7894): onBluetoothStateChange: up=false
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/BluetoothInputDevice( 7894): onBluetoothStateChange: up=false
D/BluetoothA2dp(  841): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1802): onBluetoothStateChange: up=false
W/[LGHome]LGWallpaperInfo( 1950): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1950): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/BluetoothHeadset( 1802): onBluetoothStateChange: up=false
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
D/BluetoothHeadset( 1802): onBluetoothStateChange: up=false
D/BluetoothPan( 7894): onBluetoothStateChange on: false
D/BluetoothHeadset(  841): onBluetoothStateChange: up=false
D/BluetoothPbap( 7894): onBluetoothStateChange: up=false
D/BluetoothAdapterService(887547500)( 2080): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@d76f22
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothManagerService(  841): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  841): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothManagerService(  841): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  841): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  841): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1239bcee mBinding = false
D/BluetoothManagerService(  841): Sending unbind request.
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
D/BluetoothAdapterService(887547500)( 2080): onUnbind() - calling cleanup
D/InputDispatcher(  841): Focus entered window: Window{3d59e64a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/BluetoothAdapterService(887547500)( 2080): cleanup()
D/BluetoothManagerService(  841): Bluetooth State Change Intent: 13 -> 10
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/LGBluetoothAPIService( 1876): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1370): 527890336: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1370): 527890336: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1876): Message: 2
D/LGBluetoothAPIService( 1876): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3353400b mBinding = false
D/LGBluetoothAPIService( 1876): Sending unbind request.
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1370): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
I/[LGHome]EVENT( 1950): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/LGBluetoothUserBindClient( 7894): [BTUI] initUserBindClient
I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1950): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1a4e5123,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1a4e5123,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BluetoothAdapterService(887547500)( 2080): cleanup() - Cleaning up adapter native
I/bt-btif ( 2080): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2080): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2080): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2080): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2080): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2080): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2080): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2080): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2080): GKI_exit_task 2 done
I/GKI_LINUX( 2080): GKI_exit_task 1 done
I/GKI_LINUX( 2080): GKI_exit_task 0 done
I/BluetoothServiceJni( 2080): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2080): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 2080): [BTUI] unregister observer for LG device name DB
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/BluetoothAdapterService(887547500)( 2080): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(887547500)( 2080): cleanup() done
I/[LGHome]EVENT( 1950): [Launcher.java:5214:onStop()]onStop
W/ContextImpl( 7894): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/art     ( 2080): System.exit called, status: 0
I/AndroidRuntime( 2080): VM exiting with result code 0, cleanup skipped.
,I/art     (  841): Explicit concurrent mark sweep GC freed 40882(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 9.987ms total 278.336ms
I/art     (  841): WaitForGcToComplete blocked for 139.593ms for cause Explicit
D/KeyguardModel( 1370): handleShortcutListChanged...
I/[LGHome]EVENT( 1950): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,V/AudioFlinger(  278): 2080 died, releasing its sessions
V/AudioFlinger(  278):  pid 1802 @ 0
V/AudioFlinger(  278):  pid 3477 @ 1
V/AudioFlinger(  278):  pid 3477 @ 2
D/FMFRW_FmProxy( 1876): Fm Proxy object disconnected
I/PhoneWindow( 1950): [setNavigationBarColor] color=0x 0
D/DockEventReceiver( 7894): finishStartingService: stopping service
D/BluetoothAdapter( 1771): 719761323: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1771): 719761323: getState() :  mService = null. Returning STATE_OFF
,D/LGBluetoothFeatureConfig( 7894): isPrivacyLogsEnabled : true
,E/LGBluetoothEventManager( 7894): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7894): [BTUI] clear device connection state
I/ActivityManager(  841): Process com.android.bluetooth (pid 2080) has died
,W/ActivityManager(  841): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
W/ActivityManager(  841): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1370): createShortcutInfo...
D/LGBluetoothAuthorization( 7894): [BTUI] cancel All Notification
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
I/NotificationManager( 7894): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000001) by com.android.settings
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
I/NotificationManager( 7894): com.android.settings: cancel(-1000011) by com.android.settings
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/NotificationManager( 7894): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000041) by com.android.settings
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/administrator(  841): Handling package changes for user 0
,I/ActivityManager(  841): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7958 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 7894): onReceive
D/KeyguardModel( 1370): handleShortcutListChanged...
,D/LGBluetoothAuthorization( 7894): [BTUI] cancel All Notification
I/NotificationManager( 7894): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7894): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  841): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7976 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,W/InputMethodManagerService(  841): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 24.061ms
I/art     (  841): Explicit concurrent mark sweep GC freed 6356(355KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.878ms total 257.891ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.655ms
,W/InputMethodManagerService(  841): Got RemoteException sending setActive(false) notification to pid 6172 uid 10316
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 23.652ms
,I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7976): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7976): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7976): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7976): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,I/Timeline(  841): Timeline: Activity_windows_visible id: ActivityRecord{121ff733 u0 com.lge.launcher2/.Launcher t221} time:338533
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,D/BluetoothAdapterApp( 7976): Loading JNI Library
W/IInputConnectionWrapper( 1950): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1622): Unable to connect to the editor to retrieve text... will retry later
E/BluetoothServiceJni( 7976): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1950): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1950): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/BluetoothAdapterApp( 7976): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@b182627 Instance Count = 1
D/AndroidRuntime( 7908): Shutting down VM
D/BluetoothAdapterApp( 7976): onCreate
,I/PCSuite ( 7958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7958): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1950): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
,I/LGBluetoothServiceJni( 7976): classInitNative: succeeds
D/BtSettings.ProfileConfig( 7976): [BTUI] HeadsetServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding HeadsetService
D/BtSettings.ProfileConfig( 7976): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding A2dpService
D/BtSettings.ProfileConfig( 7976): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding HidService
,D/BtSettings.ProfileConfig( 7976): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding HealthService
D/LGBluetoothFeatureConfig( 7976): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 7976): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 7976): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding PanService
D/BtSettings.ProfileConfig( 7976): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding GattService
D/BtSettings.ProfileConfig( 7976): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 7976): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 7976): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding SapService
D/BtSettings.ProfileConfig( 7976): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding FTPService
E/BtSettings.ProfileConfig( 7976): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 7976): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 7976): Adding OppService
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
D/BtSettings.ProfileConfig( 7976): deviceMode from shared preference   -1
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
D/BtSettings.ProfileConfig( 7976): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/BtSettings.ProfileConfig( 7976): Unable to read settings
D/BtSettings.ProfileConfig( 7976): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7976): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 7976): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 7976): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 7976): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 7976): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 7976): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 7976): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 7976): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 7976): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 7976): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 7976): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 7976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 7976): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 7976): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 7976): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 7976): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 7976): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 7976): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.andro,id.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/BtSettings.ProfileConfig( 7976): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
V/WiFiOffLoadBroadcast( 7894): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGBluetoothOppAdapter( 7976): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppReceiver( 7976): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 7976): [BTUI] cancel opp incoming file confirm notification
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/NotificationManager( 7976): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 7976): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 7976): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
D/WiFiOffLoadBroadcast( 7894): MCCMNC not supported: null
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
I/PCSuite ( 7958): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7958): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7958): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/NotificationService(  841): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  841): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1950): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/FmServiceJni( 7976): classInitNative: succeeds
D/FmService( 7976): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@1c26c572servicecom.broadcom.fm.fmreceiver.FmService@34d6fdc3
D/FmNativehandler( 7976): start
D/BluetoothRadioManager( 7976): [BTUI] getRadioManager()
D/BluetoothRadioManager( 7976): [BTUI] BluetoothRadioManager()
I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8003 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/TaskPersister(  841): removeObsoleteFile: deleting file=222_task.xml
D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cfd8c37:true
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
,I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BluetoothRadioManager( 7976): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
V/FmService( 7976): FM Service  onCreate
D/FmService( 7976): Binding service...
D/FMFRW_FmProxy( 1876): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@b77cee8
D/LGBluetoothUserBindClient( 7894): [BTUI] onServiceConnected
,W/ResourcesManager( 8003): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 7976): Set JNI Library before classInit
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/BluetoothAdapterService(67974197)( 7976): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(67974197)( 7976): onCreate()
D/BluetoothAdapterState( 7976): make
I/bluedroid( 7976): init
,I/BluetoothAdapterState( 7976): Entering OffState
I/bte_conf( 7976): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 7976): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 7976): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 7976): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 7976): [BTUI] lge_load_bluetooth_address
E/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1950): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/Babel_SMS( 8003): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8003): MmsConfig.loadMmsSettings
E/[LgeWidgetLib]LgeAppWidgetHostView( 1950): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/Babel_SMS( 8003): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[LGHome]EVENT( 1950): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/Babel_SMS( 8003): MmsConfig.loadFromDatabase
I/[LGHome]Launcher( 1950): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/SQLiteDatabase( 8003): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 8003): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8003): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8003): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8003): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8003): 	at alg.<init>(SourceFile:161)
E/SQLiteDatabase( 8003): 	at alj.a(SourceFile:1015)
E/SQLiteDatabase( 8003): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/SQLiteDatabase( 8003): 	at gvf.d(SourceFile:408)
E/SQLiteDatabase( 8003): 	at gvf.b(SourceFile:238)
E/SQLiteDatabase( 8003): 	at gvf.a(SourceFile:204)
E/SQLiteDatabase( 8003): 	at gvf.a(SourceFile:485)
E/SQLiteDatabase( 8003): 	at alg.a(SourceFile:167)
E/SQLiteDatabase( 8003): 	at dnm.c(SourceFile:606)
E/SQLiteDatabase( 8003): 	at dnm.b(SourceFile:570)
E/SQLiteDatabase( 8003): 	at dnn.run(SourceFile:221)

```
