#### Test 549702618c0ebdb_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:42.67 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AndroidRuntime( 6010): 
D/AndroidRuntime( 6010): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6010): CheckJNI is OFF
I/GAV2    ( 5813): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 6010): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  854): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  854): setTaskToReturnTo : TaskRecord{f8ca33e #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  854): setTaskToReturnTo : TaskRecord{f8ca33e #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  854): AppWindowTokenEx init.. 
D/ContextHelper(  854): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  854): Focus left window: Window{6d6dd4a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6010): Shutting down VM
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  854): check instance of lgWin Window{10abf5d8 u0 Starting com.test.thalitest}
I/ActivityManager(  854): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6027 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1941): Closing mic
I/WindowStateAnimator(  854): Starting window displayed
I/SystemUI[Framework](  854): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  854): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  854): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  854): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f3a9e87,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@22ddb0cf
D/BarTransitions( 1369): draw background and invalidate : color = 11000000
D/BarTransitions( 1369): draw background and invalidate : color = e0d0d0d
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioFlinger(  284): Record stopped OK
V/AudioPolicyManager(  284): stopInput() input 17
V/AudioPolicyService(  284): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  284): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  284): ThreadBase::setParameters() routing=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb3847000
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  284): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  284): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  284): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  284): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  284): disable_audio_route: exit
E/audio_hw_primary(  284): disable_snd_device: enter 144
D/hardware_info(  284): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  284): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  284): stop_input_stream: exit: status(0)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  284): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  284): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  284): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyService(  284): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  284): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  284): setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
V/AudioFlinger(  284): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  284): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  284): in_set_parameters: exit: status(0)
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb3847000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread 0xb3847000 exiting
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  284): releaseInput() exit
V/AudioFlinger(  284): releasing 16 from 1941 for -1
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): removeClient_l() pid 1941, calling pid 284
V/AudioFlinger(  284): purging stale effects
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioSystem(  854): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3198): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2023): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2830): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
I/HotwordRecognitionRnr( 1941): Hotword detection finished
D/ContextHelper( 6027): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6027): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/AlertService( 5863): Beginning updateAlertNotification
D/AlertService( 5863): No fired or scheduled alerts
I/NotificationManager( 5863): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5863): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5863): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5863): No events found starting within 1 week.
I/ActivityManager(  854): Killing 5863:com.android.calendar/u0a13 (adj 15): empty #11
I/LibraryLoader( 6027): Time to load native libraries: 3 ms (timestamps 2810-2813)
I/LibraryLoader( 6027): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6027): Binding Chromium to main looper Looper (main, tid 1) {23e2e3d6}
I/LibraryLoader( 6027): Expected native library version number "",actual native library version number ""
I/chromium( 6027): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/libprocessgroup(  854): failed to open /acct/uid_10013/pid_5863/cgroup.procs: No such file or directory
I/BrowserStartupController( 6027): Initializing chromium process, singleProcess=true
W/art     ( 6027): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6027): ApplicationContext is null in ApplicationStatus
W/chromium( 6027): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/ActivityManager(  854): Killing 5598:com.google.android.talk/u0a61 (adj 15): empty #11
E/libEGL  ( 6027): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6027): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6027): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6027): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6027): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6027): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6027): Remote Branch: 
I/Adreno-EGL( 6027): Local Patches: 
I/Adreno-EGL( 6027): Reconstruct Branch: 
W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_5598/cgroup.procs: No such file or directory
V/AudioPolicyService(  284): registerClient() client 0xb57ebde0, uid 10316
D/BluetoothManagerService(  854): Message: 20
D/BluetoothManagerService(  854): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18c404fa:true
,D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/art     ( 6027): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6027): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6027): CordovaWebView is running on device made by: LGE
,W/art     ( 6027): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6027): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6027): Activity.onPostResume() called 
,D/OpenGLRenderer( 6027): Render dirty regions requested: true
I/OpenGLRenderer( 6027): Initialized EGL, version 1.4
D/OpenGLRenderer( 6027): Enabling debug mode 0
,D/Atlas   ( 6027): Validating map...
,D/SplitWindow(  854): check instance of lgWin Window{a7a0aa u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6027): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  854): Focus entered window: Window{a7a0aa u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  854): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  854): Displayed com.test.thalitest/.MainActivity: +1s222ms
I/Timeline(  854): Timeline: Activity_windows_visible id: ActivityRecord{3892959f u0 com.test.thalitest/.MainActivity t220} time:93492
I/Timeline( 6027): Timeline: Activity_idle id: android.os.BinderProxy@932349d time:93495
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
W/BindingManager( 6027): Cannot call determinedVisibility() - never saw a connection for the pid: 6027
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{cdc27e4 type 0 when 1452267105201 com.android.vending} when 1452267105201
D/Finsky  ( 5536): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  854): android: cancelAsUser(2) by android
D/JsMessageQueue( 6027): Set native->JS mode to OnlineEventsBridgeMode
,D/libc-netbsd( 5536): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5536): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5536): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5536): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5536): propertyValue:false
D/libc-netbsd( 5536): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5536): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5536): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5536): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  854): tsOffsetIs: Apps: 94081166116; DSPS: 3174101; Offset : -2786451184
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,D/jxcore_app_log( 6027): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622762496
,D/JX-Cordova( 6027): jxcore cordova android initializing
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/qtaguid ( 5536): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5536): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5536): untagSocket(41) failed with errno -22
D/Finsky  ( 5536): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/art     ( 6027): CheckpointMarkThreadRoots callback created = 0xb078e200
,I/art     ( 6027): CheckpointMarkThreadRoots callback created = 0xb078e1d0
,I/ActivityManager(  854): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6115 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,W/ResourcesManager( 6115): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6115): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6115): VM with version 2.1.0 has multidex support
I/MultiDex( 6115): install
I/MultiDex( 6115): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 5536): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5536): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5536): untagSocket(41) failed with errno -22
V/JNIHelp ( 6115): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6115): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6115): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20cf4928: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6115): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6115): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6115): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4189): Restart initialization of location
,D/ChimeraCfgMgr( 6115): Reading stored module config
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6115): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
,I/art     ( 5497): Explicit concurrent mark sweep GC freed 8057(405KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 423us total 76.365ms
,I/art     (  854): Explicit concurrent mark sweep GC freed 30441(1527KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.338ms total 256.832ms
,D/NativeLibraryUtils( 6115): Install completed successfully. count=14 extracted=0
,I/art     ( 5536): CheckpointMarkThreadRoots callback created = 0xaaefb1d0
,D/CAR.SERVICE( 6115): Connecting to CarCallService...
,I/art     ( 5536): CheckpointMarkThreadRoots callback created = 0xaaefb1a0
I/art     ( 6115): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6115): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6115): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6115): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6115): Creating a new PhoneAdapter instance
W/ActivityManager(  854): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6115): setListener: com.google.android.gms.car.dn@2db9c217
W/ActivityManager(  854): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6115): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 6115): Starting CarCallService with initial phone null
I/NotificationManager( 6115): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6115): Package validated; name: com.android.vending
,D/UEI.SmartControl( 5942): Internal timer expired: 1
I/NotificationManager( 5536): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5536): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/qtaguid ( 5536): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5536): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5536): untagSocket(41) failed with errno -22
,I/ActivityManager(  854): Process com.android.contacts (pid 5733) has died
,W/jxcore-log( 6027): Initializing JXcore engine
W/jxcore-log( 6027): JXcore engine is ready
W/jxcore-log( 6027): Starting JXcore engine
,W/.test.thalitest( 6027): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5562]" dev="sockfs" ino=5562 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6027): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6027): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8416]" dev="sockfs" ino=8416 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6027): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6027): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6027): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28706]" dev="sockfs" ino=28706 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/ResourcesManager( 5536): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5536): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5536): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{1c3919c2 type 0 when 1452267108235 com.android.vending} when 1452267108235
,D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/Finsky  ( 5536): [685] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  854): android: cancelAsUser(2) by android
,D/Finsky  ( 5536): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5536): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
W/jxcore-log( 6027): Platform android
W/jxcore-log( 6027): 
W/jxcore-log( 6027): Process ARCH arm
W/jxcore-log( 6027): 
D/libc-netbsd( 5536): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5536): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5536): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5536): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 5536): propertyValue:false
I/ActivityManager(  854): Process com.google.android.apps.plus (pid 5464) has died
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{22167c28 type 0 when 1452267108940 com.google.android.googlequicksearchbox} when 1452267108940
,I/jxcore-log( 6027): JXcore Cordova bridge is ready!
I/jxcore-log( 6027): 
,W/jxcore-log( 6027): JXcore engine is started
I/chromium( 6027): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6027): Skipped 211 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6027): Toggling radios to true
I/jxcore-log( 6027): 
,D/BluetoothAdapter( 6027): enable(): BT is already enabled..!
D/WifiServiceImplEx(  854): setWifiEnabled: true pid=6027, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  854): setWifiEnabled: true pid=6027, uid=10316
D/WifiServiceImplEx(  854): disconnect pid=6027, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  854): reconnect pid=6027, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6027): Radios toggled
I/jxcore-log( 6027): 
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2679): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2679): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  854): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1800): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  854): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  854): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Clearing all IP addresses on wlan0
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): Read error: ssl=0xaaee2000: I/O error during system call, Connection timed out
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xaaee2000: I/O error during system call, Broken pipe
D/WifiHS20(  854): hidePasspointNotification off =false
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:49.666 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  854): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): ValidatedState{ when=-2ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Forcing reevaluation
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
,I/ActivityManager(  854): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6198 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  854): Start Disconnecting Watchdog 1
D/WifiHS20(  854): hidePasspointNotification off =false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2679): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/LGWifiP2pService(  854): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:49.773 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/CommandListener(  280): Clearing all IP addresses on wlan0
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:49.788 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiHS20(  854): hidePasspointNotification off =false
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  854): Default network via Wi-Fi disconnect. stop DSQN
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/DhcpStateMachine(  854): StoppedState
D/DhcpStateMachine(  854): StoppedState{ when=-45ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,D/WifiNetworkAgent(  854): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/DSQN    (  854): disableDataServiceNotify
D/DSQN    (  854): stop dsqn bin
D/WifiHS20(  854): hidePasspointNotification off =false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:49.806 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:49.811 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  854): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/ConnectivityService(  854): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  854): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  854): setSupplicantStateSCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  854): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  854): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  854): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  854): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  854): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1836): |CORE| No family connected
D/WIFI    (  854): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  854): MasterInitialState.processMessage what=3
V/NetworkPolicy(  854): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  854): Removing idletimer
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  854): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6198): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6198): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6198): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6198): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6198): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/IndexDatabaseHelper( 6198): Using schema version: 115
,I/IndexDatabaseHelper( 6198): Index is fine
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
,I/ActivityManager(  854): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
I/PCSuite ( 6227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6249 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6249): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2679): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Babel_SMS( 6249): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6249): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6249): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6249): MmsConfig.loadFromDatabase
D/LocSvc_java(  854): onReceive
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:50.921 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/wpa_supplicant( 2679): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:50.943 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:50.965 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:50.971 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/wpa_supplicant( 2679): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2679): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/WifiServiceExtension(  854): setVHTCapabilityType  : false
E/Babel_SMS( 6249): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6249): MmsConfig.loadFromResources
E/Babel_SMS( 6249): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6249): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6249): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6249): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6249): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6249): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6249): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6249): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6249): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6249): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6249): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6249): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6249): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6249): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6249): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6249): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6249): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6249): found sensor: Motion Accel, handle=46
I/art     ( 6249): CheckpointMarkThreadRoots callback created = 0xb042d800
,I/ActivityManager(  854): Process com.google.android.gm (pid 5813) has died
,I/WifiServerServiceExt(  854): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  854): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  854): setSecurityType  : 2
I/art     ( 6249): CheckpointMarkThreadRoots callback created = 0xb042d7d0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService(  854): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  854): Got NetworkAgent Messenger
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  854): NetworkAgent connected
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:51.163 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:51.165 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
W/art     ( 6249): Suspending all threads took: 37.438ms
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
E/WifiStateMachine(  854): Start Dhcp Watchdog 2
D/DhcpStateMachine(  854): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  854): WaitBeforeStartState
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,W/Settings( 6249): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6249): startup - clean
,I/Babel   ( 6249): deleted: false for 0
,E/WifiStateMachine(  854): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  854): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  854): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a449b57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a449b57 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  854): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Setting iface cfg
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/DhcpStateMachine(  854): DHCP Start wake lock is acquired.
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  854): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateCOMPLETED
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  854): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  854): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  854): Adding iface wlan0 to network 101
E/WifiStateMachine(  854): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:51.323 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:51.325 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/WifiHS20(  854): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService(  854): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  854): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  854): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  280): netlink response contains error (File exists)
D/ConnectivityService(  854): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:51.345 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  854): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  854): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  854): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,D/WifiHS20(  854): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:51.362 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat(  854): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Connected
D/ConnectivityService(  854):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  854): currentScore = 0, newScore = 20
D/ConnectivityService(  854):    accepting network in place of null
D/ConnectivityService(  854): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  854): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  854): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  854): [e] list.add(nai) empty : false size: 1
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  854): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  854): MasterInitialState.processMessage what=3
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  854): validation of new default Network = false
D/ConnectivityService(  854): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  854): enableDataServiceNotify 
D/DSQN    (  854): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/ConnectivityService(  854): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
I/DSQN    ( 6285): DSQN samuel.seo ver 141203
E/DSQN    ( 6285): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6285): created command queue thread
I/DSQN    ( 6285): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6285): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/NetworkPolicy(  854): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
I/PCSuite ( 6227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6249): Unsupported mime audio/x-lg-flac
,V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6249): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6249): Unsupported mime audio/g726
W/AudioCapabilities( 6249): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6249): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
W/VideoCapabilities( 6249): Unsupported mime video/mjpg
,I/PCSuite ( 6227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6227): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6249): Unsupported mime video/theora
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
D/DhcpStateMachine(  854): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  854): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  854): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6289): version 5.5.6 starting
E/dhcpcd  ( 6289): get_duid: Read-only file system
,V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6198): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6249): Unsupported mime audio/evrc
,I/dhcpcd  ( 6289): wlan0: rebinding lease of 192.168.1.134
W/AudioCapabilities( 6249): Unsupported mime audio/qcelp
W/VideoCapabilities( 6249): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
W/AudioCapabilities( 6249): Unsupported mime audio/amr-wb-plus
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6249): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6249): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
,W/VideoCapabilities( 6249): Unsupported mime video/mp4v-esdp
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
I/VideoCapabilities( 6249): Unsupported profile 4 for video/mp4v-es
I/PCSuite ( 6227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,W/VideoCapabilities( 6249): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6249): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6198): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6249): Unrecognized profile 2130706433 for video/avc
,D/WiFiOffLoadBroadcast( 6198): MCCMNC not supported: null
W/VideoCapabilities( 6249): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 6227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/vclib   ( 6249): onServiceConnected
W/Babel   ( 6249): Attempted to change video mute state without an active call.
I/ActivityManager(  854): Killing 5756:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/NotificationManager( 6249): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] DNSResolver start dns
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
,D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  854): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Checking http://clients3.google.com/generate_204 on "NG700"
I/dhcpcd  ( 6289): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  854): failed to open /acct/uid_10069/pid_5756/cgroup.procs: No such file or directory
V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{197da2b type 2 when 100385 com.google.android.gms} when 100385
I/DSQN    ( 6285): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6285): restart monitoring
,D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6285): dsqn report finish
D/DSQN    (  854): DSQM DsqnNotification wlan0  1
D/DSQN    (  854): start to monitor internet connection
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/dhcpcd  ( 6289): wlan0: leased 192.168.1.134 for 86400 seconds
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 15:31:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452267111988], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452267111964]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Validated
D/ConnectivityService(  854): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  854): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  854): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  854): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  854): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  854): set CMD_CAPTIVE_CHECK_COMPLETED
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CAR.SERVICE( 6115): mConnectedToCar = false, abort
,E/ActivityThread( 6115): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3fe62e1f that was originally bound here
E/ActivityThread( 6115): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3fe62e1f that was originally bound here
E/ActivityThread( 6115): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6115): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6115): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6115): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6115): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6115): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6115): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6115): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6115): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6115): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6115): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6115): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6115): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6115): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6115): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6115): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6115): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6115): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6115): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6115): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6115): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@308b5696 that was originally bound here
E/ActivityThread( 6115): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@308b5696 that was originally bound here
E/ActivityThread( 6115): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6115): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6115): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6115): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6115): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6115): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6115): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6115): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6115): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6115): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6115): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6115): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6115): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6115): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6115): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6115): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6115): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6115): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6115): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  854): Unbind failed: could not find connection for android.os.BinderProxy@1a632e88
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  854): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  854): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  854): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  854): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  854): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  854): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  854): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  854): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  854): RunningState
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:52.407 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  854): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  854): identical MTU - not setting
D/Nat464Xlat(  854): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  854): enableDataServiceNotify 
D/DSQN    (  854): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524295
D/DSQN    (  854): dsqn is running restart
,I/DSQN    ( 6327): DSQN samuel.seo ver 141203
,E/DSQN    ( 6327): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6327): created command queue thread
I/DSQN    ( 6327): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6327): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  854): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  854): onReceive
D/LocSvc_java(  854): got connectivity action
D/LocSvc_java(  854): broadcast - no network connections
D/LocSvc_java(  854): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  854): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  854): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  854): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  854): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  854): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  854): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6333 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  854): onReceive
D/LocSvc_java(  854): got connectivity action
D/LocSvc_java(  854): broadcast - no network connections
D/LocSvc_java(  854): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  854): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  854): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  854): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  854): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  854): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  854): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/MusicStore( 6333): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6333): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6333): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6333): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6333): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6333): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6333): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6333): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6333): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d82e4a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6333): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6333): GMSCore installation verified
,I/ConfigStore( 6333): Config Database version: 1
,I/MediaRouter( 6333): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6333): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6333): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6333): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6382 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6333): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6333): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  854): Killing 5964:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/ResourcesManager( 6382): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6382): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6382): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  854): failed to open /acct/uid_10014/pid_5964/cgroup.procs: No such file or directory
,I/NotificationManager( 6333): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6382): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6382): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/NotificationManager( 1941): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:31:54.222 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WifiInternetCheck(  854): Single check msg out of sync, ignoring.
,I/ActivityManager(  854): Process com.android.vending (pid 5536) has died
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  854): onReceive
D/LocSvc_java(  854): got connectivity action
D/LocSvc_java(  854): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  854): Sending msg: 4 arg1:1 arg2:1
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  854): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  854): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  854): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  854): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 6333): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  854): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/eas_req ( 6382): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ActivityManager(  854): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6415 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/HubEmail( 6382): JNI_OnLoad()
I/HubEmail( 6382): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6382): registerNatives()
I/HubEmail( 6382): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6382): registerNativeMethods()
I/HubEmail( 6382): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6382): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6382): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6415): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6415): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6415): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6415): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6415): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6415): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6415): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6415): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6440 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6415): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6415): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6415): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6415): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6415): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6415): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  854): Killing 6115:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,W/libprocessgroup(  854): failed to open /acct/uid_10006/pid_6115/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6440): onCreate
,W/AppUp4:DB( 6440):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6440):  setFingerPrint start
,I/AppUp4:DB( 6440):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6440):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6440):  SDK version = 0
I/AppUp4:DB( 6440):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6440): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6440): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6440): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6440): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6440): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6440): onReceive
I/AppUp4:CustModeStarterReceiver( 6440): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6440): Context : android.app.ReceiverRestrictedContext@368a6657
D/AppUp4:CustFacade( 6440): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6440): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6440): begin check event
I/AppUp4:CustModeStarterReceiver( 6440): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6440): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6440): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6440): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6440): handleAsyncCustNotification do not startCustService
I/ActivityManager(  854): Killing 6198:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6198/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3198): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3198): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3198): networkInfo.isConnected() = false
,I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6465 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6465): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6465): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6465): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  854): Killing 5942:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/System.err( 4998): android.os.DeadObjectException
W/System.err( 4998): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4998): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4998): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4998): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4998): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4998): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4998): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4998): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4998): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4998): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4998): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4998): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4998): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4998): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4998): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4998): android.os.DeadObjectException
W/System.err( 4998): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4998): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4998): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4998): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4998): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4998): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4998): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4998): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4998): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4998): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4998): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4998): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4998): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4998): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4998): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  854): propertyValue:false
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  854): propertyValue:false
I/DSQN    ( 6327): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6327): restart monitoring
,I/DSQN    ( 6327): dsqn report finish
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  854): DSQM DsqnNotification wlan0  1
D/DSQN    (  854): start to monitor internet connection
V/WifiInternetCheck(  854): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  854): failed to open /acct/uid_10089/pid_5942/cgroup.procs: No such file or directory
W/ActivityManager(  854): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/PhoneMonitor( 6465): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6465): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  854): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6490 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TelephonyAutoProfiling( 6465): [parse] Load xml
I/art     (  307): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 25.374ms
,V/TelephonyAutoProfiling( 6465): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6465): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3220): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  307): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 27.211ms
,I/CheckinService( 4189): Checkin interval check for package: unspecified last checkin: 1452267088978 min interval config: 0 actual interval: 26950
V/DownloadManager( 3220): DownloadService onCreate
D/PhoneMonitor( 6465): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 26.162ms
I/DownloadManager( 3220): in removeSpuriousFiles
I/NotificationManager( 3220): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3220): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@3e5ae41a on behalf of 3220
I/DownloadManager( 3220): in trimDatabase
V/DownloadManager( 3220): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@20cf4928 on behalf of 3220
,I/ActivityManager(  854): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6521 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3220): DownloadService onStartCommand
V/DownloadManager( 3220): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4189): Checking schedule, now: 1452267116045 next: 1452267118919
I/CheckinService( 4189): active receiver: disabled
,I/art     (  854): Explicit concurrent mark sweep GC freed 83453(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.687ms total 233.018ms
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@163327e6 on behalf of 3220
,I/ActivityManager(  854): Killing 6227:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6490): Quickset Services start...
I/UEI.SmartControl( 6490): Manufacture = LGE
D/UEI.SmartControl( 6490): File observer start...
,E/UEI.SmartControl( 6490): IR Port is disabled: false
D/UEI.SmartControl( 6490): Starting file observer...
D/UEI.SmartControl( 6490): Extracting JNI libs...
D/UEI.SmartControl( 6490): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6227/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6490): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6490): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6490): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/DownloadManager( 3220): DownloadService onDestroy
D/WeatherAncestor( 2813): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:31:56
D/UpdateThreadPoolManager( 2813): 2 : This is isUpdating : false
D/WeatherAncestor( 2813): connectivity changed - connection : true
D/Weather_cast( 2813): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2813): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:31:56
D/WeatherService( 2813): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/UEI.SmartControl( 6490): --- Selecting new region: 2
I/UEI.SmartControl( 6490): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6490): Platform has CIR...
D/UEI.SmartControl( 6490): NO CIR support, need to check package...
I/UEI.SmartControl( 6490): Model: LG-D722 uses JNI
I/ActivityManager(  854): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6540 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6490): QS Service created
W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2813): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2813): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/libc-netbsd( 6249): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6249): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6249): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6249): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6249): propertyValue:false
,E/UEI.SmartControl( 6490): QS start get config
I/Babel   ( 6249): connection state changed from UNKNOWN to CONNECTED
,D/UEI.SmartControl( 6490): Loading JNI Libs...
,D/UEI.SmartControl( 6490):  configuring local db...
I/ActivityManager(  854): Process com.google.android.music:main (pid 6333) has died
,D/UEI.SmartControl( 6490):  ---- Has DB8: true
,D/UEI.SmartControl( 6490): QS start statue = true Error code = 0
D/UEI.SmartControl( 6490): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6490): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6490): IRRCDataComm has AudioManager!!!!.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6540): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6540): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/irrc_jni( 6490): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6490): IrrcClient ++ 
D/irrcClient( 6490): getIrrcService ++ 
D/irrcClient( 6490): getIrrcService -- 
,D/irrcClient( 6490): IrrcClient -- 
W/irrc_jni( 6490): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6490): Services init done
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6540): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/UEI.SmartControl( 6490): QS Service init finished
I/UEI.SmartControl( 6490): Device manager: loading config....
,D/UEI.SmartControl( 6490): QS Service version name: 0.1.73
D/UEI.SmartControl( 6490): QS Service version code: 1073
D/UEI.SmartControl( 6490): Service requested: Control
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6540): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/UEI.SmartControl( 6490): Config is loaded...
,I/GAv4    ( 6540): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6540):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6540):   adb logcat -s GAv4
D/UEI.SmartControl( 6490):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6490): Notify AllClients services are ready: 0
,W/GAv4    ( 6540): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/UEI.SmartControl( 6490): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6490): -----IControl: 11
D/UEI.SmartControl( 6490): Internal service binding...
D/UEI.SmartControl( 6490): Caller: com.lge.qremote
D/UEI.SmartControl( 6490): ------------ IControl registerCallback...
I/UEI.SmartControl( 6490): Registering callback...
D/UEI.SmartControl( 6490): -----IControl: 19
D/UEI.SmartControl( 6490): Caller: com.lge.qremote
I/UEI.SmartControl( 6490): Registering Services Ready callback...
I/UEI.SmartControl( 6490): Notify client services are ready...
D/UEI.SmartControl( 6490): -----IControl: 8
D/UEI.SmartControl( 6490): Caller: com.lge.qremote
W/GAv4    ( 6540): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6540): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6540): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6540): Time to load native libraries: 2 ms (timestamps 5877-5879)
,I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6540): Binding Chromium to main looper Looper (main, tid 1) {3afb4c58}
I/LibraryLoader( 6540): Expected native library version number "",actual native library version number ""
I/chromium( 6540): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6540): Initializing chromium process, singleProcess=true
W/art     ( 6540): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6540): ApplicationContext is null in ApplicationStatus
,W/chromium( 6540): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6540): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6540): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6540): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6540): Remote Branch: 
I/Adreno-EGL( 6540): Local Patches: 
I/Adreno-EGL( 6540): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb40272a0, uid 10079
,W/AudioManagerAndroid( 6540): Requires BLUETOOTH permission
I/NSApplication( 6540): Starting up...
,I/ActivityManager(  854): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6603 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 4998:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10106/pid_4998/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6626 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 6382:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10021/pid_6382/cgroup.procs: No such file or directory
,W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  854): Killing 6415:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6415/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6657 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6657): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6657): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6657): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6657): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6657): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6657): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6657): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6657): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d82e4a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6657): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6657): GMSCore installation verified
,I/ConfigStore( 6657): Config Database version: 1
,I/MediaRouter( 6657): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6657): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6657): type=WIFI subType= reason=null isConnected=true
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{14c8635a type 0 when 1452267118919 com.google.android.gms} when 1452267118919
V/AlarmManager(  854): RTC_WAKEUP set : Alarm{38c4fa68 type 0 when 1452267119515 com.google.android.googlequicksearchbox} when 1452267119515
,I/NetworkMonitor( 6657): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6698 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6657): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6657): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6698): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6698): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6698): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Killing 6440:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_6440/cgroup.procs: No such file or directory
,I/NotificationManager( 6657): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6698): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6698): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/WeatherService( 2813): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:32:0
,D/WeatherService( 2813): 2 : TimeTick Intent And Screen On
D/WeatherService( 2813): 2 : SDK version : 21
W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2813): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2813): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2813): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2813): 2 : This is isUpdating : false
D/WeatherService( 2813): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2813): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2813): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2813): 2 : Fixed theme : optimus
,D/WeatherReflect( 2813): 2 : Map key string is -2
D/lim     ( 2813): 2 : time = 16:32
,I/WeatherReflect( 2813): Model Name : LG-D722
D/WeatherTheme( 2813): 2 : Different view - status_min_formatted : 31 != 32
D/WeatherTheme( 2813): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
D/WeatherReflect( 2813): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2813): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2813): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/Weather4x2_optimus( 2813): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2813): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2813): forecast size is 0
,D/Theme   ( 2813): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2813): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2813): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2813): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2813): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2813): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2813): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2813): url is : null
D/Theme   ( 2813): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2813): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2813): 2 : update view, appWidgetId: 2
D/WeatherService( 2813): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:32:0
,D/eas_req ( 6698): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  854): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6735 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/HubEmail( 6698): JNI_OnLoad()
I/HubEmail( 6698): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6698): registerNatives()
I/HubEmail( 6698): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6698): registerNativeMethods()
I/HubEmail( 6698): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6698): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  854): Killing 6465:com.google.android.setupwizard/u0a38 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_6465/cgroup.procs: No such file or directory
D/LGDMClient( 6735): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6735): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6735): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6735): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6735): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6735): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6760 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6735): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6735): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6735): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6735): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6735): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  854): Killing 6490:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/libprocessgroup(  854): failed to kill 1 processes for processgroup 6490
,I/AppUp4:AppBoxCP( 6760): onCreate
W/AppUp4:DB( 6760):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6760):  setFingerPrint start
I/AppUp4:DB( 6760):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6760):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6760):  SDK version = 0
I/AppUp4:DB( 6760):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6760): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6760): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6760): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6760): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6760): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6760): onReceive
I/AppUp4:CustModeStarterReceiver( 6760): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6760): Context : android.app.ReceiverRestrictedContext@368a6657
D/AppUp4:CustFacade( 6760): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6760): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6760): begin check event
I/AppUp4:CustModeStarterReceiver( 6760): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 6760): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6760): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6760): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6760): handleAsyncCustNotification do not startCustService
I/ActivityManager(  854): Killing 6521:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_6521/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3198): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3198): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3198): networkInfo.isConnected() = false
I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6785 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6785): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6785): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6785): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  854): Killing 6249:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_6249/cgroup.procs: No such file or directory
,V/DownloadManager( 3220): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3220): DownloadService onCreate
I/DownloadManager( 3220): in removeSpuriousFiles
,I/NotificationManager( 3220): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3220): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@25ca457d on behalf of 3220
I/DownloadManager( 3220): in trimDatabase
V/DownloadManager( 3220): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@33f9dc72 on behalf of 3220
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/PhoneMonitor( 6785): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6785): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6785): [parse] Load xml
I/ActivityManager(  854): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6814 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3220): DownloadService onStartCommand
V/TelephonyAutoProfiling( 6785): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6785): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3220): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4189): Checkin interval check for package: unspecified last checkin: 1452267088978 min interval config: 0 actual interval: 32461
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@18181540 on behalf of 3220
,D/PhoneMonitor( 6785): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 4189): Checking schedule, now: 1452267121485 next: 1452267118919
I/CheckinService( 4189): active receiver: enabled
V/DownloadManager( 3220): DownloadService onDestroy
,I/CheckinService( 4189): Preparing to send checkin request
,I/EventLogService( 4189): Accumulating logs since 1452267082081
,D/WeatherAncestor( 2813): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:32:1
,D/UpdateThreadPoolManager( 2813): 2 : This is isUpdating : false
D/WeatherAncestor( 2813): connectivity changed - connection : true
D/Weather_cast( 2813): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2813): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:32:1
D/WeatherService( 2813): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4189): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6838 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2813): 2 : Utils getTopActivity com.lge.launcher2 / true
E/ActivityThread( 4189): Failed to find provider info for com.google.android.wearable.settings
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 23.400ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.595ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.327ms
,D/WeatherService( 2813): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6838): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  854): Explicit concurrent mark sweep GC freed 18585(1031KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.093ms total 164.423ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  854): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6856 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 6838): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6838): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6838): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6838): MmsConfig.loadFromDatabase
W/ResourcesManager( 6856): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6856): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 6838): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6838): MmsConfig.loadFromResources
E/Babel_SMS( 6838): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6838): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6838): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6838): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6838): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6838): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6838): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6838): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6838): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6838): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6838): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6838): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6838): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6838): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6838): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6838): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6838): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6838): found sensor: Motion Accel, handle=46
,W/Settings( 6838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6838): startup - clean
I/MultiDex( 6856): VM with version 2.1.0 has multidex support
I/MultiDex( 6856): install
I/MultiDex( 6856): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 6838): CheckpointMarkThreadRoots callback created = 0xaaf417b0
,I/Babel   ( 6838): deleted: false for 0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/JNIHelp ( 6856): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 6838): CheckpointMarkThreadRoots callback created = 0xaaf41790
,E/lowmemorykiller(  242): Error writing /proc/6540/oom_score_adj; errno=22
,E/JavaBinder(  854): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  854): Exception when sending broadcast to ComponentInfo{com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider}
W/BroadcastQueue(  854): android.os.TransactionTooLargeException
W/BroadcastQueue(  854): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  854): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  854): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  854): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
W/BroadcastQueue(  854): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
W/BroadcastQueue(  854): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
W/BroadcastQueue(  854): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue(  854): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/BroadcastQueue(  854): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/BroadcastQueue(  854): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityThread( 6856): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6856): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20cf4928: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6856): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  854): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6888 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  854): Spurious death for ProcessRecord{33f0ebbb 6888:com.google.android.apps.magazines/u0a79}, curProc for 6540: null
I/NotificationManager( 6856): com.google.android.gms: cancel(10436) by com.google.android.gms
I/jxcore-log( 6027): Test app app.js loaded
I/jxcore-log( 6027): 
,I/NotificationManager( 6856): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  854): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6905 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  854): RTC_WAKEUP set : Alarm{213c2c1f type 0 when 1452267122488 com.android.vending} when 1452267122488
,W/AudioCapabilities( 6838): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6838): Unsupported mime audio/adpcm
I/chromium( 6027): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/AudioCapabilities( 6838): Unsupported mime audio/g726
,W/AudioCapabilities( 6838): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6838): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6838): Unsupported mime video/mjpg
W/VideoCapabilities( 6838): Unsupported mime video/theora
,W/AudioCapabilities( 6838): Unsupported mime audio/evrc
,W/AudioCapabilities( 6838): Unsupported mime audio/qcelp
W/VideoCapabilities( 6838): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6838): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6838): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6838): Unsupported mime audio/evrc
W/VideoCapabilities( 6838): Unsupported mime video/mp4v-esdp
,I/art     ( 6856): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6856): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/VideoCapabilities( 6838): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6838): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6838): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6838): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6838): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6838): onServiceConnected
W/Babel   ( 6838): Attempted to change video mute state without an active call.
,I/NotificationManager( 6838): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:03.266 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/Finsky  ( 6905): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/libc-netbsd( 6838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6838): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6888): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6888):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6888):   adb logcat -s GAv4
,I/Babel   ( 6838): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/NativeLibraryUtils( 6856): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  854): Process com.google.android.apps.plus (pid 6626) has died
W/GAv4    ( 6888): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/WVCdm   (  284): Instantiating CDM.
,I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
W/GAv4    ( 6888): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6888): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/Finsky  ( 6905): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/WVCdm   (  284): PrepareKeyRequest: nonce=1835187242
W/Settings( 6905): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6905): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6905): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 6905): Skipping gmscore version check
,D/Finsky  ( 6905): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6905): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3220): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@25054dbe on behalf of 6905
D/Finsky  ( 6905): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6905): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WebViewFactory( 6888): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6888): Time to load native libraries: 2 ms (timestamps 2506-2508)
,I/LibraryLoader( 6888): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6888): Binding Chromium to main looper Looper (main, tid 1) {3afb4c58}
,I/LibraryLoader( 6888): Expected native library version number "",actual native library version number ""
I/chromium( 6888): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6888): Initializing chromium process, singleProcess=true
W/art     ( 6888): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6888): ApplicationContext is null in ApplicationStatus
W/chromium( 6888): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6888): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6888): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6888): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6888): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6888): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6888): Remote Branch: 
I/Adreno-EGL( 6888): Local Patches: 
I/Adreno-EGL( 6888): Reconstruct Branch: 
D/Finsky  ( 6905): [860] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6905): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AudioPolicyService(  284): registerClient() client 0xb4027040, uid 10079
,W/AudioManagerAndroid( 6888): Requires BLUETOOTH permission
I/NSApplication( 6888): Starting up...
I/art     ( 6856): CheckpointMarkThreadRoots callback created = 0xb04cbe50
,I/art     ( 6856): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,I/ActivityManager(  854): Process com.google.android.music:main (pid 6657) has died
,I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6998 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 6996): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ResourcesManager( 6998): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 6996): dex2oat took 154.139ms (threads: 4)
,I/Adreno-EGL( 6856): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6856): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6856): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6856): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6856): Remote Branch: 
I/Adreno-EGL( 6856): Local Patches: 
I/Adreno-EGL( 6856): Reconstruct Branch: 
,I/ActivityManager(  854): Process com.lge.email (pid 6698) has died
,I/Adreno-EGL( 6856): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6856): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6856): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6856): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6856): Remote Branch: 
I/Adreno-EGL( 6856): Local Patches: 
I/Adreno-EGL( 6856): Reconstruct Branch: 
I/Adreno-EGL( 6856): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6856): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6856): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6856): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6856): Remote Branch: 
I/Adreno-EGL( 6856): Local Patches: 
I/Adreno-EGL( 6856): Reconstruct Branch: 
,I/WVCdm   (  284): CdmEngine::OpenSession
,I/ActivityManager(  854): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7029 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/MusicStore( 7029): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7029): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7029): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7029): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7029): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7029): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7029): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7029): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7029): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d82e4a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7029): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7029): GMSCore installation verified
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ConfigStore( 7029): Config Database version: 1
,I/art     ( 5497): Explicit concurrent mark sweep GC freed 1788(66KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 510us total 33.225ms
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  854): tsOffsetIs: Apps: 114082060431; DSPS: 3829490; Offset : -2786442321
I/MediaRouter( 7029): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7029): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7029): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7029): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7069 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/GHttpClientFactory( 7029): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7029): Using platform SSLCertificateSocketFactory
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/ResourcesManager( 7069): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7069): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
W/ResourcesManager( 7069): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/WVCdm   (  284): PrepareKeyRequest: nonce=1035965525
I/ActivityManager(  854): Killing 6735:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6735/cgroup.procs: No such file or directory
,I/NotificationManager( 7029): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7069): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7069): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7069): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  854): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7096 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7069): JNI_OnLoad()
I/HubEmail( 7069): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7069): registerNatives()
I/HubEmail( 7069): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7069): registerNativeMethods()
I/HubEmail( 7069): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7069): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7069): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  854): Explicit concurrent mark sweep GC freed 21968(1022KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.846ms total 170.871ms
,I/ActivityManager(  854): Killing 6760:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_6760/cgroup.procs: No such file or directory
D/LGDMClient( 7096): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7096): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7096): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7096): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7096): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7096): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7096): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7096): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7132 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7096): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7096): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7096): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7096): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7096): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7096): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  854): Killing 6785:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_6785/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7132): onCreate
,W/AppUp4:DB( 7132):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7132):  setFingerPrint start
I/AppUp4:DB( 7132):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7132):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7132):  SDK version = 0
I/AppUp4:DB( 7132):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7132): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7132): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7132): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7132): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7132): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7132): onReceive
I/AppUp4:CustModeStarterReceiver( 7132): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7132): Context : android.app.ReceiverRestrictedContext@368a6657
D/AppUp4:CustFacade( 7132): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7132): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7132): begin check event
I/AppUp4:CustModeStarterReceiver( 7132): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7132): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7132): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7132): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7132): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  854): Killing 6814:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_6814/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3198): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3198): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3198): networkInfo.isConnected() = true
D/PhoneState( 3198): setPdpRejectCasuse : false
I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7154 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7154): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7154): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7154): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  854): Killing 6838:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7154): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7154): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7154): [parse] Load xml
V/TelephonyAutoProfiling( 7154): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7154): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7154): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_6838/cgroup.procs: No such file or directory
V/DownloadManager( 3220): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3220): DownloadService onCreate
,I/DownloadManager( 3220): in removeSpuriousFiles
I/NotificationManager( 3220): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3220): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@3fe62e1f on behalf of 3220
,I/ActivityManager(  854): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7176 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/DownloadManager( 3220): in trimDatabase
V/DownloadManager( 3220): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/CheckinService( 4189): Checkin interval check for package: unspecified last checkin: 1452267088978 min interval config: 0 actual interval: 38300
V/DownloadManager( 3220): DownloadService onStartCommand
V/DownloadManager( 3220): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@23c487ca on behalf of 3220
,V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@2c498d3b on behalf of 3220
,V/DownloadManager( 3220): DownloadService onDestroy
,I/ActivityManager(  854): Killing 6888:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  854): failed to open /acct/uid_10079/pid_6888/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2813): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:32:7
,D/UpdateThreadPoolManager( 2813): 2 : This is isUpdating : false
D/WeatherAncestor( 2813): connectivity changed - connection : true
D/Weather_cast( 2813): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2813): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:32:7
,D/WeatherService( 2813): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/MusicWidget( 2690): mDelayedStopHandler : unbind
I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7200 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2813): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 29.588ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.883ms total 23.881ms
,D/WeatherService( 2813): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2813): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 355us total 22.308ms
,W/ResourcesManager( 7200): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MusicBrowser( 2830): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2830): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2830): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2830): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2830): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2830): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  854):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@932349dcom.lge.music.MediaPlaybackService$6@4d66d12
,D/MusicBrowser( 2830): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2830): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@266510f3
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2830): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2830): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/WVCdm   (  284): CdmEngine::CloseSession
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/WVCdm   (  284): L3 Terminate.
I/MusicBrowser( 2830): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2830): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2830): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2830): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2830): reset
,V/MediaPlayer[Native]( 2830): setListener
V/MediaPlayer[Native]( 2830): disconnect
V/MediaPlayer[Native]( 2830): destructor
V/AudioFlinger(  284): releasing 19 from 2830 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/MediaPlayer[Native]( 2830): disconnect
D/MusicBrowser( 2830): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2830): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2830): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2830): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2830): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2830): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2830): [SmartShareManagerClient] unregisterListener: 309599459
W/SmartShareClient( 2830): [SmartShareManagerClient] unregisterListener invalid listener: 309599459
I/SmartShareClient( 2830): [SmartShareManagerClient] terminate service: 2830/MediaPlaybackService/96926705
E/HomeCloudIF( 2830): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2830): [SmartShareManagerClient] unbindService context:android.app.Application@36cfa6e0
V/CloudHub( 2830): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2830): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2830): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2830): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2830): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  854): Killing 6905:com.android.vending/u0a36 (adj 15): empty #11
I/CloudHub( 2830): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,W/libprocessgroup(  854): failed to open /acct/uid_10036/pid_6905/cgroup.procs: No such file or directory
,I/Babel_SMS( 7200): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7200): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7200): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7200): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7200): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7200): MmsConfig.loadFromResources
E/Babel_SMS( 7200): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7200): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7200): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7200): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7200): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7200): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7200): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7200): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7200): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7200): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7200): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7200): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7200): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7200): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7200): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7200): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7200): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7200): found sensor: Motion Accel, handle=46
I/CheckinRequestBuilder( 4189): Classify the device as Phone.
,W/Settings( 7200): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7200): startup - clean
I/Babel   ( 7200): deleted: false for 0
,I/art     ( 7200): CheckpointMarkThreadRoots callback created = 0xb042d4a0
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 7200): CheckpointMarkThreadRoots callback created = 0xb042d480
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 4189): propertyValue:false
,I/ActivityManager(  854): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7237 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AudioCapabilities( 7200): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7200): Unsupported mime audio/adpcm
W/AudioCapabilities( 7200): Unsupported mime audio/g726
W/AudioCapabilities( 7200): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7200): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7200): Unsupported mime video/mjpg
W/VideoCapabilities( 7200): Unsupported mime video/theora
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4189): Sending checkin request (9750 bytes)
W/AudioCapabilities( 7200): Unsupported mime audio/evrc
,W/AudioCapabilities( 7200): Unsupported mime audio/qcelp
W/VideoCapabilities( 7200): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7200): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7200): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7200): Unsupported mime audio/evrc
W/VideoCapabilities( 7200): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7200): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7200): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7200): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7200): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7200): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7200): onServiceConnected
,W/Babel   ( 7200): Attempted to change video mute state without an active call.
I/NotificationManager( 7200): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7200): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7200): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7200): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7200): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 7200): propertyValue:false
I/GAv4    ( 7237): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7237):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7237):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7237): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7237): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7237): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7237): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7200): connection state changed from UNKNOWN to CONNECTED
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7237): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  854): Killing 6603:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7237): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7237): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  854): failed to open /acct/uid_10048/pid_6603/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4189): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4189): Failed to find provider info for com.google.android.wearable.settings
I/WebViewFactory( 7237): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7237): Time to load native libraries: 2 ms (timestamps 7292-7294)
I/LibraryLoader( 7237): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7237): Binding Chromium to main looper Looper (main, tid 1) {3afb4c58}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LibraryLoader( 7237): Expected native library version number "",actual native library version number ""
I/chromium( 7237): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BrowserStartupController( 7237): Initializing chromium process, singleProcess=true
W/art     ( 7237): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7237): ApplicationContext is null in ApplicationStatus
W/chromium( 7237): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/CheckinRequestBuilder( 4189): Classify the device as Phone.
E/libEGL  ( 7237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7237): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7237): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7237): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7237): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7237): Remote Branch: 
I/Adreno-EGL( 7237): Local Patches: 
I/Adreno-EGL( 7237): Reconstruct Branch: 
I/CheckinTask( 4189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4189): Checking schedule, now: 1452267128833 next: 1452794377827
I/CheckinService( 4189): active receiver: disabled
,I/CheckinService( 4189): Checking schedule, now: 1452267128874 next: 1452794377827
I/CheckinService( 4189): active receiver: disabled
,D/CheckinService( 4189): Recording last checkin time for package unspecified as 1452267128886
,V/AudioPolicyService(  284): registerClient() client 0xb57ebe00, uid 10079
,W/AudioManagerAndroid( 7237): Requires BLUETOOTH permission
I/NSApplication( 7237): Starting up...
I/ActivityManager(  854): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7304 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 7069:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  854): Killing 7029:com.google.android.music:main/u0a81 (adj 15): empty #12
,I/ActivityManager(  854): Killing 6998:com.google.android.apps.plus/u0a86 (adj 15): empty #13
,W/libprocessgroup(  854): failed to open /acct/uid_10021/pid_7069/cgroup.procs: No such file or directory
,W/libprocessgroup(  854): failed to open /acct/uid_10081/pid_7029/cgroup.procs: No such file or directory
W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_6998/cgroup.procs: No such file or directory
I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7323 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 7096:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_7096/cgroup.procs: No such file or directory
,W/ResourcesManager( 7323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Killing 7132:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_7132/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  854): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7350 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7350): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  854): Message: 20
D/BluetoothManagerService(  854): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@358ec8bd:true
,D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
I/ActivityManager(  854): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7368 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7350): Create singleton instance
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
D/UEI.SmartControl( 7368): Quickset Services start...
,I/UEI.SmartControl( 7368): Manufacture = LGE
D/UEI.SmartControl( 7368): File observer start...
E/UEI.SmartControl( 7368): IR Port is disabled: false
D/UEI.SmartControl( 7368): Starting file observer...
D/UEI.SmartControl( 7368): Extracting JNI libs...
D/UEI.SmartControl( 7368): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7350): getMode name:com.lge.qremote
,I/CheckinService( 4189): Checkin interval check for package: unspecified last checkin: 1452267128886 min interval config: 0 actual interval: 1190
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,I/CheckinService( 4189): Checking schedule, now: 1452267130109 next: 1452794377827
I/CheckinService( 4189): active receiver: disabled
,E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4189): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
W/ContextImpl( 3578): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SetupWizard( 7154): Connected to Gservices successfully
,I/AudioManager( 7350): getMode name:com.lge.qremote
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7368): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7368): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7368): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/UEI.SmartControl( 7368): --- Selecting new region: 2
,I/UEI.SmartControl( 7368): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7368): Platform has CIR...
D/UEI.SmartControl( 7368): NO CIR support, need to check package...
I/UEI.SmartControl( 7368): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7368): QS Service created
E/UEI.SmartControl( 7368): QS start get config
,D/UEI.SmartControl( 7368): Loading JNI Libs...
,D/UEI.SmartControl( 7368):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7368):  ---- Has DB8: true
,D/UEI.SmartControl( 7368): QS start statue = true Error code = 0
D/UEI.SmartControl( 7368): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7368): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7368): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7368): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7368): IrrcClient ++ 
D/irrcClient( 7368): getIrrcService ++ 
D/irrcClient( 7368): getIrrcService -- 
D/irrcClient( 7368): IrrcClient -- 
W/irrc_jni( 7368): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7368): Services init done
I/UEI.SmartControl( 7368): Device manager: loading config....
D/UEI.SmartControl( 7368): QS Service init finished
D/UEI.SmartControl( 7368): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7368): QS Service version code: 1073
D/UEI.SmartControl( 7368): Service requested: Control
D/UEI.SmartControl( 7368): Config is loaded...
D/UEI.SmartControl( 7368): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7368):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7368): Notify AllClients services are ready: 0
,I/art     (  854): Explicit concurrent mark sweep GC freed 17191(845KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.944ms total 143.099ms
,D/UEI.SmartControl( 7368): Internal service binding...
D/UEI.SmartControl( 7368): -----IControl: 11
D/UEI.SmartControl( 7368): Caller: com.lge.qremote
D/UEI.SmartControl( 7368): ------------ IControl registerCallback...
I/UEI.SmartControl( 7368): Registering callback...
D/UEI.SmartControl( 7368): -----IControl: 19
D/UEI.SmartControl( 7368): Caller: com.lge.qremote
I/UEI.SmartControl( 7368): Registering Services Ready callback...
I/UEI.SmartControl( 7368): Notify client services are ready...
D/UEI.SmartControl( 7368): -----IControl: 8
,D/UEI.SmartControl( 7368): Caller: com.lge.qremote
I/AudioManager( 7350): getMode name:com.lge.qremote
I/AudioManager( 7350): getMode name:com.lge.qremote
,I/AudioManager( 7350): getMode name:com.lge.qremote
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  854): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
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
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  854): Handling package changes for user 0
,I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7446 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ResourcesManager( 7200): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7200): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Process com.google.android.apps.magazines (pid 7237) has died
,I/NotificationManager( 7200): com.google.android.talk: cancel(8) by com.google.android.talk
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,I/AppUp4:AppBoxCP( 7446): onCreate
W/AppUp4:DB( 7446):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7446):  setFingerPrint start
,I/AppUp4:DB( 7446):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7446):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7446):  SDK version = 0
I/AppUp4:DB( 7446):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7446): AppBoxApplication onCreate()
V/JNIHelp ( 7200): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:CustModeStarterReceiver( 7446): onReceive
I/AppUp4:CustModeStarterReceiver( 7446): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7446): Context : android.app.ReceiverRestrictedContext@c684798
D/AppUp4:CustFacade( 7446): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7446): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7446): begin check event
I/AppUp4:CustModeStarterReceiver( 7446): Event For Nothing, skip.
I/ActivityManager(  854): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7467 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/System  ( 7200): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7200): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  854): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  854): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  854): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  854): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  854): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  854): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@227b1e21
,W/ResourcesManager( 7467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7467): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:12.316 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/ResourcesManager(  854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/AppConfig( 7467): Total System Memory = 906309632
,I/GalleryUtils( 7467): Application Heap = 96 MB
I/AppConfig( 7467): App Tier : NOT_DEF
D/SystemHelper( 7467): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  854): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  854): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7487 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  854): applying state to connected service
,W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7487): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7487): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7487): BUILD Country: EU
I/SystemConfig( 7487): BUILD Operator: OPEN
,I/ActivityManager(  854): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7511 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 7176:com.lge.drmservice/u0a51 (adj 15): empty #11
I/ActivityManager(  854): Process com.google.android.apps.plus (pid 7323) has died
,W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_7176/cgroup.procs: No such file or directory
,I/SystemConfig( 7487): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7487): existFile = false
I/SystemConfig( 7487): canReadFile = false
I/SystemConfig( 7487): systemFeature RCS result false
D/SystemConfig( 7487): refreshRcsSupport() :false
I/LockScreenSettings( 7511): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7511): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7511): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7511): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7511): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7511): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7528 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 2830:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  284): 2830 died, releasing its sessions
V/AudioFlinger(  284):  pid 1748 @ 0
,V/AudioFlinger(  284):  pid 3198 @ 1
V/AudioFlinger(  284):  pid 3198 @ 2
W/libprocessgroup(  854): failed to open /acct/uid_10028/pid_2830/cgroup.procs: No such file or directory
,W/ResourcesManager( 7528): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  854): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7556 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 41.752ms
,I/ActivityManager(  854): Killing 7304:com.android.chrome/u0a48 (adj 15): empty #11
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 485us total 20.639ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.042ms
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
,W/libprocessgroup(  854): failed to open /acct/uid_10048/pid_7304/cgroup.procs: No such file or directory
,D/Finsky  ( 7556): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7556): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7556): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7556): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7556): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3220): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@125281b1 on behalf of 7556
D/Ads     ( 7556): Skipping gmscore version check
,D/Finsky  ( 7556): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7556): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7556): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 4189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4189): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4189): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7556): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  854): Killing 7154:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_7154/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/Icing   ( 4189): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4189): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  854): Killing 7446:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_7446/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:15.336 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7368): Internal timer expired: 1
,I/ActivityManager(  854): Killing 7200:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_7200/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:18.353 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/charger_monitor(  490): init target 500000
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:21.377 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:24.4 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 134083190267; DSPS: 4484887; Offset : -2786441090
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{27352430 type 2 when 143622 com.google.android.gms} when 143622
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1452267155340 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 13003 seconds from now (1452267155748)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 43039(2MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 13MB/22MB, paused 1.828ms total 102.250ms
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:36.474 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  854): Explicit concurrent mark sweep GC freed 41470(1945KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.227ms total 201.043ms
,I/PowerManagerService(  854): ALS enabled for SRE
,D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27881 ms ago)
D/qdlights(  854): set_light_backlight: 253
,D/qdlights(  854): set_light_backlight: 249
D/qdlights(  854): set_light_backlight: 246
,D/qdlights(  854): set_light_backlight: 243
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  854): set_light_backlight: 239
D/qdlights(  854): set_light_backlight: 236
,D/qdlights(  854): set_light_backlight: 233
,D/qdlights(  854): set_light_backlight: 229
,D/qdlights(  854): set_light_backlight: 226
,D/qdlights(  854): set_light_backlight: 223
,D/qdlights(  854): set_light_backlight: 219
,D/qdlights(  854): set_light_backlight: 216
,D/qdlights(  854): set_light_backlight: 213
,D/qdlights(  854): set_light_backlight: 209
,D/qdlights(  854): set_light_backlight: 206
,D/qdlights(  854): set_light_backlight: 203
,D/qdlights(  854): set_light_backlight: 199
,D/qdlights(  854): set_light_backlight: 196
,D/qdlights(  854): set_light_backlight: 193
,D/qdlights(  854): set_light_backlight: 189
,D/qdlights(  854): set_light_backlight: 186
,D/qdlights(  854): set_light_backlight: 183
,D/qdlights(  854): set_light_backlight: 179
,D/qdlights(  854): set_light_backlight: 176
,D/qdlights(  854): set_light_backlight: 173
,D/qdlights(  854): set_light_backlight: 169
,D/qdlights(  854): set_light_backlight: 166
,D/qdlights(  854): set_light_backlight: 163
,D/qdlights(  854): set_light_backlight: 159
,D/qdlights(  854): set_light_backlight: 156
,D/qdlights(  854): set_light_backlight: 153
,D/qdlights(  854): set_light_backlight: 149
,D/qdlights(  854): set_light_backlight: 146
,D/qdlights(  854): set_light_backlight: 143
,D/qdlights(  854): set_light_backlight: 139
,D/qdlights(  854): set_light_backlight: 136
,D/qdlights(  854): set_light_backlight: 133
,D/qdlights(  854): set_light_backlight: 129
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/qdlights(  854): set_light_backlight: 126
D/qdlights(  854): set_light_backlight: 123
,D/qdlights(  854): set_light_backlight: 119
,D/qdlights(  854): set_light_backlight: 116
,D/qdlights(  854): set_light_backlight: 113
,D/qdlights(  854): set_light_backlight: 109
,D/qdlights(  854): set_light_backlight: 106
,D/qdlights(  854): set_light_backlight: 103
,D/qdlights(  854): set_light_backlight: 99
,D/qdlights(  854): set_light_backlight: 96
,D/qdlights(  854): set_light_backlight: 93
,D/qdlights(  854): set_light_backlight: 89
,D/qdlights(  854): set_light_backlight: 86
,D/qdlights(  854): set_light_backlight: 83
,D/qdlights(  854): set_light_backlight: 79
,D/qdlights(  854): set_light_backlight: 76
,D/qdlights(  854): set_light_backlight: 73
,D/qdlights(  854): set_light_backlight: 69
,D/qdlights(  854): set_light_backlight: 66
,D/qdlights(  854): set_light_backlight: 63
,D/qdlights(  854): set_light_backlight: 59
,D/qdlights(  854): set_light_backlight: 56
,D/qdlights(  854): set_light_backlight: 53
,D/qdlights(  854): set_light_backlight: 49
,D/qdlights(  854): set_light_backlight: 46
,D/qdlights(  854): set_light_backlight: 43
,D/qdlights(  854): set_light_backlight: 39
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  854): set_light_backlight: 36
,D/qdlights(  854): set_light_backlight: 33
,D/qdlights(  854): set_light_backlight: 29
,D/qdlights(  854): set_light_backlight: 26
,D/qdlights(  854): set_light_backlight: 23
,D/qdlights(  854): set_light_backlight: 19
,D/qdlights(  854): set_light_backlight: 16
,D/qdlights(  854): set_light_backlight: 13
,D/qdlights(  854): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:45.528 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 154084114374; DSPS: 5140277; Offset : -2786432613
,I/PowerManagerService(  854): ALS enabled for SRE
D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34865 ms ago)
I/PowerManagerService(  854): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  854): ALS enabled for SRE
D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34880 ms ago)
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  854): Sleeping (uid 1000)...
,D/LPWGController(  854): [updateScreenState] screen on = false
D/LPWGController(  854): disable proximity sensor
,D/LPWGController(  854): enable proximity sensor
I/SensorManager(  854): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3f299478] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  854): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  854): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  854): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  854): activate: handle is 48, enable
,V/sensors_hal_Ctx(  854): activate sensors is 1400000000000
D/sensors_hal_Thresh(  854): enable: handle=48
I/sensors_hal_SAM(  854): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  854): waitForResponse: timeout=1000
V/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  854): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  854): enable: Received response: 0
D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34945 ms ago)
I/Adreno-EGL(  854): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  854): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  854): Build Date: 03/02/15 Mon
I/Adreno-EGL(  854): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  854): Remote Branch: 
I/Adreno-EGL(  854): Local Patches: 
I/Adreno-EGL(  854): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1054 us)
I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  854): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  854): processInd: handle 48, count=1
V/sensors_hal_Thresh(  854): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  854): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  854): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  854): poll: count: 256
I/sensors_hal_Ctx(  854): poll: released wakelock sensor_ind
D/sensors_hal_Util(  854): waitForResponse: timeout=0
D/LPWGController(  854): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  854): current mode = 1  value = 1 1
I/LPWGController(  854): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  854): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  854): set_light_backlight: 0
,I/SensorManager(  854): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  854): activate: handle is 46, disable
V/sensors_hal_Ctx(  854): activate sensors is 1000000000000
D/sensors_hal_LP2(  854): enable: handle=46
,D/sensors_hal_LP2(  854): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  854): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  854): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  854): Display changed displayId=0
V/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  854): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  854): Excessive delay in setPowerMode(): 209ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  854): Got set_interactive hint
,D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/KeyguardViewMediator( 1369): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/WifiServerServiceExt(  854): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 854
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 16:32:47.367 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  284): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WifiServerServiceExt(  854): set CMD_KT_SCAN_INTERVAL
,D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/GpsLocationProvider(  854): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn off led
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1800): RESTART MSG
,D/SplitWindow(  854): check instance of lgWin Window{170a40b7 u0 SearchPanel}
,I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1800): lockStatus = 0
D/LNfcService( 1782): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1782): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1782): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 3
D/NfcService( 1782): Discovery configuration equal, not updating.
D/InputDispatcher(  854): Window went away: Window{1f91c911 u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,D/Ulp_jni (  854): JNI:system_update. Event-0
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
I/Sensors (  429): sns_pwr.c(301):releasing wakelock
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): ACTION_SCREEN_ON
,D/WeatherService( 2813): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:32:48
D/WeatherService( 2813): 2 : ACTION screen on
D/WeatherService( 2813): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2813): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2813): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:32:48
,D/AppCleanupService( 4042): android.intent.action.SCREEN_ON
V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 854
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/WifiController(  854): CMD_SCREEN_OFF 
D/WifiController(  854): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  854): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn on led
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
D/VolumeVibrator( 1800): clear
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
,I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1782): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1782): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1873): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): ACTION_SCREEN_OFF
D/WeatherService( 2813): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:32:48
D/WeatherService( 2813): 2 : ACTION screen off
,D/WeatherService( 2813): 2 : TimeTick Receiver Unregister
D/WeatherService( 2813): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:32:48
D/AppCleanupService( 4042): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4042): AppUsageStatsSaveTask
,E/NxpNfcJni( 1782): getReconnectState = 0x0
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: 0
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 1
E/NxpNfcJni( 1782): getReconnectState = 0x0
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{339f8024 type 2 when 160847 com.android.systemui} when 160847
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 174084876970; DSPS: 5795663; Offset : -2786463370
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=332183437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{12254d42 type 2 when 186861 com.google.android.gms} when 186861
D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=332183437 [*alarm*], flags=0x0
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{1a783153 type 2 when 188761 android} when 188761
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 194085633369; DSPS: 6451047; Offset : -2786439289
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 214086385705; DSPS: 7106432; Offset : -2786449893
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 234087058822; DSPS: 7761814; Offset : -2786448396
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 254087832044; DSPS: 8417199; Offset : -2786437880
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 274088606515; DSPS: 9072585; Offset : -2786456970
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 294089285049; DSPS: 9727967; Offset : -2786450082
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 314090452438; DSPS: 10383365; Offset : -2786442205
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 334091277482; DSPS: 11038752; Offset : -2786441215
,I/jxcore-log( 6027): TAP version 13
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # multiplex can send data
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 1 String should be length:200
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # basic
I/jxcore-log( 6027): 
,I/LocationManagerService(  854): remove 106c16d8
D/LocationManagerService(  854): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  854): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  854): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  854): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=332183437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=332183437 [*alarm*], flags=0x0
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 354091965288; DSPS: 11694134; Offset : -2786424926
,I/jxcore-log( 6027): ok 2 sane
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # another
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 3 sane
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
I/jxcore-log( 6027): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 4 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 5 null
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 6 (unnamed assert)
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 7 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 8 should not throw
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 374092759030; DSPS: 12349521; Offset : -2786454429
,I/jxcore-log( 6027): ok 9 (unnamed assert)
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 10 (unnamed assert)
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 11 should not throw
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 12 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 13 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 14 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # failed to get mobile documents path
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 15 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 394093506834; DSPS: 13004905; Offset : -2786439333
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 16 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 17 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 18 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # #init should register the networkChanged event
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 19 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # #startBroadcasting should throw on null device name
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 414094270421; DSPS: 13660290; Offset : -2786438947
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): ok 20 should throw
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 434095077652; DSPS: 14315677; Offset : -2786457174
,I/jxcore-log( 6027): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 21 should throw
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 22 should throw
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 23 should throw
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # #startBroadcasting should throw on negative port
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 24 should throw
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # #startBroadcasting should throw on too large port
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 454095830822; DSPS: 14971061; Offset : -2786434967
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 25 should throw
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 26 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 27 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 28 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 29 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 30 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 31 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 474096504929; DSPS: 15626444; Offset : -2786462661
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): ok 32 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 33 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6027): 
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 494097358358; DSPS: 16281831; Offset : -2786432997
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 34 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 35 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 36 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 37 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 38 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 514098031736; DSPS: 16937214; Offset : -2786461863
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 39 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 40 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6027): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): ok 41 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 42 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 534098791937; DSPS: 17592598; Offset : -2786433979
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): ok 43 should be equal
I/jxcore-log( 6027): 
I/jxcore-log( 6027): ok 44 should be equal
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6027): 
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6027): # teardown
I/jxcore-log( 6027): 
,D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558710.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558710.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 2023): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 2023): [BTUI] createSocketChannel FD=87 mFd=85
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558710.6027
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558710.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267558710.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267558710.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2a67912a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2a67912a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
I/jxcore-log( 6027): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
,I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
I/jxcore-log( 6027): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
D/LGWifiP2pService(  854): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558886.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  854): InactiveState{ when=-17ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-17ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2679): p2p0: CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558886.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1800): Event [CTRL-EVENT-SCAN-STARTED ]
,W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
D/LGWifiP2pService(  854): remove client information from framework
D/LGWifiP2pService(  854): InactiveState{ when=-31ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  854): InactiveState{ when=-33ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
D/LGWifiP2pService(  854): P2pEnabledState{ when=-33ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/LGWifiP2pService(  854): P2pEnabledState clear service request
D/LGWifiP2pService(  854): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558886.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558886.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267558886.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267558886.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@20735f0e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@20735f0e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
I/jxcore-log( 6027): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.Wi,fiDirectManager( 6027): release: No more listeners, de-initializing...
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
,D/LGWifiP2pService(  854): remove client information from framework
I/jxcore-log( 6027): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  854): InactiveState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558931.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/LGWifiP2pService(  854): P2pEnabledState{ when=-5ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
D/LGWifiP2pService(  854): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  854): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558931.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558931.6027
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558931.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267558931.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267558931.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8624b260 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8624b260 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6027): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 60,27): setState: NOT_STARTED
I/jxcore-log( 6027): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  854): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558965.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/LGWifiP2pService(  854): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558965.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267558965.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267558965.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267558965.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267558965.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d512ac92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d512ac92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  854): discovery change broadcast true
,I/jxcore-log( 6027): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
D/LGWifiP2pService(  854): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 6027): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
D/LGWifiP2pService(  854): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregr,oundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559007.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559007.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
,I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559007.6027
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559007.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267559007.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267559007.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b302b2a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b302b2a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6027): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  854): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
D/LGWifiP2pService(  854): remove client information from framework
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
I/jxcore-log( 6027): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdap,terProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559044.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559044.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559044.6027
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559044.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267559044.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267559044.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cc271668 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cc271668 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  854): discovery change broadcast true
I/jxcore-log( 6027): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService(  854): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
D/LGWifiP2pService(  854): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
I/jxcore-log( 6027): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559085.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559085.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559085.6027
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559085.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267559085.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267559085.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8fcf269e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8fcf269e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  854): discovery change broadcast true
I/jxcore-log( 6027): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
D/LGWifiP2pService(  854): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
,D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
I/jxcore-log( 6027): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
,D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559129.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559129.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559129.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559129.6027","ra":"F8:95:C7:87:85:54"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267559129.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267559129.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b4d01b60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b4d01b60 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6027): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service
D/LGWifiP2pService(  854): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
I/jxcore-log( 6027): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559166.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:,95:C7:87:85:54
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559166.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559166.6027
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559166.6027","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267559166.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267559166.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@55c7069e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@55c7069e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6027): start: OK
,D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6027): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  854): P2pEnabledState clear service
D/LGWifiP2pService(  854): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  854): P2pEnabledState clear service request
I/jxcore-log( 6027): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
,D/BluetoothAdapterService(310470498)( 2023): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@18c8c6c8
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559200.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): bind: Binding a new listener
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559200.6027","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6027): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 2023): BTA_JvCreateRecordByUser
I/bt-btif ( 2023): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): start: OK
I/io.jxcore.node.ConnectionHelper( 6027): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: Peer ID: F8:95:C7:87:85:54, peer name: 1452267559200.6027
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Waiting for incoming connections...
D/BluetoothManagerService(  854): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6027): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1452267559200.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): start: {"pi":"F8:95:C7:87:85:54","pn":"1452267559200.6027","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1452267559200.6027","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@240d1ef4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@240d1ef4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState add service
D/LGWifiP2pService(  854): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): start: OK
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6027): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6027): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
I/bt-btif ( 2023): BTA_JvDeleteRecord
I/bt-btif ( 2023): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6027): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6027): stop: Stopping services
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6027): Exiting thread
D/LGWifiP2pService(  854): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6027): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6027): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6027): release: No more listeners, de-initializing...
D/LGWifiP2pService(  854): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6027): setState: NOT_STARTED
D/LGWifiP2pService(  854): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2679): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState clear service request
I/jxcore-log( 6027): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6027): 
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): discovery change broadcast false
I/jxcore-log( 6027): # setup
I/jxcore-log( 6027): 
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service req,uests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED,
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6027): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6027): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6027): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6027): Service requests cleared successfully
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 4
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 554099633231; DSPS: 18247986; Offset : -2786447177
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 574100699839; DSPS: 18903381; Offset : -2786448998
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 594101357852; DSPS: 19558763; Offset : -2786462188
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 614102027792; DSPS: 20214145; Offset : -2786463479
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 634102682003; DSPS: 20869526; Offset : -2786450293
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 654103329079; DSPS: 21524907; Offset : -2786444451
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 674103996259; DSPS: 22180289; Offset : -2786448398
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 694104652501; DSPS: 22835671; Offset : -2786463386
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 714105474420; DSPS: 23491057; Offset : -2786434950
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 734106239153; DSPS: 24146442; Offset : -2786433027
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 754109044457; DSPS: 24801894; Offset : -2786435652
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 774109716532; DSPS: 25457277; Offset : -2786465691
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 794110426786; DSPS: 26112660; Offset : -2786457105
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 814111309747; DSPS: 26768048; Offset : -2786428481
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 834111981146; DSPS: 27423431; Offset : -2786459039
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 854112765513; DSPS: 28078816; Offset : -2786437767
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 874113419984; DSPS: 28734198; Offset : -2786455959
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=332183437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{174ba9e5 type 2 when 875548 android} when 875548
D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=332183437 [*alarm*], flags=0x0
,I/ActivityManager(  854): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7885 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/GAv4    ( 7885): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7885):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7885):   adb logcat -s GAv4
,W/GAv4    ( 7885): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7885): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7885): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7885): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7885): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 7885): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7885): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 7885): CheckpointMarkThreadRoots callback created = 0xb050ca10
,V/JNIHelp ( 7885): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 7885): CheckpointMarkThreadRoots callback created = 0xb050c9f0
,W/System  ( 7885): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7885): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiServiceImplEx(  854): acquireWifiLock pid=7885, uid=10058, packageName=com.google.android.apps.docs, tag=BaseSyncManager
,I/PeopleSync( 4189): onPerformSync() [5005f081]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 7885): com.google.android.apps.docs: cancel(1) by com.google.android.apps.docs
,W/Flag    ( 7885): Duration spec must be at least 2 characters long
,D/libc-netbsd( 7885): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7885): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7885): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7885): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  280): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/PeopleSync( 4189): Setting subscription: result=true [5005f081]
,I/System.out( 7885): propertyValue:false
I/PeopleSync( 4189): Starting sync, feed=null [5005f081]
,D/libc-netbsd( 7885): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7885): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/BaseAppContext( 4189): Using Auth Proxy for data requests.
,W/BaseAppContext( 4189): Using Auth Proxy for data requests.
W/BaseAppContext( 4189): Using Auth Proxy for data requests.
,I/PeopleSync( 4189): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 4189): propertyValue:false
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/NotificationManager(  854): android: cancelAsUser(2) by android
,D/libc-netbsd( 7885): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7885): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7885): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7885): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  280): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 7885): propertyValue:false
,D/libc-netbsd( 7885): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7885): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager( 7885): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,D/WifiServiceImplEx(  854): releaseWifiLock pid=7885, uid=10058, packageName=com.google.android.apps.docs
,I/NotificationManager(  854): android: cancelAsUser(-1488629395) by android
,I/PeopleSync( 4189): Sync finished, successful=true, took 1481ms
I/PeopleContactsSync( 4189): CP2 sync start [5005f081]
,I/PeopleContactsSync( 4189): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
I/PeopleContactsSync( 4189): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
I/PeopleContactsSync( 4189): CP2 cleanup done, kept= duration=48 ms
,I/PeopleContactsSync( 4189): ===CP2 sync finished, success=true, time=60,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
I/PeopleSync( 4189): ***Sync finished***, duration: 1889 [5005f081]
,I/ActivityManager(  854): Killing 7467:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/NotificationManager(  854): android: cancelAsUser(148851818) by android
W/libprocessgroup(  854): failed to open /acct/uid_10023/pid_7467/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 894114109873; DSPS: 29389580; Offset : -2786436492
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=332183437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{1dd83ed type 2 when 905861 android} when 905861
I/ActivityManager(  854): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7979 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  854): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=8014 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  854): Explicit concurrent mark sweep GC freed 58969(3MB) AllocSpace objects, 25(400KB) LOS objects, 33% free, 23MB/35MB, paused 2.321ms total 174.841ms
,I/DigitalAppWidgetProvider( 7979): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7979): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@c684798
D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=332183437 [*alarm*], flags=0x0
,I/GoogleURLConnFactory( 4189): Using platform SSLCertificateSocketFactory
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  854): android: cancelAsUser(2) by android
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 4189): propertyValue:false
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 8014): getAccountsCursor,
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 8014): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  854): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 8014): Observing account changes for notifications
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 8014): Sync started for account: account:61035162
,E/Gmail   ( 8014): Error finding the version of the Email provider.....
E/Gmail   ( 8014): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 8014): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 8014): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 8014): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 8014): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 8014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 8014): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 8014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 8014): We do not support migrating this version of the Email provider.
,I/Gmail   ( 8014): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 8014): notifyAccountChanged
,I/Gmail   ( 8014): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 8014): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 8014): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 8014): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 8014): notifyAccountChanged
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 8014): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 8014): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 8014): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14078, normalSync: true
,W/ResourcesManager( 8014): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8014): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 8014): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8014): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8014): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/art     ( 8014): CheckpointMarkThreadRoots callback created = 0xaaf665a0
,D/libc-netbsd( 8014): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8014): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 8014): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8014): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  280): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 8014): CheckpointMarkThreadRoots callback created = 0xaaf667d0
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 8014): propertyValue:false
D/libc-netbsd( 8014): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8014): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  854): Killing 7487:com.android.contacts/u0a18 (adj 15): empty #11
,I/NotificationManager(  854): android: cancelAsUser(2126026182) by android
W/libprocessgroup(  854): failed to open /acct/uid_10018/pid_7487/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=8068 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 8068): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8068): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8068): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/libc-netbsd( 8014): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8014): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AppConfig( 8068): Total System Memory = 906309632
,I/GalleryUtils( 8068): Application Heap = 96 MB
I/AppConfig( 8068): App Tier : NOT_DEF
D/SystemHelper( 8068): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  854): Killing 7511:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/NotificationManager(  854): android: cancelAsUser(-1597574061) by android
W/libprocessgroup(  854): failed to open /acct/uid_10069/pid_7511/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=8095 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8095): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8095): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8095): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8095):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8095):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8095): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8095): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8095): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8095): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8095): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8095): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8095): Time to load native libraries: 2 ms (timestamps 8489-8491)
I/LibraryLoader( 8095): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8095): Binding Chromium to main looper Looper (main, tid 1) {3afb4c58}
I/LibraryLoader( 8095): Expected native library version number "",actual native library version number ""
I/chromium( 8095): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8095): Initializing chromium process, singleProcess=true
,W/art     ( 8095): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8095): ApplicationContext is null in ApplicationStatus
W/chromium( 8095): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8095): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8095): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8095): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8095): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8095): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8095): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8095): Remote Branch: 
I/Adreno-EGL( 8095): Local Patches: 
I/Adreno-EGL( 8095): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb4027260, uid 10079
,W/AudioManagerAndroid( 8095): Requires BLUETOOTH permission
I/NSApplication( 8095): Starting up...
I/SyncAdapterService( 8095): Ignoring sync request for non-current account
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  854): Killing 6856:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,I/NotificationManager(  854): android: cancelAsUser(-701419433) by android
,W/libprocessgroup(  854): failed to open /acct/uid_10006/pid_6856/cgroup.procs: No such file or directory
,I/NotificationManager(  854): android: cancelAsUser(1500439826) by android
,I/ActivityManager(  854): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=8162 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/art     ( 8014): Explicit concurrent mark sweep GC freed 17227(576KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 689us total 60.111ms
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
I/Gmail   ( 8014): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14171, normalSync: true
I/Gmail   ( 8014): lowestBackward conversation id 0
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/MusicStore( 8162): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8162): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     (  854): Explicit concurrent mark sweep GC freed 20983(977KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.564ms total 170.122ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8162): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8162): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/NotificationManager( 8014): com.google.android.gm: cancel(10436) by com.google.android.gm
I/NotificationManager( 8014): com.google.android.gm: cancel(10436) by com.google.android.gm
,W/ResourcesManager( 8162): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8162): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8162): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Gmail   ( 8014): notifyAccountChanged
I/Gmail   ( 8014): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 8014): notifyAccountChanged
,W/Gmail   ( 8014): Sync complete for account: account:61035162
I/Gmail   ( 8014): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(1479798955) by android
,W/ActivityThread( 8162): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8162): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d82e4a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8162): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8162): GMSCore installation verified
I/ConfigStore( 8162): Config Database version: 1
,I/art     ( 4189): Explicit concurrent mark sweep GC freed 29144(1783KB) AllocSpace objects, 14(247KB) LOS objects, 25% free, 14MB/19MB, paused 1.706ms total 92.435ms
,W/BaseAppContext( 4189): Using Auth Proxy for data requests.
W/BaseAppContext( 4189): Using Auth Proxy for data requests.
,W/BaseAppContext( 4189): Using Auth Proxy for data requests.
,W/BaseAppContext( 4189): Using Auth Proxy for data requests.
W/BaseAppContext( 4189): Using Auth Proxy for data requests.
,W/BaseAppContext( 4189): Using Auth Proxy for data requests.
W/BaseAppContext( 4189): Using Auth Proxy for data requests.
,I/MediaRouter( 8162): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NotificationManager(  854): android: cancelAsUser(-379682945) by android
I/ActivityManager(  854): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=8201 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/GHttpClientFactory( 8162): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8162): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 8162): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 8162): Sync started
W/ResourcesManager( 8201): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     ( 8162): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/art     ( 5497): Explicit concurrent mark sweep GC freed 2216(86KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 389us total 33.479ms
,I/art     ( 8162): CheckpointMarkThreadRoots callback created = 0xb042d3b0
,I/ActivityManager(  854): Process com.android.vending (pid 7556) has died
,I/NetworkMonitor( 8162): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 8162): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8162): Using platform SSLCertificateSocketFactory
E/App     ( 8201): [App][onCreate()] 4.40.23
I/NotificationManager( 8162): com.google.android.music: cancel(1061) by com.google.android.music
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(2) by android
D/libc-netbsd( 8162): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8162): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 8162): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 8162): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  280): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 8162): propertyValue:false
,D/libc-netbsd( 8162): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8162): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AccountManager( 8201): setSyncFrequency
,D/libc-netbsd( 8162): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8162): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/DriveSyncService( 8201): onCreate
D/DriveSyncService( 8201): onBind
D/DriveSyncAdapter( 8201): onPerformSync() START
D/DriveSyncAdapter( 8201): Not added account. Stop
I/NotificationManager(  854): android: cancelAsUser(1312559638) by android
,I/Icing   ( 4189): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,I/Icing   ( 4189): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,I/ActivityManager(  854): Killing 7368:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7350): android.os.DeadObjectException
,W/System.err( 7350): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 7350): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 7350): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7350): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7350): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7350): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7350): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7350): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7350): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7350): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7350): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7350): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7350): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7350): android.os.DeadObjectException
W/System.err( 7350): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7350): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7350): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7350): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7350): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7350): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7350): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7350): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7350): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7350): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7350): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7350): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7350): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  854): failed to open /acct/uid_10089/pid_7368/cgroup.procs: No such file or directory
W/ActivityManager(  854): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  854): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8235 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicSyncAdapter( 8162): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 8162): Periodic update
,I/ActivityManager(  854): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=8254 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/MusicApiClient( 8162): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 8162): Sync ended
I/NotificationManager(  854): android: cancelAsUser(-1123058983) by android
,I/ActivityManager(  854): Killing 7350:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 8235): Quickset Services start...
W/BaseAppContext( 1730): Using Auth Proxy for data requests.
,I/UEI.SmartControl( 8235): Manufacture = LGE
D/UEI.SmartControl( 8235): File observer start...
E/UEI.SmartControl( 8235): IR Port is disabled: false
D/UEI.SmartControl( 8235): Starting file observer...
D/UEI.SmartControl( 8235): Extracting JNI libs...
D/UEI.SmartControl( 8235): --- this system supports 32-bit or 64-bit only
E/BaseAppContext( 1730): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/libprocessgroup(  854): failed to open /acct/uid_10106/pid_7350/cgroup.procs: No such file or directory
I/ActivityManager(  854): Process com.google.android.apps.docs (pid 7885) has died
,D/Finsky  ( 8254): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/UEI.SmartControl( 8235): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8235): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8235): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/Finsky  ( 8254): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8254): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8254): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 8254): com.android.vending: cancel(-1050172287) by com.android.vending
I/UEI.SmartControl( 8235): --- Selecting new region: 2
I/UEI.SmartControl( 8235): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8235): Platform has CIR...
D/UEI.SmartControl( 8235): NO CIR support, need to check package...
I/UEI.SmartControl( 8235): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8235): QS Service created
,V/DownloadManager( 3220): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3220): created cursor android.database.sqlite.SQLiteCursor@308b5696 on behalf of 8254
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/UEI.SmartControl( 8235): QS start get config
,I/NotificationManager(  854): android: cancelAsUser(2) by android
D/Ads     ( 8254): Skipping gmscore version check
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Finsky  ( 8254): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8162): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/Finsky  ( 8254): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8254): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 8254): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8162): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/UEI.SmartControl( 8235): Loading JNI Libs...
,D/UEI.SmartControl( 8235):  configuring local db...
I/MusicLeanback( 8162): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 8162): Stop autocaching.
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 4189): propertyValue:false
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4189): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4189): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  854): Explicit concurrent mark sweep GC freed 22711(1000KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.547ms total 164.867ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8162): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,I/GAV2    ( 8014): Thread[GAThread,5,main]: No campaign data found.
,I/GCoreUlr( 1730): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
I/GCoreUlr( 1730): DispatchingService.onCreate()
,I/NotificationManager(  854): android: cancelAsUser(1222422273) by android
D/UEI.SmartControl( 8235):  ---- Has DB8: true
,E/GmsUtils( 8162): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 8162): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/UEI.SmartControl( 8235): QS start statue = true Error code = 0
,D/UEI.SmartControl( 8235): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8235): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8235): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 8235): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8235): IrrcClient ++ 
D/irrcClient( 8235): getIrrcService ++ 
I/NotificationManager(  854): android: cancelAsUser(-1816247584) by android
,D/irrcClient( 8235): getIrrcService -- 
D/irrcClient( 8235): IrrcClient -- 
W/irrc_jni( 8235): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8235): Services init done
I/UEI.SmartControl( 8235): Device manager: loading config....
D/UEI.SmartControl( 8235): QS Service init finished
,D/UEI.SmartControl( 8235): QS Service version name: 0.1.73
D/UEI.SmartControl( 8235): QS Service version code: 1073
D/UEI.SmartControl( 8235): Config is loaded...
D/UEI.SmartControl( 8235): Service requested: Control
D/UEI.SmartControl( 8235): Service.onUnbind: IControl
D/UEI.SmartControl( 8235): Service.onDestroy
I/GCoreUlr( 1730): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/UEI.SmartControl( 8235): Shutdown IRRCPlayer... 
I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
,W/irrc_jni( 8235): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8235): ~IrrcClient ++ 
D/irrcClient( 8235): ~IrrcClient -- 
W/irrc_jni( 8235): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 8235): Blaster closed
D/UEI.SmartControl( 8235): Blaster closed
D/UEI.SmartControl( 8235): Shut down QS...
D/UEI.SmartControl( 8235): Stopped file observer...
,I/UEI.SmartControl( 8235): QS lib stop result = true
I/GCoreUlr( 1730): DispatchingService.onDestroy()
I/GCoreUlr( 1730): Stopping handler for UlrDispSvcFast
D/UEI.SmartControl( 8235): QS shutdown complete
,D/UEI.SmartControl( 8235): QS Service created
I/UEI.SmartControl( 8235): Notify AllClients services are ready: 11
I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
E/UEI.SmartControl( 8235): QS start get config
,E/Auth.Api.Credentials( 4189): [CredentialSyncAdapter] Unknown sync event.
,D/UEI.SmartControl( 8235):  configuring local db...
,I/NotificationManager(  854): android: cancelAsUser(898701380) by android
,I/ActivityManager(  854): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=8334 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/NotificationManager(  854): android: cancelAsUser(-591465577) by android
,D/UEI.SmartControl( 8235):  ---- Has DB8: true
,D/UEI.SmartControl( 8235): QS start statue = true Error code = 0
D/UEI.SmartControl( 8235): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8235): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8235): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 8235): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8235): IrrcClient ++ 
D/irrcClient( 8235): getIrrcService ++ 
D/irrcClient( 8235): getIrrcService -- 
D/irrcClient( 8235): IrrcClient -- 
W/irrc_jni( 8235): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8235): Services init done
I/UEI.SmartControl( 8235): Device manager: loading config....
D/UEI.SmartControl( 8235): QS Service init finished
D/UEI.SmartControl( 8235): Config is loaded...
D/UEI.SmartControl( 8235): QS Service version name: 0.1.73
D/UEI.SmartControl( 8235): QS Service version code: 1073
D/UEI.SmartControl( 8235): Service requested: Control
,I/ActivityManager(  854): Killing 7979:com.lge.clock/u0a10 (adj 15): empty #11
D/UEI.SmartControl( 8235):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8235): Notify AllClients services are ready: 0
,W/libprocessgroup(  854): failed to open /acct/uid_10010/pid_7979/cgroup.procs: No such file or directory
,E/ActivityThread( 8235): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@12816762 that was originally bound here
E/ActivityThread( 8235): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@12816762 that was originally bound here
E/ActivityThread( 8235): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 8235): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 8235): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 8235): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 8235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 8235): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 8235): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 8235): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 8235): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 8235): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 8235): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 8235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 8235): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 8235): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 8235): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 8235): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 8235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 8235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 8235): Internal service binding...
,I/GAv4    ( 8334): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8334):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8334):   adb logcat -s GAv4
,W/GAv4    ( 8334): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8334): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8334): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 8334): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8334): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 8334): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8334): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 8334): CheckpointMarkThreadRoots callback created = 0xaaf00ff0
,V/JNIHelp ( 8334): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 8334): CheckpointMarkThreadRoots callback created = 0xb050c9f0
,W/System  ( 8334): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8334): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  854): Killing 8068:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/NotificationManager(  854): android: cancelAsUser(-1488629395) by android
W/libprocessgroup(  854): failed to open /acct/uid_10023/pid_8068/cgroup.procs: No such file or directory
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 8235): Internal timer expired: 2
,W/System.err( 8235): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@12816762
W/System.err( 8235): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 8235): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 8235): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8235): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8235): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 8235): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 8235): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 8235): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@12816762
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 914114924240; DSPS: 30044967; Offset : -2786445736
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,E/GmsUtils( 8162): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 8162): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 8162): Stop autocaching.
E/GmsUtils( 8162): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/UEI.SmartControl( 8235): file observer is disposed!
,D/UEI.SmartControl( 8235): Internal timer expired: 3
,D/UEI.SmartControl( 8235): Service.onUnbind: IControl
D/UEI.SmartControl( 8235): Service.onDestroy
W/System.err( 8235): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1635c94f
W/System.err( 8235): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 8235): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 8235): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8235): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8235): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8235): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 8235): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 8235): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 8235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8235): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8235): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 8235): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8235): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 8235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 8235): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1635c94f
D/UEI.SmartControl( 8235): Shutdown IRRCPlayer... 
W/irrc_jni( 8235): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8235): ~IrrcClient ++ 
D/irrcClient( 8235): ~IrrcClient -- 
W/irrc_jni( 8235): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 8235): Blaster closed
D/UEI.SmartControl( 8235): Blaster closed
D/UEI.SmartControl( 8235): Shut down QS...
I/UEI.SmartControl( 8235): QS lib stop result = true
D/UEI.SmartControl( 8235): QS shutdown complete
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 934115591315; DSPS: 30700349; Offset : -2786449788
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{39f9b8cc type 2 when 936163 android} when 936163
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/NotificationManager( 8162): com.google.android.music: cancel(10436) by com.google.android.music
,I/NotificationManager( 8162): com.google.android.music: cancel(10436) by com.google.android.music
,I/NotificationManager( 8162): com.google.android.music: cancel(10436) by com.google.android.music
,I/NotificationManager( 8162): com.google.android.music: cancel(10436) by com.google.android.music
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 79761(4MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 15MB/25MB, paused 2.167ms total 173.678ms
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=332183437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{4ab26ce type 2 when 952424 com.android.bluetooth} when 952424
D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=332183437 [*alarm*], flags=0x0
,W/bt-smp  ( 2023): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2023): Plain text(LSB ~ MSB) = 83 a0 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2023): Encrypted text(LSB ~ MSB) = 94 c5 63 cc ef 25 fe 9b 6a bb 59 e9 cc f9 63 7e 
W/bt-btm  ( 2023): Stopping oneshot timer
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 954116270892; DSPS: 31355731; Offset : -2786442352
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 974117014790; DSPS: 32011116; Offset : -2786460769
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 994117774626; DSPS: 32666501; Offset : -2786464028
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ClearcutLoggerApiImpl( 4189): disconnect managed GoogleApiClient
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{340679ef type 2 when 1000838 com.google.android.gms} when 1000838
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1014118450295; DSPS: 33321883; Offset : -2786459823
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1034119112579; DSPS: 33977264; Offset : -2786438461
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1054119841166; DSPS: 34632648; Offset : -2786442140
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1074120833294; DSPS: 35288041; Offset : -2786456753
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1094121516046; DSPS: 35943423; Offset : -2786446274
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1114122181352; DSPS: 36598805; Offset : -2786451573
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1134123005354; DSPS: 37254192; Offset : -2786451467
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1154123759565; DSPS: 37909577; Offset : -2786460587
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1174124602110; DSPS: 38564964; Offset : -2786441729
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1194125265487; DSPS: 39220346; Offset : -2786449662
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1214125932511; DSPS: 39875728; Offset : -2786454024
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  854): User[0] Flushing usage stats to disk
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1234126599482; DSPS: 40531110; Offset : -2786458778
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1254127358485; DSPS: 41186494; Offset : -2786432041
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1274128031498; DSPS: 41841877; Offset : -2786461375
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1294128777949; DSPS: 42497261; Offset : -2786446852
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1314129523722; DSPS: 43152646; Offset : -2786464147
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1334130571893; DSPS: 43808040; Offset : -2786453236
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1354131215114; DSPS: 44463421; Offset : -2786451144
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1374131875628; DSPS: 45118803; Offset : -2786463657
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1394132550828; DSPS: 45774185; Offset : -2786458881
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1414133207331; DSPS: 46429566; Offset : -2786442726
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1434133948730; DSPS: 47084951; Offset : -2786463850
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1454134711847; DSPS: 47740336; Offset : -2786464558
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1474135560901; DSPS: 48395723; Offset : -2786439348
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1494136240998; DSPS: 49051106; Offset : -2786460687
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1514137004636; DSPS: 49706491; Offset : -2786460014
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1534137748899; DSPS: 50361875; Offset : -2786448355
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1554138401860; DSPS: 51017256; Offset : -2786436316
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1574139252946; DSPS: 51672644; Offset : -2786439228
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1594139988564; DSPS: 52328028; Offset : -2786436162
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1614140723192; DSPS: 52983412; Offset : -2786434060
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1634141479278; DSPS: 53638797; Offset : -2786440704
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1654142241667; DSPS: 54294182; Offset : -2786441098
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1674143001919; DSPS: 54949567; Offset : -2786443969
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 262, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1694143679254; DSPS: 55604949; Offset : -2786438411
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1714144340706; DSPS: 56260331; Offset : -2786447981
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1734144999813; DSPS: 56915713; Offset : -2786460391
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1754145667462; DSPS: 57571095; Offset : -2786464493
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1774146417297; DSPS: 58226479; Offset : -2786446742
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1794147180050; DSPS: 58881864; Offset : -2786446928
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1814147954209; DSPS: 59537249; Offset : -2786436021
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1834149336389; DSPS: 60192655; Offset : -2786457076
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=332183437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{171bdf85 type 2 when 1852472 com.android.bluetooth} when 1852472
,W/bt-smp  ( 2023): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2023): Plain text(LSB ~ MSB) = 08 72 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2023): Encrypted text(LSB ~ MSB) = 70 09 17 c8 09 84 45 d1 b0 e8 bd a7 61 91 63 1c 
W/bt-btm  ( 2023): Stopping oneshot timer
I/ProcessStatsService(  854): Prepared write state in 13ms
,I/ActivityManager(  854): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8530 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ProcessStatsService(  854): Prepared write state in 19ms
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 435us total 40.080ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 403us total 33.460ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 400us total 29.940ms
,I/DigitalAppWidgetProvider( 8530): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8530): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@c684798
D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=332183437 [*alarm*], flags=0x0
I/ActivityManager(  854): Killing 8095:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10079/pid_8095/cgroup.procs: No such file or directory
,I/ProcessStatsService(  854): Pruning old procstats: /data/system/procstats/state-2016-01-07-22-55-16.bin
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1854149988100; DSPS: 60848036; Offset : -2786447275
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{3ad6e1da type 0 when 1452268859203 com.google.android.gms} when 1452268859203
,I/EventLogService( 4189): Aggregate from 1452267121533 (log), 1452267059138 (data)
,D/LocationManagerService(  854): getAllProviders()=[passive, gps, network]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1874150674395; DSPS: 61503419; Offset : -2786462418
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 1894151345377; DSPS: 62158801; Offset : -2786462379
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{32285018 type 2 when 1901019 com.google.android.gms} when 1901019
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
,D/HeadsetStateMachine( 2023): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,TIME-OUT KILL (timeout was 1800000ms),D/WifiController(  854): battery changed pluggedType: 2
D/AndroidRuntime( 8610): 
D/AndroidRuntime( 8610): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8610): CheckJNI is OFF
D/AndroidRuntime( 8610): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  854): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  854): Killing 6027:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  854): Skipping PackageSetting{278473db com.example.hello/10317} due to missing metadata
I/WindowState(  854): WIN DEATH: Window{a7a0aa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  854): Focus left window: Window{a7a0aa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  854): Window went away: Window{a7a0aa u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  854):   Force finishing activity ActivityRecord{3892959f u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  854): Display changed displayId=0
D/DSDPConnection( 1748): Display #0 changed.
W/ActivityManager(  854): Spurious death for ProcessRecord{2e219a71 6027:com.test.thalitest/u0a316}, curProc for 6027: null
I/ActivityManager(  854): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/InputReader(  854): Reconfiguring input devices.  changes=0x00000010
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
W/System.err( 3578): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3578): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3578): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3578): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3578): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3578): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3578): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3578): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3578): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3578): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3578): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3578): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8646 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [Launcher.java:5203:onStart()]onStart
I/art     ( 1941): Explicit concurrent mark sweep GC freed 9748(662KB) AllocSpace objects, 4(96KB) LOS objects, 40% free, 12MB/20MB, paused 2.534ms total 139.336ms
I/art     ( 4189): Explicit concurrent mark sweep GC freed 6716(354KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 15MB/20MB, paused 914us total 136.498ms
I/[LGHome]EVENT( 1873): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  854): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8654 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1873): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1873): [Launcher.java:929:onResume()]onResume end
I/Activity( 1873): Activity.onPostResume() called 
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
I/art     (  854): Explicit concurrent mark sweep GC freed 39998(2MB) AllocSpace objects, 11(355KB) LOS objects, 33% free, 23MB/35MB, paused 4.748ms total 271.144ms
I/art     (  854): WaitForGcToComplete blocked for 262.405ms for cause Explicit
W/[LGHome]LGWallpaperInfo( 1873): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1873): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/LockScreenSettings( 8654): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/SystemUI[Framework](  854): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourcesManager( 8646): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/InputDispatcher(  854): Focus entered window: Window{6d6dd4a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourcesManager( 8646): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/PhoneWindowManagerEx(  854): Call!!!getLGSystemUiVisibility. =0x0
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/StatusBarManagerServiceEx(  854): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  854): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f3a9e87,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  854): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  854): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  854): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  854): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f3a9e87,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 8646): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/administrator(  854): Handling package changes for user 0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1369): handleShortcutListChanged...
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
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
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/ActivityManager(  854): Killing 7528:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/PhoneWindow( 1873): [setNavigationBarColor] color=0x 0
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_7528/cgroup.procs: No such file or directory
D/KeyguardModel( 1369): handleShortcutListChanged...
I/art     (  854): Explicit concurrent mark sweep GC freed 6494(368KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.280ms total 299.294ms
I/LGEmail ( 8646): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8646): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 8610): Shutting down VM
W/InputMethodManagerService(  854): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  854): Got RemoteException sending setActive(false) notification to pid 6027 uid 10316
D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  854): Timeline: Activity_windows_visible id: ActivityRecord{178ed8ef u0 com.lge.launcher2/.Launcher t219} time:1905529
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/NotificationService(  854): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  854): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/JobSchedulerService(  854): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/TaskPersister(  854): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
W/IInputConnectionWrapper( 1873): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1873): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1873): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1599): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1873): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
I/PackageChangeReceiver( 8646): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8692 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  854): Killing 8014:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10053/pid_8014/cgroup.procs: No such file or directory
W/ResourcesManager(  854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 8692): onCreate
W/AppUp4:DB( 8692):  [AppBoxDatabaseHelper] construct
E/SQLiteDatabase( 8692): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 8692): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8692): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8692): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8692): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8692): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 8692): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8692): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8692): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8692): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8692): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8692): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8692): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8692): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8692): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8692): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8692): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8692): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8692): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8692): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 8692): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8692): FATAL EXCEPTION: main
E/AndroidRuntime( 8692): Process: com.lge.appbox.client, PID: 8692
E/AndroidRuntime( 8692): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8692): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8692): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8692): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8692): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8692): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8692): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8692): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8692): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8692): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8692): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8692): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8692): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8692): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8692): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8692): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8692): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8692): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 8692): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8692): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8692): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8692): 	... 11 more

```
