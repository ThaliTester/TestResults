#### Test 54970261d953416_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/Icing   ( 4167): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4167): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
--------- beginning of system
I/ActivityManager(  855): Killing 6053:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10023/pid_6053/cgroup.procs: No such file or directory
I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
D/AndroidRuntime( 6210): 
D/AndroidRuntime( 6210): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6210): CheckJNI is OFF
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{3f346d16 type 0 when 1452280451113 com.android.vending} when 1452280451113
D/Finsky  ( 5781): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/AndroidRuntime( 6210): Calling main entry com.android.commands.am.Am
I/GAV2    ( 5878): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager(  855): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ActivityManager(  855): setTaskToReturnTo : TaskRecord{28acc533 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  855): setTaskToReturnTo : TaskRecord{28acc533 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  855): AppWindowTokenEx init.. 
D/ContextHelper(  855): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  855): Focus left window: Window{235db7c8 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6210): Shutting down VM
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  855): check instance of lgWin Window{307cae08 u0 Starting com.test.thalitest}
I/NotificationManager(  855): android: cancelAsUser(2) by android
I/ActivityManager(  855): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6239 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  855): Starting window displayed
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/HotwordDetector( 1933): Closing mic
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@259015d0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/MicrophoneInputStream( 1933): mic_close com.google.android.apps.gsa.speech.audio.u@2addefc8
,I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 15000000
D/BarTransitions( 1372): draw background and invalidate : color = e0d0d0d
V/AudioRecord( 1933): stop()
D/AudioRecord( 1933): AudioRecord->stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioFlinger(  286): Record stopped OK
V/AudioPolicyManager(  286): stopInput() input 16
V/AudioPolicyService(  286): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  286): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  286): ThreadBase::setParameters() routing=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb4064000
D/audio_hw_primary(  286): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/libc-netbsd( 5781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 5781): propertyValue:false
D/libc-netbsd( 5781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/audio_hw_primary(  286): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  286): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  286): disable_audio_route: exit
E/audio_hw_primary(  286): disable_snd_device: enter 144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  286): stop_input_stream: exit: status(0)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  286): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  286): setParameters(): io 16, keyvalue hotword_active=0, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb4064000
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
D/ContextHelper( 6239): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): releasing 15 from 1933 for -1
V/AudioFlinger(  286): RecordThread::stop
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioPolicyManager(  286): releaseInput() 16
V/AudioFlinger(  286): purging stale effects
V/AudioPolicyManager(  286): closeInput(16)
V/AudioFlinger(  286): closeInput() 16
V/AudioSystem(  286): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2652): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1984): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3156): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  855): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  286): ThreadBase::exit
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioSystem( 1933): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  286): RecordThread 0xb4064000 exiting
D/audio_hw_primary(  286): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  286): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
I/HotwordRecognitionRnr( 1933): Stopping hotword detection.
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  286): releaseInput() exit
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioFlinger(  286): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioFlinger(  286): removeClient_l() pid 1933, calling pid 286
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1933): Hotword detection finished
I/WebViewFactory( 6239): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 94544916894; DSPS: 3196160; Offset : -3004423729
I/LibraryLoader( 6239): Time to load native libraries: 2 ms (timestamps 4588-4590)
I/LibraryLoader( 6239): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6239): Binding Chromium to main looper Looper (main, tid 1) {2520130}
I/LibraryLoader( 6239): Expected native library version number "",actual native library version number ""
I/chromium( 6239): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6239): Initializing chromium process, singleProcess=true
W/art     ( 6239): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6239): ApplicationContext is null in ApplicationStatus
W/chromium( 6239): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6239): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6239): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6239): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6239): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6239): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6239): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6239): Remote Branch: 
I/Adreno-EGL( 6239): Local Patches: 
I/Adreno-EGL( 6239): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb4027560, uid 10316
D/BluetoothManagerService(  855): Message: 20
D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@144fec77:true
D/BluetoothAdapterService(328073308)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a0a7092
D/libc-netbsd( 5781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/art     ( 6239): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6239): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6239): CordovaWebView is running on device made by: LGE
,W/art     ( 6239): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6239): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6239): Activity.onPostResume() called 
,D/OpenGLRenderer( 6239): Render dirty regions requested: true
I/OpenGLRenderer( 6239): Initialized EGL, version 1.4
D/OpenGLRenderer( 6239): Enabling debug mode 0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  855): android: cancelAsUser(2) by android
,D/Atlas   ( 6239): Validating map...
D/SplitWindow(  855): check instance of lgWin Window{aee2d03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6239): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  855): Focus entered window: Window{aee2d03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/qtaguid ( 5781): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5781): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5781): untagSocket(41) failed with errno -22
D/Finsky  ( 5781): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/InputMethodManagerService(  855): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  855): Displayed com.test.thalitest/.MainActivity: +1s162ms
I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{2e17b0f0 u0 com.test.thalitest/.MainActivity t220} time:95317
,I/Timeline( 6239): Timeline: Activity_idle id: android.os.BinderProxy@13a279bf time:95334
,I/ActivityManager(  855): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6297 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 24.133ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 27.485ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 25.530ms
,I/NotificationManager(  855): android: cancelAsUser(2) by android
D/AlertService( 5992): Beginning updateAlertNotification
W/BindingManager( 6239): Cannot call determinedVisibility() - never saw a connection for the pid: 6239
,D/AlertService( 5992): No fired or scheduled alerts
,I/NotificationManager( 5992): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 5992): com.android.calendar: cancel(7) by com.android.calendar
,I/NotificationManager( 5992): com.android.calendar: cancel(8) by com.android.calendar
W/ResourcesManager( 6297): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6297): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 5992): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 5992): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5992): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5992): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/MultiDex( 6297): VM with version 2.1.0 has multidex support
,I/MultiDex( 6297): install
I/MultiDex( 6297): VM has multidex support, MultiDex support library is disabled.
D/AlarmScheduler( 5992): No events found starting within 1 week.
,I/qtaguid ( 5781): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5781): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5781): untagSocket(41) failed with errno -22
V/JNIHelp ( 6297): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/JsMessageQueue( 6239): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityThread( 6297): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6297): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24759ff2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6297): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6297): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6297): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
E/MDM     ( 1730): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 6297): Reading stored module config
,D/ChimeraCfgMgr( 6297): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/LocationInitializer( 4167): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
I/art     ( 5781): CheckpointMarkThreadRoots callback created = 0xb002d9a0
,D/CAR.SERVICE( 6297): Connecting to CarCallService...
,D/NativeLibraryUtils( 6297): Install completed successfully. count=14 extracted=0
,I/art     ( 5781): CheckpointMarkThreadRoots callback created = 0xb002d970
I/art     ( 6297): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6297): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6297): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6297): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6297): Creating a new PhoneAdapter instance
W/ActivityManager(  855): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6297): setListener: com.google.android.gms.car.dn@341b4f69
W/ActivityManager(  855): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6297): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6297): Starting CarCallService with initial phone null
,D/jxcore_app_log( 6239): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622854144
D/JX-Cordova( 6239): jxcore cordova android initializing
I/NotificationManager( 6297): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  855): Process com.google.android.talk (pid 5551) has died
,D/CAR.SERVICE( 6297): Package validated; name: com.android.vending
I/NotificationManager( 5781): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5781): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/art     ( 6239): CheckpointMarkThreadRoots callback created = 0xb00fccc0
,I/art     ( 6239): CheckpointMarkThreadRoots callback created = 0xb00fcc90
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  855): android: cancelAsUser(2) by android
,I/qtaguid ( 5781): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5781): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5781): untagSocket(41) failed with errno -22
,I/art     (  855): Explicit concurrent mark sweep GC freed 25096(1545KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.044ms total 193.302ms
,W/ResourcesManager( 5781): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5781): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5781): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5781): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  855): RTC_WAKEUP set : Alarm{3466410e type 0 when 1452280454645 com.android.vending} when 1452280454645
D/Finsky  ( 5781): [730] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1730): client connected with version: 8296000
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  855): android: cancelAsUser(2) by android
,D/Finsky  ( 5781): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5781): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 5781): propertyValue:false
I/ActivityManager(  855): Killing 5992:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10013/pid_5992/cgroup.procs: No such file or directory
,W/jxcore-log( 6239): Initializing JXcore engine
,W/jxcore-log( 6239): JXcore engine is ready
W/jxcore-log( 6239): Starting JXcore engine
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:15.591 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,W/.test.thalitest( 6239): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8516]" dev="sockfs" ino=8516 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6239): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6239): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6650]" dev="sockfs" ino=6650 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6239): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6239): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6239): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30412]" dev="sockfs" ino=30412 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6239): Platform android
W/jxcore-log( 6239): 
W/jxcore-log( 6239): Process ARCH arm
W/jxcore-log( 6239): 
,I/ActivityManager(  855): Process com.google.android.gm (pid 5878) has died
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  855): RTC_WAKEUP set : Alarm{33bd872 type 0 when 1452280456604 com.google.android.googlequicksearchbox} when 1452280456604
,I/jxcore-log( 6239): JXcore Cordova bridge is ready!
I/jxcore-log( 6239): 
W/jxcore-log( 6239): JXcore engine is started
,I/chromium( 6239): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 6239): Skipped 195 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6239): Toggling radios to true
I/jxcore-log( 6239): 
,D/BluetoothAdapter( 6239): enable(): BT is already enabled..!
D/WifiServiceImplEx(  855): setWifiEnabled: true pid=6239, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  855): setWifiEnabled: true pid=6239, uid=10316
,D/WifiServiceImplEx(  855): disconnect pid=6239, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  855): reconnect pid=6239, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6239): Radios toggled
I/jxcore-log( 6239): 
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2805): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2805): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  855): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1799): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  855): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): Read error: ssl=0xb0059e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb0059e00: I/O error during system call, Broken pipe
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  855): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  855): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:17.216 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=-12ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Forcing reevaluation
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/ActivityManager(  855): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6390 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
D/WifiHS20(  855): hidePasspointNotification off =false
E/WifiStateMachine(  855): Start Disconnecting Watchdog 1
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2805): wlan0: CTRL-EVENT-SCAN-STARTED 
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:17.317 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  855): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  855): disableDataServiceNotify
D/DSQN    (  855): stop dsqn bin
D/ConnectivityService(  855): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Disconnected - quitting
D/Nat464Xlat(  855): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/ActivityManager(  855): Process com.android.contacts (pid 6078) has died
D/DhcpStateMachine(  855): StoppedState
D/DhcpStateMachine(  855): StoppedState{ when=-81ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker(  855): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  855): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20(  855): hidePasspointNotification off =false
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:17.404 DNS addrs= 0.0.0.0, 0.0.0.0, 
,D/ConnectivityService(  855): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  855): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1835): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy(  855): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkManagementService(  855): Removing idletimer
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/NetworkPolicy(  855): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  855): MasterInitialState.processMessage what=3
D/Tethering(  855): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1835): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = -1
D/WifiNetworkAgent(  855): NetworkAgent: NetworkAgent channel lost
,W/Settings(  855): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  855): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiHS20(  855): hidePasspointNotification off =false
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:17.432 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    (  855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:17.437 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateDISCONNECTED
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,W/ResourcesManager( 6390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateSCANNING
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
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
I/IndexDatabaseHelper( 6390): Using schema version: 115
,I/IndexDatabaseHelper( 6390): Index is fine
I/ActivityManager(  855): Process com.lge.lockscreensettings (pid 6097) has died
,V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
I/ActivityManager(  855): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6422 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6422): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6422): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6422): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
I/PCSuite ( 6422): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6422): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6422): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6444 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{369a14c3 type 2 when 100911 com.google.android.gms} when 100911
,I/ActivityManager(  855): Process com.google.android.apps.plus (pid 6114) has died
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2805): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/LocSvc_java(  855): onReceive
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.509 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2805): wlan0: Associated with c0:ff:d4:d3:aa:48
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.521 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateASSOCIATED
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
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.551 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.554 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2805): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2805): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateGROUP_HANDSHAKE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/WifiServiceExtension(  855): setVHTCapabilityType  : false
I/WifiServerServiceExt(  855): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  855): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  855): setSecurityType  : 2
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.621 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.624 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/Babel_SMS( 6444): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6444): MmsConfig.loadMmsSettings
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  855): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  855): Got NetworkAgent Messenger
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  855): NetworkAgent connected
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Babel_SMS( 6444): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6444): MmsConfig.loadFromDatabase
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/Babel_SMS( 6444): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6444): MmsConfig.loadFromResources
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine(  855): Start Dhcp Watchdog 2
D/DhcpStateMachine(  855): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  855): WaitBeforeStartState
E/Babel_SMS( 6444): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6444): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/art     ( 6444): CheckpointMarkThreadRoots callback created = 0xb002d860
,E/WifiStateMachine(  855): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  855): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  855): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  855): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3fb70420 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3fb70420 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  855): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/SensorManager( 6444): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6444): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6444): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6444): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6444): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6444): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6444): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6444): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6444): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6444): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6444): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6444): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6444): found sensor: LGE Tilt Detector Sensor, handle=55
D/DhcpStateMachine(  855): DHCP Start wake lock is acquired.
D/SensorManager( 6444): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6444): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6444): found sensor: Motion Accel, handle=46
I/art     ( 6444): CheckpointMarkThreadRoots callback created = 0xb002d850
,D/CommandListener(  279): Setting iface cfg
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/CommandListener(  279): Trying to bring up wlan0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/LgDhcpStateMachineHelper(  855): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateCOMPLETED
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  855): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  855): ignoring duplicate network state non-change
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.793 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  855): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.802 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  855): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.815 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  855): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine(  855): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 3
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  855): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  855): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:18.828 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  855): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  279): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 3
D/ConnectivityService(  855): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  855): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  855): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  855): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  855): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  855):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  855):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  855): currentScore = 0, newScore = 20
D/ConnectivityService(  855):    accepting network in place of null
D/ConnectivityService(  855): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  855): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  855): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () ,- 101] isDefaultNetwork=true
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Connected
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  855): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  855): [e] list.add(nai) empty : false size: 1
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/QCNEJ   ( 1835): |CORE| No family connected
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  855): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] wait 500ms before dns check
D/ConnectivityService(  855): validation of new default Network = false
D/ConnectivityService(  855): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  855): enableDataServiceNotify 
D/DSQN    (  855): start dsqn bin
V/NetworkPolicy(  855): [LG_RESTRICTED] checkMobilePolicy_type()
D/CAR.SERVICE( 6297): mConnectedToCar = false, abort
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
E/ActivityThread( 6297): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@27e36b31 that was originally bound here
E/ActivityThread( 6297): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@27e36b31 that was originally bound here
E/ActivityThread( 6297): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6297): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6297): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6297): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6297): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6297): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6297): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6297): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6297): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6297): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6297): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6297): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6297): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6297): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6297): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6297): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6297): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6297): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6297): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/A,ctivityThread( 6297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/ConnectivityService(  855): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
E/ActivityThread( 6297): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1e045df0 that was originally bound here
E/ActivityThread( 6297): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1e045df0 that was originally bound here
E/ActivityThread( 6297): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6297): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6297): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6297): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6297): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6297): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6297): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6297): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6297): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6297): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6297): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6297): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6297): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6297): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6297): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6297): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6297): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6297): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  855): Unbind failed: could not find connection for android.os.BinderProxy@3589e521
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings( 6444): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  855): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
I/Babel_Crash( 6444): startup - clean
,I/DSQN    ( 6479): DSQN samuel.seo ver 141203
E/DSQN    ( 6479): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6479): created command queue thread
I/DSQN    ( 6479): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6479): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/Babel   ( 6444): deleted: false for 0
,D/DhcpStateMachine(  855): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  855): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  855): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6484): version 5.5.6 starting
E/dhcpcd  ( 6484): get_duid: Read-only file system
,V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
I/PCSuite ( 6422): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6422): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6422): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6444): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6444): Unsupported mime audio/adpcm
W/AudioCapabilities( 6444): Unsupported mime audio/g726
W/AudioCapabilities( 6444): Unsupported mime audio/x-ms-wma
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6444): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6444): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
W/VideoCapabilities( 6444): Unsupported mime video/theora
I/PCSuite ( 6422): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6422): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6422): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
I/dhcpcd  ( 6484): wlan0: rebinding lease of 192.168.1.134
,V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6390): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
W/AudioCapabilities( 6444): Unsupported mime audio/evrc
W/AudioCapabilities( 6444): Unsupported mime audio/qcelp
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
W/VideoCapabilities( 6444): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
I/DSQN    ( 6479): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6479): restart monitoring
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6479): dsqn report finish
D/DSQN    (  855): DSQM DsqnNotification wlan0  1
D/DSQN    (  855): start to monitor internet connection
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
W/AudioCapabilities( 6444): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6444): Unsupported mime audio/qcelp
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
W/AudioCapabilities( 6444): Unsupported mime audio/evrc
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
,W/VideoCapabilities( 6444): Unsupported mime video/mp4v-esdp
V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
I/PCSuite ( 6422): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6422): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6390): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/VideoCapabilities( 6444): Unsupported profile 4 for video/mp4v-es
,D/WiFiOffLoadBroadcast( 6390): MCCMNC not supported: null
W/VideoCapabilities( 6444): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6444): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 6422): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6422): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6444): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6444): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6444): onServiceConnected
W/Babel   ( 6444): Attempted to change video mute state without an active call.
,I/NotificationManager( 6444): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] DNSResolver start dns
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 19:14:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452280459455], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452280459434]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Validated
D/ConnectivityService(  855): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  855):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  855): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  855): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiDataContinuityService(  855): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
I/WifiServerServiceExt(  855): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  855): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  855): identical MTU - not setting
D/Nat464Xlat(  855): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  855): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
D/ConnectivityService(  855): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  855): enableDataServiceNotify 
D/DSQN    (  855): start dsqn bin
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/dhcpcd  ( 6484): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:20.053 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  855): dsqn is running restart
,I/DSQN    ( 6505): DSQN samuel.seo ver 141203
,I/dhcpcd  ( 6484): wlan0: leased 192.168.1.134 for 86400 seconds
E/DSQN    ( 6505): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6505): created command queue thread
I/DSQN    ( 6505): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6505): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  855): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  855): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  855): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  855): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  855): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  855): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  855): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  855): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  855): RunningState
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
,D/LocSvc_java(  855): broadcast - no network connections
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  855): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  855): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6536 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
D/LocSvc_java(  855): broadcast - no network connections
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  855): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  855): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  855): Process com.android.vending (pid 5781) has died
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  277): 
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/MusicStore( 6536): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6536): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6536): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6536): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6536): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6536): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6536): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6536): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6536): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398af595: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6536): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6536): GMSCore installation verified
,I/ConfigStore( 6536): Config Database version: 1
,I/MediaRouter( 6536): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6536): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6536): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6536): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6571 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6536): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6536): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6571): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6571): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6571): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 6536): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6571): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6571): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:21.697 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 6571): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/NotificationManager( 1933): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  855): Single check msg out of sync, ignoring.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6604 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  855): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  855): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/NetworkMonitor( 6536): type=WIFI subType= reason=null isConnected=true
,I/HubEmail( 6571): JNI_OnLoad()
I/HubEmail( 6571): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6571): registerNatives()
I/HubEmail( 6571): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6571): registerNativeMethods()
I/HubEmail( 6571): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6571): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  855): Killing 6169:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/Settings( 6571): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  855): failed to open /acct/uid_10014/pid_6169/cgroup.procs: No such file or directory
,D/LGDMClient( 6604): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6604): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6604): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6604): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6604): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6604): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6629 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6604): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6604): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6604): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6604): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6604): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  855): Killing 6297:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10006/pid_6297/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6629): onCreate
,W/AppUp4:DB( 6629):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6629):  setFingerPrint start
I/AppUp4:DB( 6629):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6629):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6629):  SDK version = 0
I/AppUp4:DB( 6629):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6629): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6629): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6629): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6629): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6629): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6629): onReceive
I/AppUp4:CustModeStarterReceiver( 6629): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6629): Context : android.app.ReceiverRestrictedContext@146751a9
D/AppUp4:CustFacade( 6629): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6629): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6629): begin check event
I/AppUp4:CustModeStarterReceiver( 6629): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6629): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6629): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6629): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6629): handleAsyncCustNotification do not startCustService
I/ActivityManager(  855): Killing 6390:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6390/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3156): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3156): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3156): networkInfo.isConnected() = false
I/ActivityManager(  855): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6652 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6652): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6652): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6652): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  855): Killing 5615:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5031): android.os.DeadObjectException
,W/System.err( 5031): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5031): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5031): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 5031): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5031): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5031): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5031): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5031): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5031): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5031): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5031): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5031): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5031): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5031): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5031): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5031): android.os.DeadObjectException
W/System.err( 5031): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5031): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5031): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5031): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5031): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5031): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5031): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5031): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5031): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5031): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5031): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5031): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5031): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5031): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5031): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
W/libprocessgroup(  855): failed to open /acct/uid_10089/pid_5615/cgroup.procs: No such file or directory
W/ActivityManager(  855): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/DSQN    ( 6505): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6505): restart monitoring
,I/DSQN    ( 6505): dsqn report finish
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  855): DSQM DsqnNotification wlan0  1
D/DSQN    (  855): start to monitor internet connection
I/CheckinService( 4167): Checkin interval check for package: unspecified last checkin: 1452280436680 min interval config: 0 actual interval: 26431
V/WifiInternetCheck(  855): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  855): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6680 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
,D/PhoneMonitor( 6652): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6652): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6652): [parse] Load xml
I/DownloadManager( 3230): in removeSpuriousFiles
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@24759ff2 on behalf of 3230
I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/TelephonyAutoProfiling( 6652): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@3fd0643 on behalf of 3230
,V/TelephonyAutoProfiling( 6652): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6709 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3230): DownloadService onStartCommand
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4167): Checking schedule, now: 1452280463306 next: 1452280466623
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@1839c93e on behalf of 3230
D/PhoneMonitor( 6652): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 4167): active receiver: disabled
,D/UEI.SmartControl( 6680): Quickset Services start...
V/DownloadManager( 3230): DownloadService onDestroy
I/UEI.SmartControl( 6680): Manufacture = LGE
,D/UEI.SmartControl( 6680): File observer start...
E/UEI.SmartControl( 6680): IR Port is disabled: false
D/UEI.SmartControl( 6680): Starting file observer...
D/UEI.SmartControl( 6680): Extracting JNI libs...
D/UEI.SmartControl( 6680): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  855): Killing 6422:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6680): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6680): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6680): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6680): --- Selecting new region: 2
,I/UEI.SmartControl( 6680): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6680): Platform has CIR...
D/UEI.SmartControl( 6680): NO CIR support, need to check package...
I/UEI.SmartControl( 6680): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6680): QS Service created
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6422/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2594): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:14:23
D/UpdateThreadPoolManager( 2594): 2 : This is isUpdating : false
D/WeatherAncestor( 2594): connectivity changed - connection : true
D/Weather_cast( 2594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2594): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:14:23
D/WeatherService( 2594): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2594): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2594): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2594): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
E/UEI.SmartControl( 6680): QS start get config
,I/ActivityManager(  855): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6729 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 23.779ms
,D/UEI.SmartControl( 6680): Loading JNI Libs...
D/UEI.SmartControl( 6680):  configuring local db...
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.588ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.673ms
,D/libc-netbsd( 6444): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6444): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6444): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6444): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6444): propertyValue:false
,I/Babel   ( 6444): connection state changed from UNKNOWN to CONNECTED
,D/UEI.SmartControl( 6680):  ---- Has DB8: true
,D/UEI.SmartControl( 6680): QS start statue = true Error code = 0
D/UEI.SmartControl( 6680): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6680): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6680): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6680): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6680): IrrcClient ++ 
D/irrcClient( 6680): getIrrcService ++ 
,D/irrcClient( 6680): getIrrcService -- 
D/irrcClient( 6680): IrrcClient -- 
W/irrc_jni( 6680): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6680): Services init done
I/UEI.SmartControl( 6680): Device manager: loading config....
D/UEI.SmartControl( 6680): QS Service init finished
D/UEI.SmartControl( 6680): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6680): QS Service version code: 1073
D/UEI.SmartControl( 6680): Service requested: Control
D/UEI.SmartControl( 6680): Config is loaded...
D/UEI.SmartControl( 6680): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6680):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6680): Notify AllClients services are ready: 0
I/ActivityManager(  855): Killing 5031:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6680): -----IControl: 11
D/UEI.SmartControl( 6680): Caller: com.lge.qremote
D/UEI.SmartControl( 6680): ------------ IControl registerCallback...
I/UEI.SmartControl( 6680): Registering callback...
,W/libprocessgroup(  855): failed to open /acct/uid_10106/pid_5031/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6680): Internal service binding...
,I/art     (  855): Explicit concurrent mark sweep GC freed 80072(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.029ms total 179.398ms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6729): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6729): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6729):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6729):   adb logcat -s GAv4
,W/GAv4    ( 6729): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6729): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6729): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6729): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6729): Time to load native libraries: 3 ms (timestamps 7372-7375)
,I/LibraryLoader( 6729): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6729): Binding Chromium to main looper Looper (main, tid 1) {29d1e9a2}
I/LibraryLoader( 6729): Expected native library version number "",actual native library version number ""
I/chromium( 6729): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6729): Initializing chromium process, singleProcess=true
,W/art     ( 6729): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6729): ApplicationContext is null in ApplicationStatus
W/chromium( 6729): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6729): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6729): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6729): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6729): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6729): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6729): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6729): Remote Branch: 
I/Adreno-EGL( 6729): Local Patches: 
I/Adreno-EGL( 6729): Reconstruct Branch: 
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:24.722 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AudioPolicyService(  286): registerClient() client 0xb385cb20, uid 10079
W/AudioManagerAndroid( 6729): Requires BLUETOOTH permission
,I/NSApplication( 6729): Starting up...
I/ActivityManager(  855): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6793 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 6536:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10081/pid_6536/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6814 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 6571:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10021/pid_6571/cgroup.procs: No such file or directory
,W/ResourcesManager( 6814): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  855): Killing 6604:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6604/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6847 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6847): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6847): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6847): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6847): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6847): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398af595: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6847): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6847): GMSCore installation verified
,I/ConfigStore( 6847): Config Database version: 1
,I/MediaRouter( 6847): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6847): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6847): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6847): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6875 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6847): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6847): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  855): Killing 6629:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6875): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6875): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_6629/cgroup.procs: No such file or directory
,I/NotificationManager( 6847): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6875): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6875): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6875): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6898 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6875): JNI_OnLoad()
I/HubEmail( 6875): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6875): registerNatives()
I/HubEmail( 6875): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6875): registerNativeMethods()
I/HubEmail( 6875): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6875): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  855): Killing 6652:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/Settings( 6875): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{3ef679d type 0 when 1452280466623 com.google.android.gms} when 1452280466623
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{bc07e3 type 0 when 1452280467305 com.google.android.googlequicksearchbox} when 1452280467305
W/libprocessgroup(  855): failed to open /acct/uid_10038/pid_6652/cgroup.procs: No such file or directory
D/LGDMClient( 6898): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6898): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6898): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6898): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6898): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6926 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6898): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6898): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6898): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6898): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6898): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  855): Killing 6680:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/libprocessgroup(  855): failed to kill 1 processes for processgroup 6680
,I/AppUp4:AppBoxCP( 6926): onCreate
,W/AppUp4:DB( 6926):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6926):  setFingerPrint start
I/AppUp4:DB( 6926):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6926):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6926):  SDK version = 0
I/AppUp4:DB( 6926):  beforefinger == newfinger no write in DB
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 20:14:27.834 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AppUp4:AppBoxApplication( 6926): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6926): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6926): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NetworkStateForAutoUpdateMonitor( 6926): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6926): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6926): onReceive
,I/AppUp4:CustModeStarterReceiver( 6926): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6926): Context : android.app.ReceiverRestrictedContext@146751a9
D/AppUp4:CustFacade( 6926): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6926): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6926): begin check event
I/AppUp4:CustModeStarterReceiver( 6926): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6926): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6926): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6926): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6926): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  855): Killing 6709:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_6709/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3156): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3156): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3156): networkInfo.isConnected() = false
I/ActivityManager(  855): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6952 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6952): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6952): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6952): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  855): Killing 6444:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6952): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6952): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6952): [parse] Load xml
V/TelephonyAutoProfiling( 6952): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6952): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6952): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_6444/cgroup.procs: No such file or directory
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
I/DownloadManager( 3230): in removeSpuriousFiles
,I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@1bdaecec on behalf of 3230
I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@3aeef8b5 on behalf of 3230
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6975 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3230): DownloadService onStartCommand
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@ffebd8 on behalf of 3230
I/CheckinService( 4167): Checkin interval check for package: unspecified last checkin: 1452280436680 min interval config: 0 actual interval: 31655
I/CheckinService( 4167): Checking schedule, now: 1452280468347 next: 1452280466623
I/CheckinService( 4167): active receiver: enabled
,I/CheckinService( 4167): Preparing to send checkin request
I/EventLogService( 4167): Accumulating logs since 1452280427915
,D/WeatherAncestor( 2594): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:14:28
D/UpdateThreadPoolManager( 2594): 2 : This is isUpdating : false
D/WeatherAncestor( 2594): connectivity changed - connection : true
D/Weather_cast( 2594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2594): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:14:28
D/WeatherService( 2594): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4167): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6999 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
E/ActivityThread( 4167): Failed to find provider info for com.google.android.wearable.settings
D/Weather.Utils( 2594): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3230): DownloadService onDestroy
,D/WeatherService( 2594): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2594): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6999): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  855): Explicit concurrent mark sweep GC freed 16496(885KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.107ms total 147.136ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  855): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7027 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  855): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7034 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{3afa0941 type 0 when 1452280468966 com.android.vending} when 1452280468966
,I/art     (  310): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 288us total 23.177ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.624ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.809ms
,W/ResourcesManager( 7027): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7027): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 6999): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6999): MmsConfig.loadMmsSettings
I/Babel_SMS( 6999): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 6999): MmsConfig.loadFromDatabase
I/art     ( 6999): CheckpointMarkThreadRoots callback created = 0xb002d470
,E/Babel_SMS( 6999): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6999): MmsConfig.loadFromResources
E/Babel_SMS( 6999): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6999): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6999): CheckpointMarkThreadRoots callback created = 0xb002d450
,D/Finsky  ( 7034): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/SensorManager( 6999): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6999): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6999): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6999): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6999): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6999): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6999): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6999): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6999): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6999): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6999): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6999): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6999): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6999): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6999): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6999): found sensor: Motion Accel, handle=46
I/MultiDex( 7027): VM with version 2.1.0 has multidex support
I/MultiDex( 7027): install
I/MultiDex( 7027): VM has multidex support, MultiDex support library is disabled.
W/Settings( 6999): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6999): startup - clean
V/JNIHelp ( 7027): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 6999): deleted: false for 0
,W/ActivityThread( 7027): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7027): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24759ff2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7027): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  855): Process com.google.android.apps.magazines (pid 6729) has died
,I/NotificationManager( 7027): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7027): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/Finsky  ( 7034): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ActivityManager(  855): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7093 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Settings( 7034): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     ( 7027): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7027): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/Settings( 7034): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7034): com.android.vending: cancel(-1050172287) by com.android.vending
,W/AudioCapabilities( 6999): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6999): Unsupported mime audio/adpcm
W/AudioCapabilities( 6999): Unsupported mime audio/g726
W/AudioCapabilities( 6999): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6999): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6999): Unsupported mime video/mjpg
,W/VideoCapabilities( 6999): Unsupported mime video/theora
D/Finsky  ( 7034): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7034): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7034): Skipping gmscore version check
,W/AudioCapabilities( 6999): Unsupported mime audio/evrc
W/AudioCapabilities( 6999): Unsupported mime audio/qcelp
W/VideoCapabilities( 6999): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6999): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6999): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6999): Unsupported mime audio/evrc
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@1f63c216 on behalf of 7034
W/VideoCapabilities( 6999): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6999): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6999): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6999): Unrecognized profile 2130706433 for video/avc
D/Finsky  ( 7034): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/VideoCapabilities( 6999): Unrecognized profile 2130706433 for video/avc
D/WVCdm   (  286): Instantiating CDM.
,I/WVCdm   (  286): CdmEngine::OpenSession
I/WVCdm   (  286): Level3 Library Dec 11 2014 16:13:16
D/NativeLibraryUtils( 7027): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 6999): Unrecognized profile 2130706433 for video/avc
W/WVCdm   (  286): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  286): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  286): L1 library not specified. Falling Back to L3
I/vclib   ( 6999): onServiceConnected
,W/Babel   ( 6999): Attempted to change video mute state without an active call.
,D/Finsky  ( 7034): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NotificationManager( 6999): com.google.android.talk: cancel(10436) by com.google.android.talk
I/WVCdm   (  286): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  286): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  286): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  286): CdmEngine::GenerateKeyRequest
D/WVCdm   (  286): PrepareKeyRequest: nonce=1943209747
D/libc-netbsd( 6999): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6999): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6999): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6999): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6999): propertyValue:false
I/jxcore-log( 6239): Test app app.js loaded
I/jxcore-log( 6239): 
,I/Babel   ( 6999): connection state changed from UNKNOWN to CONNECTED
I/chromium( 6239): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,D/Finsky  ( 7034): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
D/Finsky  ( 7034): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  855): Killing 6793:com.android.chrome/u0a48 (adj 15): empty #11
,I/GAv4    ( 7093): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7093):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7093):   adb logcat -s GAv4
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
I/WVCdm   (  286): CdmEngine::OpenSession
,W/libprocessgroup(  855): failed to open /acct/uid_10048/pid_6793/cgroup.procs: No such file or directory
,W/GAv4    ( 7093): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7093): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7093): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WebViewFactory( 7093): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7093): Time to load native libraries: 2 ms (timestamps 3947-3949)
,I/LibraryLoader( 7093): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7093): Binding Chromium to main looper Looper (main, tid 1) {29d1e9a2}
I/LibraryLoader( 7093): Expected native library version number "",actual native library version number ""
I/chromium( 7093): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7093): Initializing chromium process, singleProcess=true
,W/art     ( 7093): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7093): ApplicationContext is null in ApplicationStatus
W/chromium( 7093): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7093): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7093): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7093): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7093): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7093): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7093): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7093): Remote Branch: 
I/Adreno-EGL( 7093): Local Patches: 
I/Adreno-EGL( 7093): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb551c800, uid 10079
,W/AudioManagerAndroid( 7093): Requires BLUETOOTH permission
I/NSApplication( 7093): Starting up...
I/ActivityManager(  855): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7163 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 6814:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10086/pid_6814/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7182 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 6847:com.google.android.music:main/u0a81 (adj 15): empty #11
D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 114546012200; DSPS: 3851556; Offset : -3004425362
,W/libprocessgroup(  855): failed to open /acct/uid_10081/pid_6847/cgroup.procs: No such file or directory
,W/ResourcesManager( 7182): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Killing 6875:com.lge.email/u0a21 (adj 15): empty #11
,I/art     ( 7182): CheckpointMarkThreadRoots callback created = 0xb002d460
I/art     ( 7182): CheckpointMarkThreadRoots callback created = 0xb002d440
,W/libprocessgroup(  855): failed to open /acct/uid_10021/pid_6875/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7207 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  286): CdmEngine::CloseSession
,I/MusicStore( 7207): Database version: 120
,I/WVCdm   (  286): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  286): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  286): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  286): CdmEngine::GenerateKeyRequest
D/WVCdm   (  286): PrepareKeyRequest: nonce=2647350237
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7207): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7207): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7207): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7207): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7207): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7207): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7207): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7207): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398af595: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7207): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7207): GMSCore installation verified
I/ConfigStore( 7207): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 6139): Explicit concurrent mark sweep GC freed 2033(88KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 401us total 53.015ms
,I/MediaRouter( 7207): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7207): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7207): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7207): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7240 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7207): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7207): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  855): Killing 6898:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7240): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7240): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7240): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6898/cgroup.procs: No such file or directory
,I/NotificationManager( 7207): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7240): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7240): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7240): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/MusicWidget( 2519): mDelayedStopHandler : unbind
,I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7263 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7240): JNI_OnLoad()
I/HubEmail( 7240): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7240): registerNatives()
I/HubEmail( 7240): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7240): registerNativeMethods()
I/HubEmail( 7240): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7240): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  855): Killing 6926:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/MusicBrowser( 2652): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2652): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2652): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2652): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2652): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_6926/cgroup.procs: No such file or directory
W/Settings( 7240): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/MusicBrowser( 2652): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2652): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  855):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2e5b03decom.lge.music.MediaPlaybackService$6@13a279bf
D/MusicBrowser( 2652): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3aba5f65
,I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2652): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2652): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2652): reset
D/LGDMClient( 7263): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7263): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7263): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7263): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/MediaPlayer[Native]( 2652): setListener
V/MediaPlayer[Native]( 2652): disconnect
V/MediaPlayer[Native]( 2652): destructor
V/AudioFlinger(  286): releasing 18 from 2652 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
V/MediaPlayer[Native]( 2652): disconnect
D/MusicBrowser( 2652): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/SmartShareClient( 2652): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2652): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2652): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2652): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2652): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2652): [SmartShareManagerClient] unregisterListener: 100677772
W/SmartShareClient( 2652): [SmartShareManagerClient] unregisterListener invalid listener: 100677772
I/SmartShareClient( 2652): [SmartShareManagerClient] terminate service: 2652/MediaPlaybackService/697904755
E/HomeCloudIF( 2652): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2652): [SmartShareManagerClient] unbindService context:android.app.Application@279aebd5
D/LGDMClient( 7263): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7263): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7263): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7289 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/LGDMClient( 7263): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/CloudHub( 2652): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2652): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2652): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2652): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2652): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
W/ContextImpl( 7263): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ActivityManager(  855): Killing 6952:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/CloudHub( 2652): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
E/LGDMClient( 7263): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7263): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7263): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7263): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7263): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,W/libprocessgroup(  855): failed to open /acct/uid_10038/pid_6952/cgroup.procs: No such file or directory
I/ActivityManager(  855): Killing 6975:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7289): onCreate
W/AppUp4:DB( 7289):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7289):  setFingerPrint start
I/AppUp4:DB( 7289):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7289):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7289):  SDK version = 0
I/AppUp4:DB( 7289):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_6975/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7289): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7289): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7289): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7289): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7289): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7289): onReceive
I/AppUp4:CustModeStarterReceiver( 7289): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7289): Context : android.app.ReceiverRestrictedContext@146751a9
D/AppUp4:CustFacade( 7289): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7289): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7289): begin check event
I/AppUp4:CustModeStarterReceiver( 7289): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7289): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7289): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7289): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7289): handleAsyncCustNotification do not startCustService
I/ActivityManager(  855): Killing 6999:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_6999/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3156): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3156): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3156): networkInfo.isConnected() = true
D/PhoneState( 3156): setPdpRejectCasuse : false
I/ActivityManager(  855): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7314 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/WVCdm   (  286): CdmEngine::CloseSession
I/WVCdm   (  286): L3 Terminate.
,I/art     (  855): Explicit concurrent mark sweep GC freed 23938(1109KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.952ms total 152.104ms
,D/PhoneMonitor( 7314): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7314): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7314): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  855): Killing 7093:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7314): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7314): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7314): [parse] Load xml
V/TelephonyAutoProfiling( 7314): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7314): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7314): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  855): failed to open /acct/uid_10079/pid_7093/cgroup.procs: No such file or directory
,V/DownloadManager( 3230): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3230): DownloadService onCreate
I/DownloadManager( 3230): in removeSpuriousFiles
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@35a08797 on behalf of 3230
I/NotificationManager( 3230): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3230): in trimDatabase
V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@1fd2896d on behalf of 3230
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7337 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3230): DownloadService onStartCommand
V/DownloadManager( 3230): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4167): Checkin interval check for package: unspecified last checkin: 1452280436680 min interval config: 0 actual interval: 38401
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@18dc0633 on behalf of 3230
,V/DownloadManager( 3230): DownloadService onDestroy
,I/ActivityManager(  855): Killing 7034:com.android.vending/u0a36 (adj 15): empty #11
,I/dex2oat ( 7353): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  855): failed to open /acct/uid_10036/pid_7034/cgroup.procs: No such file or directory
D/WeatherAncestor( 2594): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:14:35
D/UpdateThreadPoolManager( 2594): 2 : This is isUpdating : false
D/WeatherAncestor( 2594): connectivity changed - connection : true
D/Weather_cast( 2594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2594): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:14:35
D/WeatherService( 2594): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7357 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2594): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2594): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2594): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7357): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/dex2oat ( 7353): dex2oat took 120.946ms (threads: 4)
,I/Adreno-EGL( 7027): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7027): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7027): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7027): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7027): Remote Branch: 
I/Adreno-EGL( 7027): Local Patches: 
I/Adreno-EGL( 7027): Reconstruct Branch: 
,I/Adreno-EGL( 7027): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7027): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7027): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7027): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7027): Remote Branch: 
I/Adreno-EGL( 7027): Local Patches: 
I/Adreno-EGL( 7027): Reconstruct Branch: 
,I/Babel_SMS( 7357): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7357): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7357): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7357): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7357): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7357): MmsConfig.loadFromResources
E/Babel_SMS( 7357): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7357): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7357): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7357): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7357): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7357): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7357): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7357): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7357): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7357): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7357): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7357): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7357): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7357): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7357): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7357): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7357): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7357): found sensor: Motion Accel, handle=46
,W/Settings( 7357): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7357): startup - clean
I/Babel   ( 7357): deleted: false for 0
,I/Adreno-EGL( 7027): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7027): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7027): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7027): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7027): Remote Branch: 
I/Adreno-EGL( 7027): Local Patches: 
I/Adreno-EGL( 7027): Reconstruct Branch: 
I/art     ( 7357): CheckpointMarkThreadRoots callback created = 0xb002d570
I/art     ( 7357): CheckpointMarkThreadRoots callback created = 0xb002d550
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  855): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7394 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.924ms
,W/AudioCapabilities( 7357): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7357): Unsupported mime audio/adpcm
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 332us total 22.433ms
,W/AudioCapabilities( 7357): Unsupported mime audio/g726
W/AudioCapabilities( 7357): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7357): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7357): Unsupported mime video/mjpg
W/VideoCapabilities( 7357): Unsupported mime video/theora
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 409us total 24.536ms
W/AudioCapabilities( 7357): Unsupported mime audio/evrc
,W/AudioCapabilities( 7357): Unsupported mime audio/qcelp
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7357): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7357): Unsupported mime audio/qcelp
W/AudioCapabilities( 7357): Unsupported mime audio/evrc
,W/VideoCapabilities( 7357): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7357): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7357): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7394): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7394):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7394):   adb logcat -s GAv4
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7394): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7357): onServiceConnected
W/Babel   ( 7357): Attempted to change video mute state without an active call.
D/libc-netbsd( 7357): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7357): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7357): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7357): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7357): propertyValue:false
,I/NotificationManager( 7357): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7394): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7394): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7394): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/CheckinRequestBuilder( 4167): Classify the device as Phone.
W/GAv4    ( 7394): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
W/GAv4    ( 7394): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7394): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7357): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  855): Killing 7163:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10048/pid_7163/cgroup.procs: No such file or directory
,D/libc-netbsd( 4167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 4167): propertyValue:false
,D/libc-netbsd( 4167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4167): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4167): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/WebViewFactory( 7394): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/CheckinTask( 4167): Sending checkin request (9854 bytes)
I/LibraryLoader( 7394): Time to load native libraries: 2 ms (timestamps 9033-9035)
I/LibraryLoader( 7394): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7394): Binding Chromium to main looper Looper (main, tid 1) {29d1e9a2}
I/LibraryLoader( 7394): Expected native library version number "",actual native library version number ""
I/chromium( 7394): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7394): Initializing chromium process, singleProcess=true
,W/art     ( 7394): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7394): ApplicationContext is null in ApplicationStatus
W/chromium( 7394): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7394): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7394): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7394): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7394): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7394): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7394): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7394): Remote Branch: 
I/Adreno-EGL( 7394): Local Patches: 
I/Adreno-EGL( 7394): Reconstruct Branch: 
V/AudioPolicyService(  286): registerClient() client 0xb4027800, uid 10079
,W/AudioManagerAndroid( 7394): Requires BLUETOOTH permission
I/NSApplication( 7394): Starting up...
,I/ActivityManager(  855): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7461 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 7182:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10086/pid_7182/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7483 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 7207:com.google.android.music:main/u0a81 (adj 15): empty #11
I/CheckinRequestBuilder( 4167): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  855): failed to open /acct/uid_10081/pid_7207/cgroup.procs: No such file or directory
,E/ActivityThread( 4167): Failed to find provider info for com.google.android.wearable.settings
W/ResourcesManager( 7483): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4167): Classify the device as Phone.
,I/CheckinTask( 4167): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4167): Checking schedule, now: 1452280476972 next: 1452807725965
I/CheckinService( 4167): active receiver: disabled
,I/CheckinService( 4167): Checking schedule, now: 1452280477014 next: 1452807725965
I/CheckinService( 4167): active receiver: disabled
,D/CheckinService( 4167): Recording last checkin time for package unspecified as 1452280477025
,I/ActivityManager(  855): Killing 2652:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  286): 2652 died, releasing its sessions
V/AudioFlinger(  286):  pid 1748 @ 0
V/AudioFlinger(  286):  pid 3156 @ 1
V/AudioFlinger(  286):  pid 3156 @ 2
,I/ActivityManager(  855): Killing 7240:com.lge.email/u0a21 (adj 15): empty #12
,W/libprocessgroup(  855): failed to open /acct/uid_10028/pid_2652/cgroup.procs: No such file or directory
,W/libprocessgroup(  855): failed to open /acct/uid_10021/pid_7240/cgroup.procs: No such file or directory
I/ActivityManager(  855): Killing 7263:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_7263/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 4167): Checkin interval check for package: unspecified last checkin: 1452280477025 min interval config: 0 actual interval: 306
,I/CheckinService( 4167): Checking schedule, now: 1452280477340 next: 1452807725965
I/CheckinService( 4167): active receiver: disabled
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4167): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/ContextImpl( 3601): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=7531 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
,I/MusicStore( 7531): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7531): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7531): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/JNIHelp ( 7531): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 7531): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7531): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398af595: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7531): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7531): GMSCore installation verified
,I/ConfigStore( 7531): Config Database version: 1
,I/MediaRouter( 7531): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7531): type=WIFI subType= reason=null isConnected=true
,I/art     (  855): Explicit concurrent mark sweep GC freed 15808(798KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.870ms total 136.245ms
,I/art     ( 7531): CheckpointMarkThreadRoots callback created = 0xaaf1c710
,I/MusicLeanback( 7531): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7531): Stop autocaching.
,I/NetworkMonitor( 7531): type=WIFI subType= reason=null isConnected=true
,I/MusicLeanback( 7531): Stop autocaching.
,V/SetupWizard( 7314): Connected to Gservices successfully
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/art     ( 7531): CheckpointMarkThreadRoots callback created = 0xaaf1c6f0
I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
,I/MusicLeanback( 7531): Stop autocaching.
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/GHttpClientFactory( 7531): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7531): Using platform SSLCertificateSocketFactory
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/MusicLeanback( 7531): Stop autocaching.
,I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/AppUp4:CustModeStarterReceiver( 7289): onReceive
I/AppUp4:CustModeStarterReceiver( 7289): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7289): Context : android.app.ReceiverRestrictedContext@146751a9
D/AppUp4:CustFacade( 7289): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7289): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7289): begin check event
I/AppUp4:CustModeStarterReceiver( 7289): Event For Nothing, skip.
D/administrator(  855): Handling package changes for user 0
,I/ActivityManager(  855): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7589 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 7531): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  855): Process com.google.android.apps.magazines (pid 7394) has died
,I/NotificationManager( 7357): com.google.android.talk: cancel(8) by com.google.android.talk
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,W/ResourcesManager( 7357): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7357): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
E/GmsUtils( 7531): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7531): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/NotificationService(  855): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  855): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  855): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
E/lowmemorykiller(  241): Error writing /proc/7461/oom_score_adj; errno=22
,V/JNIHelp ( 7357): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Process com.android.chrome (pid 7461) has died
W/System  ( 7357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7357): Installed default security provider GmsCore_OpenSSL
V/BackupManagerService(  855): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  855): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2a7d7f2e
,I/AppConfig( 7589): Total System Memory = 906309632
,I/GalleryUtils( 7589): Application Heap = 96 MB
I/AppConfig( 7589): App Tier : NOT_DEF
D/SystemHelper( 7589): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  855): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  855): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7611 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7611): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7611): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7611): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7611): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7611): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  855): applying state to connected service
I/SystemConfig( 7611): BUILD Country: EU
I/SystemConfig( 7611): BUILD Operator: OPEN
I/ActivityManager(  855): Process com.google.android.apps.plus (pid 7483) has died
,I/ActivityManager(  855): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7637 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7611): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7611): existFile = false
I/SystemConfig( 7611): canReadFile = false
I/SystemConfig( 7611): systemFeature RCS result false
D/SystemConfig( 7611): refreshRcsSupport() :false
,I/LockScreenSettings( 7637): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7637): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7637): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7637): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7637): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7637): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7654 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  855): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7688 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
,D/Finsky  ( 7688): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7688): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7688): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7688): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7688): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@341b4f69 on behalf of 7688
D/Finsky  ( 7688): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7688): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7688): Skipping gmscore version check
,D/PackageBroadcastService( 4167): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4167): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7688): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 4167): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7688): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  855): Killing 7337:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_7337/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 4167): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4167): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  855): Killing 7531:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10081/pid_7531/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Killing 7314:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10038/pid_7314/cgroup.procs: No such file or directory
,D/charger_monitor(  491): init target 500000
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 134547143859; DSPS: 4506953; Offset : -3004422490
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  855): acquireWakeLockInternal: lock=110342649, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=855
,D/WeatherService( 2594): 2 : TimeTick Intent has been received, Time(hour:min:sec) 20:15:0
,D/WeatherService( 2594): 2 : TimeTick Intent And Screen On
D/WeatherService( 2594): 2 : SDK version : 21
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2594): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2594): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2594): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2594): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2594): 2 : This is isUpdating : false
D/WeatherService( 2594): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2594): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2594): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2594): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
,D/WeatherReflect( 2594): 2 : Map key string is -2
,I/[SystemUI]Clock( 1372): called onTimeUpdated()
,D/lim     ( 2594): 2 : time = 20:15
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,I/WeatherReflect( 2594): Model Name : LG-D722
D/WeatherTheme( 2594): 2 : Different view - status_min_formatted : 14 != 15
D/WeatherTheme( 2594): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2594): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2594): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2594): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2594): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2594): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2594): forecast size is 0
,D/Theme   ( 2594): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2594): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2594): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2594): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2594): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2594): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2594): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2594): url is : null
D/Theme   ( 2594): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2594): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2594): 2 : update view, appWidgetId: 2
D/WeatherService( 2594): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 20:15:0
,D/PowerManagerServiceEx(  855): releaseWakeLockInternal: lock=110342649 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  302): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  855): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7778 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{2cb2d53e type 2 when 144127 com.google.android.gms} when 144127
,I/DigitalAppWidgetProvider( 7778): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7778): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3ea58ae2
I/ActivityManager(  855): Killing 7289:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_7289/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4167): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4167): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 4167): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 4167): Failed to execute periodic sync, missing client context - aborting
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  855): Explicit concurrent mark sweep GC freed 37101(1760KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.243ms total 149.551ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/VacuumService( 1730): Vacuum at: now=1452280502118 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  855): ALS enabled for SRE
,D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (31661 ms ago)
D/qdlights(  855): set_light_backlight: 252
,D/qdlights(  855): set_light_backlight: 249
D/qdlights(  855): set_light_backlight: 245
,D/qdlights(  855): set_light_backlight: 242
,D/qdlights(  855): set_light_backlight: 239
,D/qdlights(  855): set_light_backlight: 235
,D/qdlights(  855): set_light_backlight: 232
,D/qdlights(  855): set_light_backlight: 229
,D/qdlights(  855): set_light_backlight: 225
,D/qdlights(  855): set_light_backlight: 222
,D/qdlights(  855): set_light_backlight: 219
,D/qdlights(  855): set_light_backlight: 215
,D/qdlights(  855): set_light_backlight: 212
,D/qdlights(  855): set_light_backlight: 209
,D/qdlights(  855): set_light_backlight: 205
,D/qdlights(  855): set_light_backlight: 202
,D/qdlights(  855): set_light_backlight: 199
,D/qdlights(  855): set_light_backlight: 195
,D/qdlights(  855): set_light_backlight: 192
,D/qdlights(  855): set_light_backlight: 189
,D/qdlights(  855): set_light_backlight: 185
,D/qdlights(  855): set_light_backlight: 182
,D/qdlights(  855): set_light_backlight: 179
,D/qdlights(  855): set_light_backlight: 175
,D/qdlights(  855): set_light_backlight: 172
,D/qdlights(  855): set_light_backlight: 169
,D/qdlights(  855): set_light_backlight: 165
,D/qdlights(  855): set_light_backlight: 162
,D/qdlights(  855): set_light_backlight: 159
,D/qdlights(  855): set_light_backlight: 155
,D/qdlights(  855): set_light_backlight: 152
,D/qdlights(  855): set_light_backlight: 149
,D/qdlights(  855): set_light_backlight: 145
,D/qdlights(  855): set_light_backlight: 142
,D/qdlights(  855): set_light_backlight: 139
,D/qdlights(  855): set_light_backlight: 135
,D/qdlights(  855): set_light_backlight: 132
,D/qdlights(  855): set_light_backlight: 129
,D/qdlights(  855): set_light_backlight: 125
,D/qdlights(  855): set_light_backlight: 122
,D/qdlights(  855): set_light_backlight: 119
,D/qdlights(  855): set_light_backlight: 115
,D/qdlights(  855): set_light_backlight: 112
,D/qdlights(  855): set_light_backlight: 109
,D/qdlights(  855): set_light_backlight: 105
,D/qdlights(  855): set_light_backlight: 102
,D/qdlights(  855): set_light_backlight: 99
,D/qdlights(  855): set_light_backlight: 95
,D/qdlights(  855): set_light_backlight: 92
,D/qdlights(  855): set_light_backlight: 89
,D/qdlights(  855): set_light_backlight: 85
,D/qdlights(  855): set_light_backlight: 82
,D/qdlights(  855): set_light_backlight: 79
,D/qdlights(  855): set_light_backlight: 75
,D/qdlights(  855): set_light_backlight: 72
,D/qdlights(  855): set_light_backlight: 69
,D/qdlights(  855): set_light_backlight: 65
,D/qdlights(  855): set_light_backlight: 62
,D/qdlights(  855): set_light_backlight: 59
,D/qdlights(  855): set_light_backlight: 55
,D/qdlights(  855): set_light_backlight: 52
,D/qdlights(  855): set_light_backlight: 49
,D/qdlights(  855): set_light_backlight: 45
,D/qdlights(  855): set_light_backlight: 42
,D/qdlights(  855): set_light_backlight: 39
,D/qdlights(  855): set_light_backlight: 35
,D/qdlights(  855): set_light_backlight: 32
,D/qdlights(  855): set_light_backlight: 29
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  855): set_light_backlight: 25
,D/qdlights(  855): set_light_backlight: 22
,D/qdlights(  855): set_light_backlight: 19
,D/qdlights(  855): set_light_backlight: 15
,D/qdlights(  855): set_light_backlight: 12
,D/qdlights(  855): set_light_backlight: 10
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 154547913591; DSPS: 5162339; Offset : -3004446007
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  855): ALS enabled for SRE
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (38652 ms ago)
I/PowerManagerService(  855): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  855): ALS enabled for SRE
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (38664 ms ago)
W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  855): Sleeping (uid 1000)...
D/LPWGController(  855): [updateScreenState] screen on = false
D/LPWGController(  855): disable proximity sensor
D/LPWGController(  855): enable proximity sensor
I/SensorManager(  855): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2ba35984] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  855): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  855): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  855): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  855): activate: handle is 48, enable
V/sensors_hal_Ctx(  855): activate sensors is 1400000000000
D/sensors_hal_Thresh(  855): enable: handle=48
I/sensors_hal_SAM(  855): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  855): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  855): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  855): enable: Received response: 0
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (38702 ms ago)
I/Adreno-EGL(  855): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  855): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  855): Build Date: 03/02/15 Mon
I/Adreno-EGL(  855): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  855): Remote Branch: 
I/Adreno-EGL(  855): Local Patches: 
I/Adreno-EGL(  855): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (983 us)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  855): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  855): processInd: handle 48, count=1
V/sensors_hal_Thresh(  855): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  855): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  855): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  855): poll: count: 256
I/sensors_hal_Ctx(  855): poll: released wakelock sensor_ind
D/sensors_hal_Util(  855): waitForResponse: timeout=0
D/LPWGController(  855): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  855): current mode = 1  value = 1 1
,I/LPWGController(  855): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  855): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  855): set_light_backlight: 0
,I/SensorManager(  855): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  855): activate: handle is 46, disable
V/sensors_hal_Ctx(  855): activate sensors is 1000000000000
D/sensors_hal_LP2(  855): enable: handle=46
D/sensors_hal_LP2(  855): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  855): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  855): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,I/DisplayManagerService(  855): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  855): Display changed displayId=0
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  855): Excessive delay in setPowerMode(): 218ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  855): Got set_interactive hint
D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/WifiServerServiceExt(  855): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  286): setParameters(): io 0, keyvalue screen_state=on, calling pid 855
,D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=on
,V/voice   (  286): voice_set_parameters: enter: screen_state=on
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  286): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/WifiServerServiceExt(  855): set CMD_KT_SCAN_INTERVAL
D/GpsLocationProvider(  855): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:true
I/LEDService( 1799): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1782): action : android.intent.action.SCREEN_ON
D/LEDService( 1799): stopPatternFlashing()
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): updateLightsLocked : turn off led
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1799): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1799): lockStatus = 0
D/LEDHandler( 1799): RESTART MSG
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
D/Ulp_jni (  855): JNI:system_update. Event-0
D/SplitWindow(  855): check instance of lgWin Window{2cb36233 u0 SearchPanel}
,D/InputDispatcher(  855): Window went away: Window{109e70bf u0 SearchPanel}
I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2594): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:15:17
,D/WeatherService( 2594): 2 : ACTION screen on
D/WeatherService( 2594): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2594): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:15:17
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): ACTION_SCREEN_ON
,D/AppCleanupService( 4031): android.intent.action.SCREEN_ON
,V/AudioFlinger(  286): setParameters(): io 0, keyvalue screen_state=off, calling pid 855
D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: enter: screen_state=off
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  286): voice_extn_compress_voip_set_parameters: exit
V/voice   (  286): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  286): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  286): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  286): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  286): adev_set_parameters: exit with code(0)
D/WifiController(  855): CMD_SCREEN_OFF 
D/WifiController(  855): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  855): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:false
,I/LEDService( 1799): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1799): stopPatternFlashing()
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1799): clear
I/LEDService( 1799): updateLightsLocked : turn on led
E/LEDService( 1799): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1799): Can't handle this request of patternId:0
D/LEDHandler( 1799): RESTART MSG
D/LNfcService( 1782): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1799): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1782): mScreenState : 1, mInProvisionMode : false
,I/Sensors (  430): sns_pwr.c(301):releasing wakelock
I/[LGHome]EVENT( 1873): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2594): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:15:17
D/WeatherService( 2594): 2 : ACTION screen off
D/WeatherService( 2594): 2 : TimeTick Receiver Unregister
D/WeatherService( 2594): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:15:17
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): ACTION_SCREEN_OFF
,D/AppCleanupService( 4031): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4031): AppUsageStatsSaveTask
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
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{16be89f0 type 2 when 164588 com.android.systemui} when 164588
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 174548597021; DSPS: 5817721; Offset : -3004434171
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{1cc80b69 type 2 when 188436 android} when 188436
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{30dd09ee type 2 when 190470 com.google.android.gms} when 190470
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 47190(2MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 13MB/22MB, paused 2.835ms total 149.616ms
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 1879 seconds from now (1452280548250)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  855): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 194549351909; DSPS: 6473106; Offset : -3004442067
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/ThermalEngine(  302): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 214550153725; DSPS: 7128492; Offset : -3004433891
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 234550877519; DSPS: 7783876; Offset : -3004442388
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 254551735324; DSPS: 8439264; Offset : -3004438788
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 274552417921; DSPS: 9094646; Offset : -3004428021
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 294553105413; DSPS: 9750029; Offset : -3004442303
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  302): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6239): --= Surplus to requirements =--
I/jxcore-log( 6239): 
I/jxcore-log( 6239): ****TEST TOOK:  ms ****
I/jxcore-log( 6239): 
I/jxcore-log( 6239): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6239): 
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 314554369832; DSPS: 10405430; Offset : -3004429235
,D/AndroidRuntime( 7898): 
D/AndroidRuntime( 7898): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7898): CheckJNI is OFF
,D/AndroidRuntime( 7898): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  855): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  855): Killing 6239:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  855): Skipping PackageSetting{214f7b0d com.example.hello/10317} due to missing metadata
,I/WindowState(  855): WIN DEATH: Window{aee2d03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  855): Focus left window: Window{aee2d03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  855): Window went away: Window{aee2d03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  855):   Force finishing activity ActivityRecord{2e17b0f0 u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  855): Display changed displayId=0
D/DSDPConnection( 1748): Display #0 changed.
,W/ActivityManager(  855): Spurious death for ProcessRecord{1e15ca9e 6239:com.test.thalitest/u0a316}, curProc for 6239: null
I/ActivityManager(  855): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  855):   Force finishing activity ActivityRecord{2e17b0f0 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  855): Duplicate finish request for ActivityRecord{2e17b0f0 u0 com.test.thalitest/.MainActivity t220 f}
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1873): [Launcher.java:5203:onStart()]onStart
W/System.err( 3601): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/[LGHome]EVENT( 1873): [Launcher.java:776:onResume()]onResume
W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
W/System.err( 3601): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3601): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3601): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3601): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3601): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3601): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3601): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3601): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3601): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/art     ( 1933): Explicit concurrent mark sweep GC freed 10606(691KB) AllocSpace objects, 3(72KB) LOS objects, 40% free, 12MB/21MB, paused 3.493ms total 108.495ms
I/art     ( 4167): Explicit concurrent mark sweep GC freed 4954(282KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/18MB, paused 1.059ms total 104.045ms
,I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7931 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  855): Explicit concurrent mark sweep GC freed 35914(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 2.056ms total 226.105ms
,I/art     (  855): WaitForGcToComplete blocked for 161.711ms for cause Explicit
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1873): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1873): [Launcher.java:929:onResume()]onResume end
I/Activity( 1873): Activity.onPostResume() called 
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 1372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1372): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
,W/ResourcesManager( 1372): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 1372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1372): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@259015d0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/[LGHome]LGWallpaperInfo( 1873): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1873): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@259015d0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1372): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/InputDispatcher(  855): Focus entered window: Window{235db7c8 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
,W/ResourcesManager( 7931): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1372): handleShortcutListChanged...
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): createShortcutInfo...
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
D/administrator(  855): Handling package changes for user 0
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1873): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1372): handleShortcutListChanged...
,I/art     (  855): Explicit concurrent mark sweep GC freed 4678(249KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.235ms total 314.046ms
,I/LGEmail ( 7931): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7931): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/NotificationService(  855): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/AndroidRuntime( 7898): Shutting down VM
D/JobSchedulerService(  855): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  855): removeObsoleteFile: deleting file=220_task.xml
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/InputMethodManagerService(  855): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  855): Got RemoteException sending setActive(false) notification to pid 6239 uid 10316
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/PackageChangeReceiver( 7931): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1873): getTextBeforeCursor on inactive InputConnection
,I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7955 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  855): Killing 7589:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 322us total 24.463ms
,E/b       ( 1580): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 23.854ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1873): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1873): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 335us total 24.020ms
,W/libprocessgroup(  855): failed to open /acct/uid_10023/pid_7589/cgroup.procs: No such file or directory
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{1bbe605a u0 com.lge.launcher2/.Launcher t219} time:316599
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
,W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
I/AppUp4:AppBoxCP( 7955): onCreate
W/AppUp4:DB( 7955):  [AppBoxDatabaseHelper] construct
,W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/AppUp4:DB( 7955):  setFingerPrint start
I/AppUp4:DB( 7955):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/AppUp4:DB( 7955):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7955):  SDK version = 0
I/AppUp4:DB( 7955):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7955): AppBoxApplication onCreate()
W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AppUp4:PreloadHelper( 7955): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
