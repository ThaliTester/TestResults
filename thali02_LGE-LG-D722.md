#### Test 56151093914d164_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
D/AndroidRuntime( 6051): 
D/AndroidRuntime( 6051): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6051): CheckJNI is OFF
D/AndroidRuntime( 6051): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  852): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  852): setTaskToReturnTo : TaskRecord{18549e69 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  852): setTaskToReturnTo : TaskRecord{18549e69 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/WindowStateEx(  852): AppWindowTokenEx init.. 
D/ContextHelper(  852): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  852): Focus left window: Window{13bb6665 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6051): Shutting down VM
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  852): check instance of lgWin Window{1b7edfab u0 Starting com.test.thalitest}
I/ActivityManager(  852): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6071 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  852): Starting window displayed
I/SystemUI[Framework](  852): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  852): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  852): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  852): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  852): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25645387,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  852): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/HotwordDetector( 1936): Closing mic
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = 15000000
,I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@e3af7c4
D/BarTransitions( 1373): draw background and invalidate : color = 211f1f1f
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioFlinger(  284): Record stopped OK
V/AudioPolicyManager(  284): stopInput() input 17
V/AudioPolicyService(  284): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  284): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch handle 18
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  284): ThreadBase::setParameters() routing=0
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
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb3846000
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
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb3846000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  852): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1983): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioSystem( 3253): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread 0xb3846000 exiting
V/AudioFlinger(  284): releasing 16 from 1936 for -1
V/AudioSystem( 2814): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): releaseInput() exit
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  284): removeClient_l() pid 1936, calling pid 284
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
D/ContextHelper( 6071): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6071): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 94248554758; DSPS: 3180102; Offset : -2811919438
I/LibraryLoader( 6071): Time to load native libraries: 3 ms (timestamps 4289-4292)
I/LibraryLoader( 6071): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6071): Binding Chromium to main looper Looper (main, tid 1) {9f55f5f}
I/LibraryLoader( 6071): Expected native library version number "",actual native library version number ""
I/chromium( 6071): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6071): Initializing chromium process, singleProcess=true
W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6071): ApplicationContext is null in ApplicationStatus
W/chromium( 6071): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6071): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6071): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6071): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6071): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6071): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6071): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6071): Remote Branch: 
I/Adreno-EGL( 6071): Local Patches: 
I/Adreno-EGL( 6071): Reconstruct Branch: 
D/Finsky  ( 5616): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  852): RTC_WAKEUP set : Alarm{38ed9923 type 0 when 1453042943613 com.android.vending} when 1453042943613
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  852): android: cancelAsUser(2) by android
,V/AudioPolicyService(  284): registerClient() client 0xb4027340, uid 10316
,D/BluetoothManagerService(  852): Message: 20
D/BluetoothManagerService(  852): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@141a007c:true
,D/BluetoothAdapterService(138056315)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@24700529
D/AlertService( 5880): Beginning updateAlertNotification
D/AlertService( 5880): No fired or scheduled alerts
,I/NotificationManager( 5880): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(7) by com.android.calendar
,I/NotificationManager( 5880): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5880): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5880): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/libc-netbsd( 5616): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5616): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5616): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5616): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5616): propertyValue:false
D/libc-netbsd( 5616): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5616): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AlarmScheduler( 5880): No events found starting within 1 week.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6071): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6071): CordovaWebView is running on device made by: LGE
,W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6071): Activity.onPostResume() called 
,D/libc-netbsd( 5616): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5616): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/OpenGLRenderer( 6071): Render dirty regions requested: true
I/OpenGLRenderer( 6071): Initialized EGL, version 1.4
D/OpenGLRenderer( 6071): Enabling debug mode 0
,D/Atlas   ( 6071): Validating map...
,D/SplitWindow(  852): check instance of lgWin Window{301c80ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6071): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  852): Focus entered window: Window{301c80ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  852): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  852): Displayed com.test.thalitest/.MainActivity: +1s235ms
I/Timeline(  852): Timeline: Activity_windows_visible id: ActivityRecord{1281a0ee u0 com.test.thalitest/.MainActivity t222} time:95030
,I/ActivityManager(  852): Killing 5880:com.android.calendar/u0a13 (adj 15): empty #11
I/Timeline( 6071): Timeline: Activity_idle id: android.os.BinderProxy@1f9859ba time:95042
,W/libprocessgroup(  852): failed to open /acct/uid_10013/pid_5880/cgroup.procs: No such file or directory
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BindingManager( 6071): Cannot call determinedVisibility() - never saw a connection for the pid: 6071
I/NotificationManager(  852): android: cancelAsUser(2) by android
,I/qtaguid ( 5616): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5616): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5616): untagSocket(41) failed with errno -22
D/Finsky  ( 5616): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/JsMessageQueue( 6071): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  852): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6154 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  852): android: cancelAsUser(2) by android
,W/ResourcesManager( 6154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6154): VM with version 2.1.0 has multidex support
,I/MultiDex( 6154): install
I/MultiDex( 6154): VM has multidex support, MultiDex support library is disabled.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/JNIHelp ( 6154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6154): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31634c09: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6154): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 5616): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5616): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5616): untagSocket(41) failed with errno -22
I/ActivityManager(  852): Process com.google.android.talk (pid 5327) has died
,I/NotificationManager( 6154): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6154): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4210): Restart initialization of location
E/MDM     ( 1730): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6154): Reading stored module config
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,D/jxcore_app_log( 6071): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622836224
D/JX-Cordova( 6071): jxcore cordova android initializing
,D/ChimeraCfgMgr( 6154): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 6071): CheckpointMarkThreadRoots callback created = 0x9a1ba3d0
,D/NativeLibraryUtils( 6154): Install completed successfully. count=14 extracted=0
I/art     ( 6071): CheckpointMarkThreadRoots callback created = 0x9a1ba3a0
,I/art     ( 5616): CheckpointMarkThreadRoots callback created = 0xb058b340
,I/art     ( 5616): CheckpointMarkThreadRoots callback created = 0xb058b300
,D/CAR.SERVICE( 6154): Connecting to CarCallService...
I/art     ( 6154): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6154): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6154): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6154): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6154): Creating a new PhoneAdapter instance
W/ActivityManager(  852): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6154): setListener: com.google.android.gms.car.dn@2403f66c
W/ActivityManager(  852): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6154): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6154): Starting CarCallService with initial phone null
I/NotificationManager( 6154): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5596): Explicit concurrent mark sweep GC freed 8030(404KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 444us total 48.400ms
,D/CAR.SERVICE( 6154): Package validated; name: com.android.vending
,I/NotificationManager( 5616): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5616): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  852): Explicit concurrent mark sweep GC freed 28702(1446KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.649ms total 202.754ms
,D/UEI.SmartControl( 6006): Internal timer expired: 1
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  852): android: cancelAsUser(2) by android
,I/qtaguid ( 5616): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5616): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5616): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5616): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5616): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5616): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  852): Process com.android.gallery3d (pid 5942) has died
,D/Finsky  ( 5616): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  852): RTC_WAKEUP set : Alarm{179e297d type 0 when 1453042946669 com.android.vending} when 1453042946669
,D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/Finsky  ( 5616): [689] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  852): android: cancelAsUser(2) by android
,D/Finsky  ( 5616): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5616): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5616): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5616): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5616): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5616): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 5616): propertyValue:false
I/ActivityManager(  852): Process com.android.contacts (pid 5456) has died
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:27.011 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/jxcore-log( 6071): Initializing JXcore engine
W/jxcore-log( 6071): JXcore engine is ready
,W/jxcore-log( 6071): Starting JXcore engine
,I/art     ( 6071): Background sticky concurrent mark sweep GC freed 49714(4MB) AllocSpace objects, 0(0B) LOS objects, 12% free, 23MB/26MB, paused 2.544ms total 100.776ms
,I/ActivityManager(  852): Process com.google.android.apps.plus (pid 5559) has died
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,W/.test.thalitest( 6071): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8422]" dev="sockfs" ino=8422 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6071): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6071): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7724]" dev="sockfs" ino=7724 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6071): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6071): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6071): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24206]" dev="sockfs" ino=24206 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6071): Platform android
W/jxcore-log( 6071): 
,W/jxcore-log( 6071): Process ARCH arm
W/jxcore-log( 6071): 
I/ActivityManager(  852): Process com.lge.lockscreensettings (pid 5476) has died
,V/AlarmManager(  852): RTC_WAKEUP set : Alarm{1466913b type 0 when 1453042948127 com.google.android.googlequicksearchbox} when 1453042948127
,I/jxcore-log( 6071): JXcore Cordova bridge is ready!
I/jxcore-log( 6071): 
,W/jxcore-log( 6071): JXcore engine is started
I/chromium( 6071): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6071): Skipped 206 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 6071): Toggling radios to true
I/jxcore-log( 6071): 
,D/BluetoothAdapter( 6071): enable(): BT is already enabled..!
D/WifiServiceImplEx(  852): setWifiEnabled: true pid=6071, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  852): setWifiEnabled: true pid=6071, uid=10316
D/WifiServiceImplEx(  852): disconnect pid=6071, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  852): reconnect pid=6071, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6071): Radios toggled
I/jxcore-log( 6071): 
I/jxcore-log( 6071): My device name is: LGE-LG-D722
I/jxcore-log( 6071): 
I/wpa_supplicant( 2752): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 2752): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/WifiStateMachine(  852): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  852): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  852): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  852): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  852): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Clearing all IP addresses on wlan0
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): Read error: ssl=0xb045d600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb045d600: I/O error during system call, Broken pipe
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  852): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  852): hidePasspointNotification off =false
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:28.959 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  852): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  852): ignoring duplicate network state non-change
D/ConnectivityService(  852): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): ValidatedState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): DefaultState{ when=-26ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): Forcing reevaluation
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
,I/ActivityManager(  852): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6239 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  852): Start Disconnecting Watchdog 1
D/WifiHS20(  852): hidePasspointNotification off =false
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  852): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  852): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2752): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:29.04 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  852): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  852): disableDataServiceNotify
D/DSQN    (  852): stop dsqn bin
D/WifiHS20(  852): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:29.059 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiNetworkAgent(  852): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:29.074 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  852): hidePasspointNotification off =false
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  852): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:29.079 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateDISCONNECTED
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  852): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): Disconnected - quitting
D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateSCANNING
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  852): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  852): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  852): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  852): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  852): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  852): MasterInitialState.processMessage what=3
V/NetworkPolicy(  852): [LG_RESTRICTED] !!!isConnected  type  :1
,D/ConnectivityService(  852): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  852): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  852): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  852):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/QCNEJ   ( 1839): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/QCNEJ   ( 1839): |CORE| No family connected
D/Tethering(  852): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  852): Removing idletimer
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  852): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
D/DhcpStateMachine(  852): StoppedState
D/DhcpStateMachine(  852): StoppedState{ when=-98ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6239): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6239): Using schema version: 115
,I/IndexDatabaseHelper( 6239): Index is fine
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/ActivityManager(  852): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6264 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  852): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6286 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6286): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2752): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Babel_SMS( 6286): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6286): MmsConfig.loadMmsSettings
D/LocSvc_java(  852): onReceive
,W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.193 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.195 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateASSOCIATING
I/wpa_supplicant( 2752): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Babel_SMS( 6286): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6286): MmsConfig.loadFromDatabase
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateASSOCIATED
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.228 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/wpa_supplicant( 2752): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2752): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.243 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/WifiServiceExtension(  852): setVHTCapabilityType  : false
E/Babel_SMS( 6286): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6286): MmsConfig.loadFromResources
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/Babel_SMS( 6286): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6286): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/WifiServerServiceExt(  852): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  852): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  852): setSecurityType  : 2
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.287 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.289 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  852): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  852): Got NetworkAgent Messenger
D/ConnectivityService(  852): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  852): NetworkAgent connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  852): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  852): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  852): Start Dhcp Watchdog 2
D/DhcpStateMachine(  852): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  852): WaitBeforeStartState
D/SensorManager( 6286): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6286): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6286): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6286): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6286): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6286): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6286): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6286): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6286): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6286): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6286): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6286): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6286): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6286): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6286): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6286): found sensor: Motion Accel, handle=46
,I/ActivityManager(  852): Process com.android.providers.calendar (pid 5980) has died
,D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  852): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.458 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 6286): CheckpointMarkThreadRoots callback created = 0xb042d4d0
,W/Settings( 6286): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6286): startup - clean
I/Babel   ( 6286): deleted: false for 0
I/art     ( 6286): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,E/WifiStateMachine(  852): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  852): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  852): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f1202d target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  852): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f1202d target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  852): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  852): WaitBeforeStartState{ when=-2ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Setting iface cfg
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/DhcpStateMachine(  852): DHCP Start wake lock is acquired.
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  852): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  852): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  852): setSupplicantStateCOMPLETED
D/ConnectivityService(  852): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  852): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  852): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  852): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  852): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  852): ignoring duplicate network state non-change
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.568 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.578 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  852): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  852): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiHS20(  852): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
E/WifiStateMachine(  852): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.6 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  852): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  852): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  852): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:30.607 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  852): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  280): netlink response contains error (File exists)
D/ConnectivityService(  852): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  852): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  852): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  852): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  852): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  852): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  852):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  852):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  852):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  852): currentScore = 0, newScore = 20
D/ConnectivityService(  852):    accepting network in place of null
D/ConnectivityService(  852): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  852): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  852):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score,=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/ConnectivityService(  852): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  852): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  852): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  852): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  852): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1839): |CORE| No family connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  852): MasterInitialState.processMessage what=3
D/ConnectivityService(  852): validation of new default Network = false
D/ConnectivityService(  852): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  852): enableDataServiceNotify 
D/DSQN    (  852): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): [LWD] wait 500ms before dns check
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
W/AudioCapabilities( 6286): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6286): Unsupported mime audio/adpcm
V/NetworkPolicy(  852): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService(  852): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/DSQN    ( 6323): DSQN samuel.seo ver 141203
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/DSQN    ( 6323): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6323): created command queue thread
I/DSQN    ( 6323): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6323): Interface wlan0 netmask 255.255.255.0 0xc0a80186
W/AudioCapabilities( 6286): Unsupported mime audio/g726
W/AudioCapabilities( 6286): Unsupported mime audio/x-ms-wma
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
W/AudioCapabilities( 6286): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/VideoCapabilities( 6286): Unsupported mime video/mjpg
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/VideoCapabilities( 6286): Unsupported mime video/theora
D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6239): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
,W/AudioCapabilities( 6286): Unsupported mime audio/evrc
W/AudioCapabilities( 6286): Unsupported mime audio/qcelp
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6286): Unrecognized profile 2130706433 for video/avc
,D/DhcpStateMachine(  852): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  852): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  852): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
W/AudioCapabilities( 6286): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6286): Unsupported mime audio/qcelp
,I/dhcpcd  ( 6326): version 5.5.6 starting
E/dhcpcd  ( 6326): get_duid: Read-only file system
W/AudioCapabilities( 6286): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CAR.SERVICE( 6154): mConnectedToCar = false, abort
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
E/ActivityThread( 6154): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@20dd60d4 that was originally bound here
E/ActivityThread( 6154): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@20dd60d4 that was originally bound here
E/ActivityThread( 6154): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6154): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6154): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6154): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6154): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6154): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6154): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6154): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6154): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6154): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6154): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6154): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6154): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6154): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6154): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6154): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6154): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6154): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6154): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6154): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6154): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6154): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1149031f that was originally bound here
E/ActivityThread( 6154): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1149031f that was originally bound here
E/ActivityThread( 6154): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6154): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6154): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6154): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6154): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6154): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6154): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6154): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6154): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6154): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6154): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6154): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6154): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6154): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6154): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6154): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6154): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6154): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6154): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6154): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  852): Unbind failed: could not find connection for android.os.BinderProxy@16855dcc
W/VideoCapabilities( 6286): Unsupported mime video/mp4v-esdp
I/dhcpcd  ( 6326): wlan0: rebinding lease of 192.168.1.134
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/VideoCapabilities( 6286): Unsupported profile 4 for video/mp4v-es
,V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6286): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
,W/VideoCapabilities( 6286): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6286): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6286): Unrecognized profile 2130706433 for video/avc
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/vclib   ( 6286): onServiceConnected
W/Babel   ( 6286): Attempted to change video mute state without an active call.
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager( 6286): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/dhcpcd  ( 6326): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6239): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6239): MCCMNC not supported: null
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/dhcpcd  ( 6326): wlan0: leased 192.168.1.134 for 86400 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): [LWD] DNSResolver start dns
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  852): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6323): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6323): restart monitoring
,D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  852): DSQM DsqnNotification wlan0  1
D/DSQN    (  852): start to monitor internet connection
I/DSQN    ( 6323): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:02:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453042951222], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453042951199]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  852): Validated
D/ConnectivityService(  852): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  852):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  852): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  852): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  852): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  852):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  852): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  852): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  852): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  852): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  852): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  852): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  852): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  852): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  852): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  852): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  852): RunningState
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  852): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  852): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  852): identical MTU - not setting
D/Nat464Xlat(  852): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  852): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  852):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:31.919 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  852): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  852): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  852): enableDataServiceNotify 
D/DSQN    (  852): start dsqn bin
,D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
D/DSQN    (  852): dsqn is running restart
,I/DSQN    ( 6363): DSQN samuel.seo ver 141203
,E/DSQN    ( 6363): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6363): created command queue thread
I/DSQN    ( 6363): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6363): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  852): onReceive
D/LocSvc_java(  852): got connectivity action
D/LocSvc_java(  852): broadcast - no network connections
D/LocSvc_java(  852): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  852): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  852): onReceive
D/LocSvc_java(  852): got connectivity action
D/LocSvc_java(  852): broadcast - no network connections
D/LocSvc_java(  852): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  852): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  852): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  852): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  852): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  852): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  852): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  852): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/ActivityManager(  852): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6366 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  852): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  852): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  852): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  852): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/MusicStore( 6366): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6366): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6366): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6366): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6366): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6366): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6366): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6366): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6366): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c2d7c88: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6366): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6366): GMSCore installation verified
I/ConfigStore( 6366): Config Database version: 1
,I/MediaRouter( 6366): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6366): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6366): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6366): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  852): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6408 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6366): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6366): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6366): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6408): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6408): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  852): Process com.android.vending (pid 5616) has died
,I/NotificationManager( 1936): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:02:33.468 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/LGEmail ( 6408): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LGEmail ( 6408): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  852): Process com.google.android.talk (pid 6286) has died
,V/WifiInternetCheck(  852): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  852): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  852): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  852): onReceive
D/LocSvc_java(  852): got connectivity action
D/LocSvc_java(  852): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  852): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  852): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  852): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  852): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6366): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  852): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6071): 
,D/eas_req ( 6408): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  852): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6440 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6408): JNI_OnLoad()
I/HubEmail( 6408): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6408): registerNatives()
I/HubEmail( 6408): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6408): registerNativeMethods()
I/HubEmail( 6408): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6408): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6408): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6440): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6440): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6440): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6440): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6440): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6440): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6440): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6440): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  852): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6467 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6440): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6440): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6440): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6440): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6440): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6440): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6467): onCreate
,W/AppUp4:DB( 6467):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6467):  setFingerPrint start
I/AppUp4:DB( 6467):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6467):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6467):  SDK version = 0
I/AppUp4:DB( 6467):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6467): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6467): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6467): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6467): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6467): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6467): onReceive
I/AppUp4:CustModeStarterReceiver( 6467): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6467): Context : android.app.ReceiverRestrictedContext@2302bdac
D/AppUp4:CustFacade( 6467): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6467): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6467): begin check event
I/AppUp4:CustModeStarterReceiver( 6467): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6467): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6467): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6467): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6467): handleAsyncCustNotification do not startCustService
I/ActivityManager(  852): Killing 6154:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  852): failed to open /acct/uid_10006/pid_6154/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3253): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3253): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3253): networkInfo.isConnected() = false
I/ActivityManager(  852): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6486 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6071): 
,D/PhoneMonitor( 6486): Register our PhoneStateListener
I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6071): 
D/MobileConnectivityChangeReceiver( 6486): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6486): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  852): Killing 6239:com.android.settings/1000 (adj 15): empty #11
I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6071): 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6071): 
I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6071): 
,W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_6239/cgroup.procs: No such file or directory
I/jxcore-log( 6071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6071): 
I/CheckinService( 4210): Checkin interval check for package: unspecified last checkin: 1453042928948 min interval config: 0 actual interval: 25707
,V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/PhoneMonitor( 6486): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6486): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6486): [parse] Load xml
V/TelephonyAutoProfiling( 6486): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6486): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3202): DownloadService onCreate
D/PhoneMonitor( 6486): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/DownloadManager( 3202): in removeSpuriousFiles
I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@46a49d3 on behalf of 3202
I/ActivityManager(  852): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6510 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 324us total 23.130ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.575ms
,I/CheckinService( 4210): Checking schedule, now: 1453042954755 next: 1453042958886
I/CheckinService( 4210): active receiver: disabled
V/DownloadManager( 3202): DownloadService onStartCommand
,I/DownloadManager( 3202): in trimDatabase
V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 25.804ms
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@20684e0e on behalf of 3202
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@105b02f on behalf of 3202
,I/ActivityManager(  852): Killing 6006:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5037): android.os.DeadObjectException
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  852): propertyValue:false
W/System.err( 5037): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5037): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5037): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5037): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5037): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5037): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5037): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5037): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5037): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5037): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5037): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5037): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5037): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5037): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5037): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5037): android.os.DeadObjectException
W/System.err( 5037): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5037): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5037): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5037): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5037): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5037): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5037): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5037): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5037): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5037): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5037): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5037): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5037): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5037): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5037): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  852): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  852): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  852): propertyValue:false
I/DSQN    ( 6363): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6363): restart monitoring
,D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6363): dsqn report finish
D/DSQN    (  852): DSQM DsqnNotification wlan0  1
D/DSQN    (  852): start to monitor internet connection
V/WifiInternetCheck(  852): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  852): failed to open /acct/uid_10089/pid_6006/cgroup.procs: No such file or directory,
,W/ActivityManager(  852): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2796): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:35
I/ActivityManager(  852): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6539 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3202): DownloadService onDestroy
D/UpdateThreadPoolManager( 2796): 2 : This is isUpdating : false
D/WeatherAncestor( 2796): connectivity changed - connection : true
D/Weather_cast( 2796): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2796): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:35
D/WeatherService( 2796): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  852): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6556 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  852): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2796): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2796): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2796): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6539): Quickset Services start...
I/UEI.SmartControl( 6539): Manufacture = LGE
D/UEI.SmartControl( 6539): File observer start...
W/SQLiteConnectionPool( 4210): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
E/UEI.SmartControl( 6539): IR Port is disabled: false
,D/UEI.SmartControl( 6539): Starting file observer...
D/UEI.SmartControl( 6539): Extracting JNI libs...
D/UEI.SmartControl( 6539): --- this system supports 32-bit or 64-bit only
,I/jxcore-log( 6071): Test app app.js loaded
I/jxcore-log( 6071): 
,V/AlarmManager(  852): ELAPSED_WAKEUP set : Alarm{25bf8df2 type 2 when 106343 com.google.android.gms} when 106343
,I/chromium( 6071): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/UEI.SmartControl( 6539): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6539): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6539): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6539): --- Selecting new region: 2
I/UEI.SmartControl( 6539): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6539): Platform has CIR...
D/UEI.SmartControl( 6539): NO CIR support, need to check package...
,I/UEI.SmartControl( 6539): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6539): QS Service created
I/art     (  852): Explicit concurrent mark sweep GC freed 80312(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.994ms total 222.953ms
,E/UEI.SmartControl( 6539): QS start get config
,D/UEI.SmartControl( 6539): Loading JNI Libs...
,D/UEI.SmartControl( 6539):  configuring local db...
,I/Babel_SMS( 6556): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6556): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6556): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6556): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6556): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6556): MmsConfig.loadFromResources
E/Babel_SMS( 6556): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6556): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
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
W/Settings( 6556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6556): startup - clean
I/art     ( 6556): CheckpointMarkThreadRoots callback created = 0xaaf416e0
,I/Babel   ( 6556): deleted: false for 0
,I/art     ( 6556): CheckpointMarkThreadRoots callback created = 0xaaf416c0
,D/UEI.SmartControl( 6539):  ---- Has DB8: true
,D/UEI.SmartControl( 6539): QS start statue = true Error code = 0
D/UEI.SmartControl( 6539): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6539): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6539): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6539): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6539): IrrcClient ++ 
D/irrcClient( 6539): getIrrcService ++ 
,D/irrcClient( 6539): getIrrcService -- 
D/irrcClient( 6539): IrrcClient -- 
W/irrc_jni( 6539): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6539): Services init done
I/UEI.SmartControl( 6539): Device manager: loading config....
D/UEI.SmartControl( 6539): Config is loaded...
,I/ActivityManager(  852): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6592 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6539): QS Service init finished
D/UEI.SmartControl( 6539):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6539): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6539): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6539): QS Service version code: 1073
D/UEI.SmartControl( 6539): Service requested: Control
I/ActivityManager(  852): Killing 6264:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6539): -----IControl: 11
D/UEI.SmartControl( 6539): Caller: com.lge.qremote
D/UEI.SmartControl( 6539): ------------ IControl registerCallback...
I/UEI.SmartControl( 6539): Registering callback...
D/UEI.SmartControl( 6539): -----IControl: 19
D/UEI.SmartControl( 6539): Caller: com.lge.qremote
I/UEI.SmartControl( 6539): Registering Services Ready callback...
W/AudioCapabilities( 6556): Unsupported mime audio/x-lg-flac
I/UEI.SmartControl( 6539): Notify client services are ready...
,W/AudioCapabilities( 6556): Unsupported mime audio/adpcm
W/AudioCapabilities( 6556): Unsupported mime audio/g726
W/AudioCapabilities( 6556): Unsupported mime audio/x-ms-wma
D/UEI.SmartControl( 6539): -----IControl: 8
W/AudioCapabilities( 6556): Unsupported mime audio/wma-voice
D/UEI.SmartControl( 6539): Caller: com.lge.qremote
W/VideoCapabilities( 6556): Unsupported mime video/mjpg
,W/VideoCapabilities( 6556): Unsupported mime video/theora
W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_6264/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6539): Internal service binding...
,W/AudioCapabilities( 6556): Unsupported mime audio/evrc
W/AudioCapabilities( 6556): Unsupported mime audio/qcelp
W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6556): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6556): Unsupported mime audio/qcelp
W/AudioCapabilities( 6556): Unsupported mime audio/evrc
W/VideoCapabilities( 6556): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6556): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6556): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6556): onServiceConnected
,W/Babel   ( 6556): Attempted to change video mute state without an active call.
I/NotificationManager( 6556): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6556): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6556): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6556): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6556): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6556): propertyValue:false
I/ActivityManager(  852): Process com.google.android.music:main (pid 6366) has died
,I/Babel   ( 6556): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6592): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6592): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6592):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6592):   adb logcat -s GAv4
,W/GAv4    ( 6592): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6592): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6592): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6592): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6592): Time to load native libraries: 2 ms (timestamps 7792-7794)
I/LibraryLoader( 6592): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6592): Binding Chromium to main looper Looper (main, tid 1) {26fa4979}
I/LibraryLoader( 6592): Expected native library version number "",actual native library version number ""
I/chromium( 6592): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6592): Initializing chromium process, singleProcess=true
W/art     ( 6592): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6592): ApplicationContext is null in ApplicationStatus
W/chromium( 6592): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6592): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6592): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6592): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6592): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6592): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6592): Remote Branch: 
I/Adreno-EGL( 6592): Local Patches: 
I/Adreno-EGL( 6592): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb3844a40, uid 10079
,W/AudioManagerAndroid( 6592): Requires BLUETOOTH permission
I/NSApplication( 6592): Starting up...
,I/ActivityManager(  852): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6659 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 5037:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  852): failed to open /acct/uid_10106/pid_5037/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  852): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6678 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 6408:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  852): failed to open /acct/uid_10021/pid_6408/cgroup.procs: No such file or directory
,W/ResourcesManager( 6678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  852): Killing 6440:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_6440/cgroup.procs: No such file or directory
,I/ActivityManager(  852): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6702 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6702): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6702): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6702): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6702): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6702): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6702): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6702): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6702): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c2d7c88: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6702): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6702): GMSCore installation verified
I/ConfigStore( 6702): Config Database version: 1
,I/MediaRouter( 6702): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6702): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6702): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  852): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6730 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6702): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6702): Using platform SSLCertificateSocketFactory
,V/AlarmManager(  852): RTC_WAKEUP set : Alarm{84a80c type 0 when 1453042958771 com.google.android.googlequicksearchbox} when 1453042958771
I/ActivityManager(  852): Killing 6467:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10011/pid_6467/cgroup.procs: No such file or directory
,I/NotificationManager( 6702): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 6730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 6730): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6730): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6730): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  852): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6766 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6730): JNI_OnLoad()
I/HubEmail( 6730): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6730): registerNatives()
I/HubEmail( 6730): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6730): registerNativeMethods()
I/HubEmail( 6730): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6730): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  852): Killing 6486:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10038/pid_6486/cgroup.procs: No such file or directory
W/Settings( 6730): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6766): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6766): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  852): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6785 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6766): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6766): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6766): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6766): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6766): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6766): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6766): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6766): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6766): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  852): Killing 6510:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10051/pid_6510/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6785): onCreate
W/AppUp4:DB( 6785):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6785):  setFingerPrint start
,I/AppUp4:DB( 6785):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6785):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6785):  SDK version = 0
I/AppUp4:DB( 6785):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6785): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6785): onReceive
I/AppUp4:CustModeStarterReceiver( 6785): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6785): Context : android.app.ReceiverRestrictedContext@2302bdac
D/AppUp4:CustFacade( 6785): isCustomizationCompleted : false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/AppUp4:CustFacade( 6785): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6785): begin check event
I/AppUp4:CustModeStarterReceiver( 6785): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6785): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6785): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6785): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6785): handleAsyncCustNotification do not startCustService
I/ActivityManager(  852): Killing 6539:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10089/pid_6539/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3253): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3253): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3253): networkInfo.isConnected() = false
I/ActivityManager(  852): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6820 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6820): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6820): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6820): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  852): Killing 6556:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  852): failed to open /acct/uid_10061/pid_6556/cgroup.procs: No such file or directory
,V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3202): DownloadService onCreate
,D/PhoneMonitor( 6820): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/TelephonyAutoProfiling( 6820): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6820): [parse] Load xml
I/DownloadManager( 3202): in removeSpuriousFiles
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/TelephonyAutoProfiling( 6820): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6820): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@6eb9fc5 on behalf of 3202
I/DownloadManager( 3202): in trimDatabase
,V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/ActivityManager(  852): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6849 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 4210): Checkin interval check for package: unspecified last checkin: 1453042928948 min interval config: 0 actual interval: 31005
,V/DownloadManager( 3202): DownloadService onStartCommand
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.520ms
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@1821ca28 on behalf of 3202
D/PhoneMonitor( 6820): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@14eb7341 on behalf of 3202
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 27.021ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.974ms
,I/CheckinService( 4210): Checking schedule, now: 1453042960018 next: 1453042958886
I/CheckinService( 4210): active receiver: enabled
,V/DownloadManager( 3202): DownloadService onDestroy
I/CheckinService( 4210): Preparing to send checkin request
I/EventLogService( 4210): Accumulating logs since 1453042921099
,D/WeatherAncestor( 2796): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:40
D/UpdateThreadPoolManager( 2796): 2 : This is isUpdating : false
D/WeatherAncestor( 2796): connectivity changed - connection : true
D/Weather_cast( 2796): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2796): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:40
D/WeatherService( 2796): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4210): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  852): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6878 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  852): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2796): 2 : Utils getTopActivity com.lge.launcher2 / true
E/ActivityThread( 4210): Failed to find provider info for com.google.android.wearable.settings
D/WeatherService( 2796): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2796): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  852): Explicit concurrent mark sweep GC freed 18493(1031KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.785ms total 160.497ms
,W/ResourcesManager( 6878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  852): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6899 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6899): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6899): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Babel_SMS( 6878): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6878): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6878): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6878): MmsConfig.loadFromDatabase
I/MultiDex( 6899): VM with version 2.1.0 has multidex support
I/MultiDex( 6899): install
I/MultiDex( 6899): VM has multidex support, MultiDex support library is disabled.
,E/Babel_SMS( 6878): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6878): MmsConfig.loadFromResources
E/Babel_SMS( 6878): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6878): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/JNIHelp ( 6899): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SensorManager( 6878): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6878): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6878): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6878): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6878): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6878): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6878): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6878): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6878): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6878): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6878): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
,D/SensorManager( 6878): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6878): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6878): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6878): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6878): found sensor: Motion Accel, handle=46
W/Settings( 6878): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6878): startup - clean
W/ActivityThread( 6899): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6899): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31634c09: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6899): Installed default security provider GmsCore_OpenSSL
I/Babel   ( 6878): deleted: false for 0
I/NotificationManager( 6899): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6899): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6878): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,W/AudioCapabilities( 6878): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6878): Unsupported mime audio/adpcm
W/AudioCapabilities( 6878): Unsupported mime audio/g726
V/MusicLeanback( 6702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/art     ( 6878): CheckpointMarkThreadRoots callback created = 0xb042d890
W/AudioCapabilities( 6878): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6878): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6878): Unsupported mime video/mjpg
I/art     ( 6899): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/VideoCapabilities( 6878): Unsupported mime video/theora
I/art     ( 6899): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/LGDMClient( 6766): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6766): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/Settings( 6730): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6785): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6785): onReceive
I/AppUp4:CustModeStarterReceiver( 6785): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6785): Context : android.app.ReceiverRestrictedContext@2302bdac
D/AppUp4:CustFacade( 6785): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6785): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6785): begin check event
I/AppUp4:CustModeStarterReceiver( 6785): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3253): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3253): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3253): networkInfo.isConnected() = true
,D/PhoneState( 3253): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6820): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6820): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 6766): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6766): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 6766): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3202): DownloadService onCreate
I/LGDMClient( 6766): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3202): in removeSpuriousFiles
,I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/WeatherAncestor( 2796): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:40
D/UpdateThreadPoolManager( 2796): 2 : This is isUpdating : false
D/WeatherAncestor( 2796): connectivity changed - connection : true
D/Weather_cast( 2796): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2796): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:2:40
D/WeatherService( 2796): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  852): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2796): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3202): DownloadService onStartCommand
D/WeatherService( 2796): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2796): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@29bb027d on behalf of 3202
W/ContextImpl( 6766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/AlarmManager(  852): RTC_WAKEUP set : Alarm{92276f6 type 0 when 1453042958886 com.google.android.gms} when 1453042958886
E/LGDMClient( 6766): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6766): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6766): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6766): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6766): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,W/AudioCapabilities( 6878): Unsupported mime audio/evrc
W/AudioCapabilities( 6878): Unsupported mime audio/qcelp
,I/ActivityManager(  852): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6941 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  852): RTC_WAKEUP set : Alarm{1c2fcaf7 type 0 when 1453042960941 com.android.vending} when 1453042960941
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@29105572 on behalf of 3202
I/DownloadManager( 3202): in trimDatabase
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@3e294dc3 on behalf of 3202
W/AudioCapabilities( 6878): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6878): Unsupported mime audio/qcelp
W/AudioCapabilities( 6878): Unsupported mime audio/evrc
,W/VideoCapabilities( 6878): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6878): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
D/NativeLibraryUtils( 6899): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  852): Process com.google.android.apps.magazines (pid 6592) has died
,V/DownloadManager( 3202): DownloadService onDestroy
I/vclib   ( 6878): onServiceConnected
,W/Babel   ( 6878): Attempted to change video mute state without an active call.
I/NotificationManager( 6878): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6878): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6878): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6878): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6878): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6878): propertyValue:false
D/WVCdm   (  284): Instantiating CDM.
,I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
I/ActivityManager(  852): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6962 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6878): connection state changed from UNKNOWN to CONNECTED
,W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=2307801841
,D/Finsky  ( 6941): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6941): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6941): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6941): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6941): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 6941): Skipping gmscore version check
,D/Finsky  ( 6941): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6941): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@26fa4979 on behalf of 6941
,D/Finsky  ( 6941): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6962): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,D/Finsky  ( 6941): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6962): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6962): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6962):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6962):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6962): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 6962): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 6962): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6962): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6962): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 6899): CheckpointMarkThreadRoots callback created = 0xb04cbe80
,I/art     ( 6899): CheckpointMarkThreadRoots callback created = 0xb04cbe70
,I/dex2oat ( 7012): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/Finsky  ( 6941): [860] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6941): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  852): Killing 6659:com.android.chrome/u0a48 (adj 15): empty #11
I/dex2oat ( 7012): dex2oat took 83.987ms (threads: 4)
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6899): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6899): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6899): Remote Branch: 
I/Adreno-EGL( 6899): Local Patches: 
I/Adreno-EGL( 6899): Reconstruct Branch: 
,W/libprocessgroup(  852): failed to open /acct/uid_10048/pid_6659/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6899): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6899): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6899): Remote Branch: 
I/Adreno-EGL( 6899): Local Patches: 
I/Adreno-EGL( 6899): Reconstruct Branch: 
,I/ActivityManager(  852): Process com.google.android.music:main (pid 6702) has died
,I/WebViewFactory( 6962): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6962): Time to load native libraries: 2 ms (timestamps 3363-3365)
I/LibraryLoader( 6962): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6962): Binding Chromium to main looper Looper (main, tid 1) {26fa4979}
,I/LibraryLoader( 6962): Expected native library version number "",actual native library version number ""
I/chromium( 6962): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6962): Initializing chromium process, singleProcess=true
,W/art     ( 6962): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6962): ApplicationContext is null in ApplicationStatus
W/chromium( 6962): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6962): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6962): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6962): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6962): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6962): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6962): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6962): Remote Branch: 
I/Adreno-EGL( 6962): Local Patches: 
I/Adreno-EGL( 6962): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb3844bc0, uid 10079
,W/AudioManagerAndroid( 6962): Requires BLUETOOTH permission
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NSApplication( 6962): Starting up...
,I/ActivityManager(  852): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7050 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6899): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6899): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6899): Remote Branch: 
I/Adreno-EGL( 6899): Local Patches: 
I/Adreno-EGL( 6899): Reconstruct Branch: 
,I/ActivityManager(  852): Killing 6730:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10021/pid_6730/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  852): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7074 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,I/WVCdm   (  284): CdmEngine::OpenSession
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7074): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/BluetoothManagerService(  852): Message: 20
D/BluetoothManagerService(  852): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@70ff748:true
,D/BluetoothAdapterService(138056315)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@24700529
D/BluetoothAdapterService(138056315)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@24700529
D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 114249310167; DSPS: 3835486; Offset : -2811898638
,I/ActivityManager(  852): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7106 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7074): Create singleton instance
,I/AudioManager( 7074): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7106): Quickset Services start...
I/UEI.SmartControl( 7106): Manufacture = LGE
,D/UEI.SmartControl( 7106): File observer start...
E/UEI.SmartControl( 7106): IR Port is disabled: false
,D/UEI.SmartControl( 7106): Starting file observer...
D/UEI.SmartControl( 7106): Extracting JNI libs...
D/WearableService( 1730): callingUid 10006, callindPid: 1730
D/UEI.SmartControl( 7106): --- this system supports 32-bit or 64-bit only
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4210): Restart initialization of location
,E/MDM     ( 1730): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinService( 4210): Checkin interval check for package: unspecified last checkin: 1453042928948 min interval config: 0 actual interval: 34683
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
W/ContextImpl( 3604): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/AudioManager( 7074): getMode name:com.lge.qremote
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/UEI.SmartControl( 7106): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7106): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7106): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/WVCdm   (  284): PrepareKeyRequest: nonce=4274400311
I/UEI.SmartControl( 7106): --- Selecting new region: 2
I/UEI.SmartControl( 7106): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7106): Platform has CIR...
,D/UEI.SmartControl( 7106): NO CIR support, need to check package...
I/UEI.SmartControl( 7106): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7106): QS Service created
E/UEI.SmartControl( 7106): QS start get config
,D/UEI.SmartControl( 7106): Loading JNI Libs...
,D/UEI.SmartControl( 7106):  configuring local db...
D/UEI.SmartControl( 7106):  ---- Has DB8: true
,D/UEI.SmartControl( 7106): QS start statue = true Error code = 0
D/UEI.SmartControl( 7106): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7106): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7106): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7106): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7106): IrrcClient ++ 
D/irrcClient( 7106): getIrrcService ++ 
D/irrcClient( 7106): getIrrcService -- 
D/irrcClient( 7106): IrrcClient -- 
W/irrc_jni( 7106): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7106): Services init done
,I/UEI.SmartControl( 7106): Device manager: loading config....
D/UEI.SmartControl( 7106): QS Service init finished
D/UEI.SmartControl( 7106): QS Service version name: 0.1.73
D/UEI.SmartControl( 7106): Config is loaded...
D/UEI.SmartControl( 7106): QS Service version code: 1073
D/UEI.SmartControl( 7106): Service requested: Control
D/UEI.SmartControl( 7106): Internal service binding...
D/UEI.SmartControl( 7106): -----IControl: 11
,D/UEI.SmartControl( 7106): Caller: com.lge.qremote
D/UEI.SmartControl( 7106): ------------ IControl registerCallback...
I/UEI.SmartControl( 7106): Registering callback...
D/UEI.SmartControl( 7106): -----IControl: 19
D/UEI.SmartControl( 7106): Caller: com.lge.qremote
I/UEI.SmartControl( 7106): Registering Services Ready callback...
I/UEI.SmartControl( 7106): Notify client services are ready...
D/UEI.SmartControl( 7106): -----IControl: 8
D/UEI.SmartControl( 7106): Caller: com.lge.qremote
I/AudioManager( 7074): getMode name:com.lge.qremote
,I/ActivityManager(  852): Killing 6849:com.lge.drmservice/u0a51 (adj 15): empty #11
D/UEI.SmartControl( 7106):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7106): Notify AllClients services are ready: 0
,I/ActivityManager(  852): Killing 6785:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  852): failed to open /acct/uid_10051/pid_6849/cgroup.procs: No such file or directory
,W/libprocessgroup(  852): failed to open /acct/uid_10011/pid_6785/cgroup.procs: No such file or directory
,I/AudioManager( 7074): getMode name:com.lge.qremote
I/AudioManager( 7074): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): L3 Terminate.
I/MusicWidget( 2756): mDelayedStopHandler : unbind
,I/MusicBrowser( 2814): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2814): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2814): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2814): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2814): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2814): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2814): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  852):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@115acae5com.lge.music.MediaPlaybackService$6@1f9859ba
D/MusicBrowser( 2814): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1fb40898
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2814): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2814): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2814): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2814): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2814): reset
V/MediaPlayer[Native]( 2814): setListener
V/MediaPlayer[Native]( 2814): disconnect
V/MediaPlayer[Native]( 2814): destructor
V/AudioFlinger(  284): releasing 19 from 2814 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
,V/MediaPlayer[Native]( 2814): disconnect
D/MusicBrowser( 2814): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2814): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2814): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2814): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2814): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2814): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
,I/SmartShareClient( 2814): [SmartShareManagerClient] unregisterListener: 1058082923
W/SmartShareClient( 2814): [SmartShareManagerClient] unregisterListener invalid listener: 1058082923
I/SmartShareClient( 2814): [SmartShareManagerClient] terminate service: 2814/MediaPlaybackService/645495806
E/HomeCloudIF( 2814): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2814): [SmartShareManagerClient] unbindService context:android.app.Application@2b06c7c8
V/CloudHub( 2814): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2814): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2814): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2814): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2814): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  852): Killing 6766:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/CloudHub( 2814): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,W/libprocessgroup(  852): failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 4210): Classify the device as Phone.
,D/libc-netbsd( 4210): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4210): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4210): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4210): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 4210): propertyValue:false
D/libc-netbsd( 4210): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4210): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4210): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4210): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4210): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4210): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4210): Sending checkin request (9905 bytes)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 4210): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4210): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xb042d2f0
,I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xb042d2c0
I/art     (  852): Explicit concurrent mark sweep GC freed 24451(1089KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.662ms total 163.250ms
,I/art     ( 5596): Explicit concurrent mark sweep GC freed 1867(69KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 716us total 31.080ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4210): Classify the device as Phone.
,I/CheckinTask( 4210): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4210): Checking schedule, now: 1453042967880 next: 1453570216875
I/CheckinService( 4210): active receiver: disabled
,I/CheckinService( 4210): Checking schedule, now: 1453042967911 next: 1453570216875
I/CheckinService( 4210): active receiver: disabled
,D/CheckinService( 4210): Recording last checkin time for package unspecified as 1453042967920
V/SetupWizard( 6820): Connected to Gservices successfully
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  852): Killing 6941:com.android.vending/u0a36 (adj 15): empty #11
I/ActivityManager(  852): Killing 6962:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  852): failed to open /acct/uid_10036/pid_6941/cgroup.procs: No such file or directory
,W/libprocessgroup(  852): failed to open /acct/uid_10079/pid_6962/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7106): Internal timer expired: 1
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  852): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/ActivityManager(  852): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7188 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/art     ( 1786): Background sticky concurrent mark sweep GC freed 90110(5MB) AllocSpace objects, 0(0B) LOS objects, 36% free, 9MB/14MB, paused 1.269ms total 100.542ms
,I/NotificationManager( 6878): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 6878): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6878): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  852): Handling package changes for user 0
,V/JNIHelp ( 6878): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7188): onCreate
,W/AppUp4:DB( 7188):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7188):  setFingerPrint start
,I/AppUp4:DB( 7188):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7188):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7188):  SDK version = 0
I/AppUp4:DB( 7188):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7188): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7188): onReceive
,I/AppUp4:CustModeStarterReceiver( 7188): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7188): Context : android.app.ReceiverRestrictedContext@2dc5bbb9
D/AppUp4:CustFacade( 7188): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7188): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7188): begin check event
I/AppUp4:CustModeStarterReceiver( 7188): Event For Nothing, skip.
W/System  ( 6878): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6878): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  852): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7216 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
W/ResourcesManager( 7216): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationService(  852): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  852): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  852): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  852): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  852): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  852): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@224ac0b9
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager(  852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppConfig( 7216): Total System Memory = 906309632
,I/GalleryUtils( 7216): Application Heap = 96 MB
I/AppConfig( 7216): App Tier : NOT_DEF
D/SystemHelper( 7216): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourceType(  852): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  852): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7235 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  852): Killing 7050:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10048/pid_7050/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7235): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7235): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7235): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7235): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7235): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  852): applying state to connected service
,I/SystemConfig( 7235): BUILD Country: EU
,I/SystemConfig( 7235): BUILD Operator: OPEN
I/SystemConfig( 7235): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7235): existFile = false
I/SystemConfig( 7235): canReadFile = false
I/SystemConfig( 7235): systemFeature RCS result false
D/SystemConfig( 7235): refreshRcsSupport() :false
I/ActivityManager(  852): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7258 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 6678:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.405ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 27.192ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 23.145ms
,W/libprocessgroup(  852): failed to open /acct/uid_10086/pid_6678/cgroup.procs: No such file or directory
I/LockScreenSettings( 7258): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7258): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7258): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7258): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7258): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7258): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  852): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7278 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  852): Killing 2814:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  284): 2814 died, releasing its sessions
V/AudioFlinger(  284):  pid 1749 @ 0
V/AudioFlinger(  284):  pid 3253 @ 1
V/AudioFlinger(  284):  pid 3253 @ 2
,W/libprocessgroup(  852): failed to open /acct/uid_10028/pid_2814/cgroup.procs: No such file or directory
,W/ResourcesManager( 7278): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  852): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7303 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  852): Killing 6820:com.google.android.setupwizard/u0a38 (adj 15): empty #11,
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,W/libprocessgroup(  852): failed to open /acct/uid_10038/pid_6820/cgroup.procs: No such file or directory
,D/Finsky  ( 7303): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7303): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7303): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7303): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7303): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@278a56be on behalf of 7303
,D/Finsky  ( 7303): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7303): Skipping gmscore version check
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
D/Finsky  ( 7303): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7303): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 4210): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4210): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7303): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4210): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4210): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4210): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  852): Killing 6899:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  852): failed to open /acct/uid_10006/pid_6899/cgroup.procs: No such file or directory
,I/ActivityManager(  852): Killing 7106:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7074): android.os.DeadObjectException
,W/System.err( 7074): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7074): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7074): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7074): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7074): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7074): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7074): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7074): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7074): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7074): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7074): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7074): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7074): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7074): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7074): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7074): android.os.DeadObjectException
W/System.err( 7074): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7074): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7074): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7074): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7074): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7074): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7074): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7074): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7074): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7074): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7074): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7074): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7074): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7074): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7074): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  852): failed to open /acct/uid_10089/pid_7106/cgroup.procs: No such file or directory
,W/ActivityManager(  852): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  852): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7362 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7362): Quickset Services start...
,I/UEI.SmartControl( 7362): Manufacture = LGE
,D/UEI.SmartControl( 7362): File observer start...
E/UEI.SmartControl( 7362): IR Port is disabled: false
D/UEI.SmartControl( 7362): Starting file observer...
D/UEI.SmartControl( 7362): Extracting JNI libs...
D/UEI.SmartControl( 7362): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7362): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7362): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7362): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7362): --- Selecting new region: 2
,I/UEI.SmartControl( 7362): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7362): Platform has CIR...
D/UEI.SmartControl( 7362): NO CIR support, need to check package...
I/UEI.SmartControl( 7362): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7362): QS Service created
E/UEI.SmartControl( 7362): QS start get config
,D/UEI.SmartControl( 7362): Loading JNI Libs...
,D/UEI.SmartControl( 7362):  configuring local db...
D/UEI.SmartControl( 7362):  ---- Has DB8: true
,D/UEI.SmartControl( 7362): QS start statue = true Error code = 0
D/UEI.SmartControl( 7362): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7362): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7362): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7362): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7362): IrrcClient ++ 
D/irrcClient( 7362): getIrrcService ++ 
D/irrcClient( 7362): getIrrcService -- 
,D/irrcClient( 7362): IrrcClient -- 
W/irrc_jni( 7362): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7362): Services init done
I/UEI.SmartControl( 7362): Device manager: loading config....
,D/UEI.SmartControl( 7362): Config is loaded...
D/UEI.SmartControl( 7362): QS Service init finished
D/UEI.SmartControl( 7362): QS Service version name: 0.1.73
D/UEI.SmartControl( 7362): QS Service version code: 1073
D/UEI.SmartControl( 7362): Service requested: Control
D/UEI.SmartControl( 7362): -----IControl: 11
I/ActivityManager(  852): Killing 7074:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7362): Caller: com.lge.qremote
,D/UEI.SmartControl( 7362): ------------ IControl registerCallback...
I/UEI.SmartControl( 7362): Registering callback...
W/libprocessgroup(  852): failed to open /acct/uid_10106/pid_7074/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7362): Internal service binding...
,D/UEI.SmartControl( 7362):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7362): Notify AllClients services are ready: 0
D/charger_monitor(  487): init target 500000
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/WifiController(  852): battery changed pluggedType: 2
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/charger_monitor(  487): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerManagerServiceEx(  852): acquireWakeLockInternal: lock=422241063, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,D/WeatherService( 2796): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:3:0
,D/WeatherService( 2796): 2 : TimeTick Intent And Screen On
D/WeatherService( 2796): 2 : SDK version : 21
W/ActivityManager(  852): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2796): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2796): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2796): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2796): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2796): 2 : This is isUpdating : false
D/WeatherService( 2796): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2796): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2796): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2796): 2 : Fixed theme : optimus
D/WeatherReflect( 2796): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
,D/lim     ( 2796): 2 : time = 16:03
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/WeatherReflect( 2796): Model Name : LG-D722
D/WeatherTheme( 2796): 2 : Different view - status_min_formatted : 02 != 03
D/WeatherTheme( 2796): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2796): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2796): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2796): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2796): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2796): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2796): forecast size is 0
D/Theme   ( 2796): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2796): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2796): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2796): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2796): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
,D/Theme   ( 2796): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2796): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2796): url is : null
D/Theme   ( 2796): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2796): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2796): 2 : update view, appWidgetId: 2
D/WeatherService( 2796): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:3:0
D/PowerManagerServiceEx(  852): releaseWakeLockInternal: lock=422241063 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 7362): Internal timer expired: 1
,D/UEI.SmartControl( 7362): Service.onUnbind: IControl
D/UEI.SmartControl( 7362): Service.onDestroy
W/System.err( 7362): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@83a927b
,W/System.err( 7362): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7362): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7362): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7362): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7362): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7362): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7362): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7362): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7362): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7362): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7362): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7362): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@83a927b
D/UEI.SmartControl( 7362): Shutdown IRRCPlayer... 
W/irrc_jni( 7362): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7362): ~IrrcClient ++ 
D/irrcClient( 7362): ~IrrcClient -- 
W/irrc_jni( 7362): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7362): Blaster closed
D/UEI.SmartControl( 7362): Blaster closed
D/UEI.SmartControl( 7362): Shut down QS...
,D/UEI.SmartControl( 7362): Stopped file observer...
I/UEI.SmartControl( 7362): QS lib stop result = true
D/UEI.SmartControl( 7362): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 134249994586; DSPS: 4490869; Offset : -2811914483
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  852): ELAPSED_WAKEUP set : Alarm{1fa2c9d4 type 2 when 141053 com.google.android.gms} when 141053
,D/ChimeraCfgMgr( 4210): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4210): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 4210): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 4210): Failed to execute periodic sync, missing client context - aborting
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  852): Explicit concurrent mark sweep GC freed 39010(1899KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.333ms total 166.694ms
,I/VacuumService( 1730): Vacuum at: now=1453042990829 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  852): ALS enabled for SRE
D/PowerManagerServiceEx(  852): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28963 ms ago)
,D/qdlights(  852): set_light_backlight: 252
,D/qdlights(  852): set_light_backlight: 249
D/qdlights(  852): set_light_backlight: 246
,D/qdlights(  852): set_light_backlight: 242
,D/qdlights(  852): set_light_backlight: 239
,D/qdlights(  852): set_light_backlight: 236
,D/qdlights(  852): set_light_backlight: 232
,D/qdlights(  852): set_light_backlight: 229
,D/qdlights(  852): set_light_backlight: 226
,D/qdlights(  852): set_light_backlight: 222
,D/qdlights(  852): set_light_backlight: 219
,D/qdlights(  852): set_light_backlight: 216
,D/qdlights(  852): set_light_backlight: 212
,D/qdlights(  852): set_light_backlight: 209
,D/qdlights(  852): set_light_backlight: 206
,D/qdlights(  852): set_light_backlight: 202
,D/qdlights(  852): set_light_backlight: 199
,D/qdlights(  852): set_light_backlight: 196
,D/qdlights(  852): set_light_backlight: 192
,D/qdlights(  852): set_light_backlight: 189
,D/qdlights(  852): set_light_backlight: 186
,D/qdlights(  852): set_light_backlight: 182
,D/qdlights(  852): set_light_backlight: 179
,D/qdlights(  852): set_light_backlight: 176
,D/qdlights(  852): set_light_backlight: 172
,D/qdlights(  852): set_light_backlight: 169
,D/qdlights(  852): set_light_backlight: 166
,D/qdlights(  852): set_light_backlight: 162
,D/qdlights(  852): set_light_backlight: 159
,D/qdlights(  852): set_light_backlight: 156
,D/qdlights(  852): set_light_backlight: 152
,D/qdlights(  852): set_light_backlight: 149
,D/qdlights(  852): set_light_backlight: 146
,D/qdlights(  852): set_light_backlight: 142
,D/qdlights(  852): set_light_backlight: 139
,D/qdlights(  852): set_light_backlight: 136
,D/qdlights(  852): set_light_backlight: 132
,D/qdlights(  852): set_light_backlight: 129
,D/qdlights(  852): set_light_backlight: 126
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  852): set_light_backlight: 122
,D/qdlights(  852): set_light_backlight: 119
,D/qdlights(  852): set_light_backlight: 116
,D/qdlights(  852): set_light_backlight: 112
,D/qdlights(  852): set_light_backlight: 109
,D/qdlights(  852): set_light_backlight: 106
,D/qdlights(  852): set_light_backlight: 102
,D/qdlights(  852): set_light_backlight: 99
,D/qdlights(  852): set_light_backlight: 96
,D/qdlights(  852): set_light_backlight: 92
,D/qdlights(  852): set_light_backlight: 89
,D/qdlights(  852): set_light_backlight: 86
,D/qdlights(  852): set_light_backlight: 82
,D/qdlights(  852): set_light_backlight: 79
,D/qdlights(  852): set_light_backlight: 76
,D/qdlights(  852): set_light_backlight: 72
,D/qdlights(  852): set_light_backlight: 69
,D/qdlights(  852): set_light_backlight: 66
,D/qdlights(  852): set_light_backlight: 62
,D/qdlights(  852): set_light_backlight: 59
,D/qdlights(  852): set_light_backlight: 56
,D/qdlights(  852): set_light_backlight: 52
,D/qdlights(  852): set_light_backlight: 49
,D/qdlights(  852): set_light_backlight: 46
,D/qdlights(  852): set_light_backlight: 42
,D/qdlights(  852): set_light_backlight: 39
,D/qdlights(  852): set_light_backlight: 36
,D/qdlights(  852): set_light_backlight: 32
,D/qdlights(  852): set_light_backlight: 29
,D/qdlights(  852): set_light_backlight: 26
,D/qdlights(  852): set_light_backlight: 22
,D/qdlights(  852): set_light_backlight: 19
,D/qdlights(  852): set_light_backlight: 16
,D/qdlights(  852): set_light_backlight: 12
,D/qdlights(  852): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 154250950517; DSPS: 5146260; Offset : -2811904779
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  852): ALS enabled for SRE
D/PowerManagerServiceEx(  852): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35959 ms ago)
,I/PowerManagerService(  852): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  852): ALS enabled for SRE
D/PowerManagerServiceEx(  852): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35969 ms ago)
W/ContextImpl(  852): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  852): Sleeping (uid 1000)...
D/LPWGController(  852): [updateScreenState] screen on = false
D/LPWGController(  852): disable proximity sensor
D/LPWGController(  852): enable proximity sensor
,I/SensorManager(  852): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@144451ca] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  852): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  852): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  852): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  852): activate: handle is 48, enable
V/sensors_hal_Ctx(  852): activate sensors is 1400000000000
D/sensors_hal_Thresh(  852): enable: handle=48
I/sensors_hal_SAM(  852): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  852): waitForResponse: timeout=1000
V/sensors_hal_SAM(  852): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  852): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  852): enable: Received response: 0
D/PowerManagerServiceEx(  852): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36007 ms ago)
I/Adreno-EGL(  852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  852): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  852): Build Date: 03/02/15 Mon
I/Adreno-EGL(  852): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  852): Remote Branch: 
I/Adreno-EGL(  852): Local Patches: 
I/Adreno-EGL(  852): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (978 us)
,I/Sensors (  426): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  852): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  852): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  852): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  852): processInd: handle 48, count=1
V/sensors_hal_Thresh(  852): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  852): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  852): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  852): poll: count: 256
I/sensors_hal_Ctx(  852): poll: released wakelock sensor_ind
D/sensors_hal_Util(  852): waitForResponse: timeout=0
D/LPWGController(  852): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  852): current mode = 1  value = 1 1
I/LPWGController(  852): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/ActivityManager(  852): Process com.google.android.talk (pid 6878) has died
,I/LPWGController(  852): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  852): set_light_backlight: 0
,I/SensorManager(  852): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  852): activate: handle is 46, disable
V/sensors_hal_Ctx(  852): activate sensors is 1000000000000
D/sensors_hal_LP2(  852): enable: handle=46
D/sensors_hal_LP2(  852): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  852): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  852): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  852): Display changed displayId=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/DSDPConnection( 1749): Display #0 changed.
,V/sensors_hal_SAM(  852): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  852): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  852): Excessive delay in setPowerMode(): 197ms
I/QCOM PowerHAL(  852): Got set_interactive hint
D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1373): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  852): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 852
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  284): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,I/WifiServerServiceExt(  852): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  852): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1804): lockStatus = 0
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
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
,D/NfcService( 1786): Discovery configuration equal, not updating.
D/SplitWindow(  852): check instance of lgWin Window{170453b1 u0 SearchPanel}
,D/InputDispatcher(  852): Window went away: Window{16e17af8 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,D/Ulp_jni (  852): JNI:system_update. Event-0
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 44372(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 1.245ms total 100.510ms
,W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): ACTION_SCREEN_ON
,D/WeatherService( 2796): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:3:26
D/WeatherService( 2796): 2 : ACTION screen on
D/WeatherService( 2796): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2796): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2796): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:3:26
D/AppCleanupService( 4047): android.intent.action.SCREEN_ON
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 852
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
D/WifiController(  852): CMD_SCREEN_OFF 
D/WifiController(  852): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  852): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
,D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  852): ACTION_SCREEN_OFF
D/WeatherService( 2796): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:3:26
,D/WeatherService( 2796): 2 : ACTION screen off
D/WeatherService( 2796): 2 : TimeTick Receiver Unregister
D/WeatherService( 2796): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:3:26
D/AppCleanupService( 4047): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4047): AppUsageStatsSaveTask
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
,I/Sensors (  426): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  852): ELAPSED_WAKEUP set : Alarm{a3dc096 type 2 when 161837 com.android.systemui} when 161837
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 174251634103; DSPS: 5801642; Offset : -2811892657
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  852): battery changed pluggedType: 2
V/AlarmManager(  852): ELAPSED_WAKEUP set : Alarm{36fce417 type 2 when 187557 com.google.android.gms} when 187557
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 5639 seconds from now (1453043036964)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  852): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
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
,I/System.out( 1730): propertyValue:false
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  852): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  852): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  852): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  852): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  852): ELAPSED_WAKEUP set : Alarm{2a890107 type 2 when 189957 android} when 189957
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 194252366908; DSPS: 6457026; Offset : -2811892144
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 214253042890; DSPS: 7112409; Offset : -2811917572
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 234253812205; DSPS: 7767794; Offset : -2811912185
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  852): battery changed pluggedType: 2
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  852): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  852): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 254254565583; DSPS: 8423179; Offset : -2811920810
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 274255283232; DSPS: 9078562; Offset : -2811905377
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 294256031661; DSPS: 9733947; Offset : -2811920306
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  852): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  852): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 314256796602; DSPS: 10389331; Offset : -2811887785
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  852): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  852): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  852): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  852): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  852): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  852): tsOffsetIs: Apps: 334257467167; DSPS: 11044714; Offset : -2811918942
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6071): --= Surplus to requirements =--
I/jxcore-log( 6071): 
I/jxcore-log( 6071): ****TEST TOOK:  ms ****
I/jxcore-log( 6071): 
I/jxcore-log( 6071): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6071): 
,D/AndroidRuntime( 7560): 
D/AndroidRuntime( 7560): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7560): CheckJNI is OFF
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/AndroidRuntime( 7560): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  852): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  852): Killing 6071:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  852): WIN DEATH: Window{301c80ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  852): Focus left window: Window{301c80ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  852): Window went away: Window{301c80ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  852): Skipping PackageSetting{1f09cd19 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  852):   Force finishing activity ActivityRecord{1281a0ee u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  852): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
W/ActivityManager(  852): Spurious death for ProcessRecord{2d0fc234 6071:com.test.thalitest/u0a316}, curProc for 6071: null
,I/ActivityManager(  852): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  852):   Force finishing activity ActivityRecord{1281a0ee u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  852): Duplicate finish request for ActivityRecord{1281a0ee u0 com.test.thalitest/.MainActivity t222 f}
I/art     ( 1936): Explicit concurrent mark sweep GC freed 9352(546KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.652ms total 70.201ms
,I/art     ( 4210): Explicit concurrent mark sweep GC freed 4787(276KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 804us total 89.321ms
,I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  852): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
,W/System.err( 3604): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/ActivityManager(  852): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7591 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3604): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3604): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3604): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3604): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3604): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3604): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3604): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3604): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3604): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3604): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3604): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
,D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
,D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/art     (  852): Explicit concurrent mark sweep GC freed 39134(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.378ms total 237.184ms
,I/art     (  852): WaitForGcToComplete blocked for 215.886ms for cause Explicit
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
I/SystemUI[Framework](  852): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  852): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  852): setLGSystemUiVisibility(0x0)
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/StatusBarManagerServiceEx(  852): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher(  852): Focus entered window: Window{13bb6665 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/SystemUI[Framework](  852): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25645387,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  852): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  852): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  852): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  852): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  852): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  852): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25645387,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  852): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,D/KeyguardModel( 1373): handleShortcutListChanged...
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): handleShortcutListChanged...
W/ResourcesManager( 7591): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7591): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7591): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  852): Handling package changes for user 0
,I/art     (  852): Explicit concurrent mark sweep GC freed 6282(373KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 10.002ms total 301.197ms
,W/InputMethodManagerService(  852): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  852): Got RemoteException sending setActive(false) notification to pid 6071 uid 10316
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/Timeline(  852): Timeline: Activity_windows_visible id: ActivityRecord{379297cd u0 com.lge.launcher2/.Launcher t221} time:344794
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/LGEmail ( 7591): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1611): Unable to connect to the editor to retrieve text... will retry later
D/AndroidRuntime( 7560): Shutting down VM
,D/LGEmail ( 7591): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/NotificationService(  852): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  852): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
D/JobSchedulerService(  852): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/TaskPersister(  852): removeObsoleteFile: deleting file=222_task.xml
,D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,W/ResourcesManager(  852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PackageChangeReceiver( 7591): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/AppUp4:PreloadHelper( 7188): added Exclude : com.test.thalitest
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/ActivityManager(  852): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7624 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourceType(  852): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
