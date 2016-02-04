#### Test 58259810381ca4f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/SystemConfig( 5396): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5396): existFile = false
I/SystemConfig( 5396): canReadFile = false
I/SystemConfig( 5396): systemFeature RCS result false
D/SystemConfig( 5396): refreshRcsSupport() :false
I/LockScreenSettings( 5417): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5417): New app installed broadcast received ..
I/LockScreenSettings( 5417): Number of installed packages  1
,--------- beginning of system
I/ActivityManager(  853): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5448 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 4281:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_4281/cgroup.procs: No such file or directory
D/EulaProviderUpdateObserver( 5448): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5448): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5217): android.intent.action.PACKAGE_ADDED : com.test.thalitest
I/ActivityManager(  853): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5469 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 5234:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_5234/cgroup.procs: No such file or directory
D/AndroidRuntime( 5466): 
D/AndroidRuntime( 5466): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5466): CheckJNI is OFF
D/AndroidRuntime( 5466): Calling main entry com.android.commands.am.Am
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2de6e57f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2de6e57f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  853): AppWindowTokenEx init.. 
D/ContextHelper(  853): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/GAv4    ( 5469): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5469):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5469):   adb logcat -s GAv4
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  853): Focus left window: Window{1910d2e0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5466): Shutting down VM
W/GAv4    ( 5469): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/SplitWindow(  853): check instance of lgWin Window{5d67e11 u0 Starting com.test.thalitest}
I/ActivityManager(  853): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5508 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
W/GAv4    ( 5469): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/WindowStateAnimator(  853): Starting window displayed
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/HotwordDetector( 1943): Closing mic
W/GAv4    ( 5469): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cae59be,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/MicrophoneInputStream( 1943): mic_close com.google.android.apps.gsa.speech.audio.u@38c02ab4
V/AudioRecord( 1943): stop()
D/AudioRecord( 1943): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
W/AnalyticsTrackerProxyImpl( 5469): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb438e000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
D/BarTransitions( 1372): draw background and invalidate : color = e000000
D/BarTransitions( 1372): draw background and invalidate : color = f0e0e0e
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
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
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2e338213 type 2 when 80536 android} when 80536
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
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb438e000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1943): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb438e000 exiting
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioFlinger(  281): removeClient_l() pid 1943, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 1752): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): releasing 16 from 1943 for -1
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioSystem( 3224): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2691): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1943): Stopping hotword detection.
I/HotwordRecognitionRnr( 1943): Hotword detection finished
D/ContextHelper( 5508): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5508): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5508): Time to load native libraries: 2 ms (timestamps 760-762)
I/LibraryLoader( 5508): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5508): Binding Chromium to main looper Looper (main, tid 1) {2b5d629c}
I/LibraryLoader( 5508): Expected native library version number "",actual native library version number ""
I/chromium( 5508): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5469): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/BrowserStartupController( 5508): Initializing chromium process, singleProcess=true
W/art     ( 5508): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5508): ApplicationContext is null in ApplicationStatus
D/AlertService( 3816): Beginning updateAlertNotification
I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5548 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 5288:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/chromium( 5508): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5508): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5508): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5508): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5508): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5508): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5508): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5508): Remote Branch: 
I/Adreno-EGL( 5508): Local Patches: 
I/Adreno-EGL( 5508): Reconstruct Branch: 
W/ResourcesManager( 5469): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5469): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 5469): CheckpointMarkThreadRoots callback created = 0xb050fa70
E/lowmemorykiller(  243): Error opening /proc/5288/oom_score_adj; errno=2
W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_5288/cgroup.procs: No such file or directory
I/ActivityThread( 3816): Removing dead content provider:android.content.ContentProviderProxy@22c40e65
V/AudioPolicyService(  281): registerClient() client 0xb4027080, uid 10316
W/ResourcesManager( 5548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30256568:true
D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
I/art     ( 5469): CheckpointMarkThreadRoots callback created = 0xb050fa40
I/NotificationManager( 5469): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
I/ActivityManager(  853): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5575 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5575): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 5469): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/CalendarProvider2( 5575): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@153dfdb3
,D/CalendarProvider2( 5575): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5575): Created com.android.providers.calendar.CalendarAlarmManager@2b5d629c(com.android.providers.calendar.CalendarProvider2@153dfdb3)
,D/AlertService( 3816): No fired or scheduled alerts
,I/NotificationManager( 3816): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(3) by com.android.calendar
,W/System  ( 5469): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5469): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 3816): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 3816): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 3816): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3816): com.android.calendar: cancel(20) by com.android.calendar
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AlertService( 3816): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3816): No events found starting within 1 week.
,W/art     ( 5508): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5508): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5508): CordovaWebView is running on device made by: LGE
,W/art     ( 5508): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5508): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5508): Activity.onPostResume() called 
,D/OpenGLRenderer( 5508): Render dirty regions requested: true
I/OpenGLRenderer( 5508): Initialized EGL, version 1.4
D/OpenGLRenderer( 5508): Enabling debug mode 0
,D/Atlas   ( 5508): Validating map...
,D/SplitWindow(  853): check instance of lgWin Window{21b06061 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5508): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  853): Killing 5312:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_5312/cgroup.procs: No such file or directory
,D/InputDispatcher(  853): Focus entered window: Window{21b06061 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  853): Killing 5339:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 5508): Timeline: Activity_idle id: android.os.BinderProxy@1b82ba1b time:81615
,W/libprocessgroup(  853): failed to open /acct/uid_10009/pid_5339/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Displayed com.test.thalitest/.MainActivity: +1s310ms
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{2476994c u0 com.test.thalitest/.MainActivity t222} time:81637
W/BindingManager( 5508): Cannot call determinedVisibility() - never saw a connection for the pid: 5508
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5628 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
,D/JsMessageQueue( 5508): Set native->JS mode to OnlineEventsBridgeMode
,D/Finsky  ( 5628): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  486): init target 500000
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/WifiController(  853): battery changed pluggedType: 2
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/MainApplication( 5217): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/MainApplication( 5217): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WifiController(  853): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,D/Finsky  ( 5628): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5628): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5628): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5628): com.android.vending: cancel(-1050172287) by com.android.vending
,D/jxcore_app_log( 5508): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622977024
,I/art     ( 3991): Explicit concurrent mark sweep GC freed 8003(403KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 1.104ms total 29.069ms
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2286443d on behalf of 5628
I/NotificationManager( 5628): com.android.vending: cancel(1003285959) by com.android.vending
I/chromium( 5508): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Ads     ( 5628): Skipping gmscore version check
,D/Finsky  ( 5628): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5628): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  853): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5675 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 5508): CheckpointMarkThreadRoots callback created = 0x9c5b9500
,I/art     ( 5508): CheckpointMarkThreadRoots callback created = 0x9c5b94d0
,D/Finsky  ( 5628): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/art     ( 5508): Background partial concurrent mark sweep GC freed 9083(720KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 5.415ms total 57.434ms
,D/Finsky  ( 5628): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5628): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  853): Killing 5359:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_5359/cgroup.procs: No such file or directory
,W/ResourcesManager( 5675): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5675): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5675): VM with version 2.1.0 has multidex support
I/MultiDex( 5675): install
,I/MultiDex( 5675): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5675): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5675): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5675): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f1569f4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5675): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5675): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5675): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5675): Reading stored module config
,D/PackageBroadcastService( 5675): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5675): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5675): Loading module APK com.google.android.play.games
I/art     (  853): Explicit concurrent mark sweep GC freed 23301(1182KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.510ms total 172.080ms
,D/NativeLibraryUtils( 5675): Install completed successfully. count=14 extracted=0
,I/art     ( 5675): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/art     ( 5675): CheckpointMarkThreadRoots callback created = 0xb042d430
,D/ChimeraCfgMgr( 5675): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5675): Module APK com.google.android.play.games already loaded
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
D/ChimeraCfgMgr( 5675): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleDatabaseHelper( 5675): cleanUpNonGplusAccounts done.
D/AsyncTaskServiceImpl( 5675): Submit a task: k
,I/ActivityManager(  853): Process com.android.contacts (pid 5396) has died
,D/ChimeraCfgMgr( 5675): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5675): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5675): Processing package: com.test.thalitest
I/Icing   ( 5675): Storage manager: low false usage 1.70MB avail 2.38GB capacity 4.06GB
,W/BaseAppContext( 5675): Using Auth Proxy for data requests.
D/GassUtils( 5675): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5675): Found info for package com.test.thalitest in db.
I/art     ( 5675): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5675): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/BaseAppContext( 5675): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5675): Using Auth Proxy for data requests.
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,W/BaseAppContext( 5675): Using Auth Proxy for data requests.
,E/MDM     ( 1733): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5675): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BaseAppContext( 5675): Using Auth Proxy for data requests.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5675): Using Auth Proxy for data requests.
W/BaseAppContext( 5675): Using Auth Proxy for data requests.
W/jxcore-log( 5508): Initializing JXcore engine
,W/jxcore-log( 5508): JXcore engine is ready
I/ActivityManager(  853): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5742 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 5675): Using Auth Proxy for data requests.
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
W/Thread-651( 5671): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5851]" dev="sockfs" ino=5851 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-651( 5671): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-651( 5671): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6005]" dev="sockfs" ino=6005 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-651( 5671): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5671): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5671): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21350]" dev="sockfs" ino=21350 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5508): Starting JXcore engine
,I/ActivityManager(  853): Process com.android.gallery3d (pid 5377) has died
W/IcingInternalCorpora( 5675): getNumBytesRead when not calculated.
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/jxcore-log( 5508): Platform android
W/jxcore-log( 5508): 
W/jxcore-log( 5508): Process ARCH arm
W/jxcore-log( 5508): 
,I/Gmail   ( 5742): getAccountsCursor
,I/ActivityManager(  853): Process com.lge.lockscreensettings (pid 5417) has died
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5742): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5742): Error finding the version of the Email provider.....
E/Gmail   ( 5742): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5742): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5742): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5742): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5742): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/EmailMigration( 5742): We do not support migrating this version of the Email provider.
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/lowmemorykiller(  243): Error writing /proc/5448/oom_score_adj; errno=22
,I/Gmail   ( 5742): getAccountsCursor
,I/Gmail   ( 5742): Observing account changes for notifications
,I/Icing   ( 5675): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  853): Process com.lge.eula (pid 5448) has died
,D/ChimeraCfgMgr( 5675): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5675): Module APK com.google.android.play.games already loaded
I/PhoneApp( 1752): onTrimMemory: 10
I/PhoneApp( 1752): trim memory
,I/BackgroundMemoryTrimmer( 1943): Trimming objects from memory, since app is in the background.
I/art     ( 1733): Explicit concurrent mark sweep GC freed 18611(1150KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 13MB/22MB, paused 2.097ms total 119.112ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2023d432 on behalf of 5675
,I/art     ( 3991): Explicit concurrent mark sweep GC freed 2949(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.921ms total 32.573ms
,W/InstanceID/Rpc( 5675): Found 10006
D/InitAlarmsService( 3816): Clearing and rescheduling alarms.
,I/art     ( 5675): Background sticky concurrent mark sweep GC freed 14450(1082KB) AllocSpace objects, 12(192KB) LOS objects, 7% free, 13MB/14MB, paused 10.626ms total 121.297ms
,I/jxcore-log( 5508): JXcore Cordova bridge is ready!
I/jxcore-log( 5508): 
W/jxcore-log( 5508): JXcore engine is started
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5795 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.360ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.667ms
,I/Gmail   ( 5742): notifyAccountChanged
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 421us total 21.911ms
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2a94c583 on behalf of 5675
D/CalendarProvider2( 5575): Scheduling check of next Alarm
,D/CalendarProvider2( 5575): SCHEDULE_ALARM_REMOVE
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@3bd83300 on behalf of 5675
I/Gmail   ( 5742): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5742): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5742): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5742): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5742): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{2b4be764 type 0 when 1454578903487 com.google.android.googlequicksearchbox} when 1454578903487
,D/PhoneMonitor( 5795): Register our PhoneStateListener
,I/Icing   ( 5675): Internal init done: storage state 0
,I/jxcore-log( 5508): Toggling radios to true
I/jxcore-log( 5508): 
D/BluetoothAdapter( 5508): enable(): BT is already enabled..!
I/NotificationManager( 5675): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/WifiServiceImplEx(  853): setWifiEnabled: true pid=5508, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  853): setWifiEnabled: true pid=5508, uid=10316
,D/WifiServiceImplEx(  853): disconnect pid=5508, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  853): reconnect pid=5508, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5508): Radios toggled
I/jxcore-log( 5508): 
I/jxcore-log( 5508): My device name is: LGE-LG-D722
I/jxcore-log( 5508): 
I/Icing   ( 5675): Post-init done
,I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2801): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  853): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/PhoneMonitor( 5795): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5795): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5795): [parse] Load xml
,I/Gmail   ( 5742): getAccountsCursor
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  277): Clearing all IP addresses on wlan0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
V/TelephonyAutoProfiling( 5795): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5795): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/NativeCrypto( 1733): Read error: ssl=0xaaf3d600: I/O error during system call, Connection timed out
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaf3d600: I/O error during system call, Broken pipe
D/PhoneMonitor( 5795): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  853): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:43.727 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-8ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Forcing reevaluation
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/WifiStateMachine(  853): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:43.743 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/CheckinService( 5675): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 6614
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,I/art     ( 5675): Background sticky concurrent mark sweep GC freed 6872(541KB) AllocSpace objects, 9(144KB) LOS objects, 6% free, 13MB/14MB, paused 16.926ms total 45.845ms
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityService(  853): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  853): disableDataServiceNotify
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:43.825 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DSQN    (  853): stop dsqn bin
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/CheckinService( 5675): Disabling old GoogleServicesFramework version
D/WifiNetworkAgent(  853): NetworkAgent: NetworkAgent channel lost
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  853): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:43.861 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:43.862 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  853): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  853): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/DhcpStateMachine(  853): StoppedState
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/DhcpStateMachine(  853): StoppedState{ when=-136ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/CSLegacyTypeTracker(  853): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  853): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1842): |CORE| No family connected
V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1752): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  853): Removing idletimer
W/Settings(  853): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  853): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/art     (  853): Explicit concurrent mark sweep GC freed 24846(1136KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 14.656ms total 242.824ms
D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateSCANNING
D/Tethering(  853): MasterInitialState.processMessage what=3
D/Tethering(  853): MasterInitialState.processMessage what=3
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5836 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,I/CheckinService( 5675): Checking schedule, now: 1454578904024 next: 1454578927114
I/CheckinService( 5675): active receiver: disabled
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
W/ResourcesManager( 5836): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Process com.lge.bnr (pid 5217) has died
,I/Babel_SMS( 5836): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5836): MmsConfig.loadMmsSettings
I/Babel_SMS( 5836): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5836): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5836): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5836): MmsConfig.loadFromResources
E/Babel_SMS( 5836): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5836): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/CalendarProvider2( 5575): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5575): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/SensorManager( 5836): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5836): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5836): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5836): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5836): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5836): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5836): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5836): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5836): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5836): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5836): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5836): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5836): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5836): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5836): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5836): found sensor: Motion Accel, handle=46
I/art     ( 5836): CheckpointMarkThreadRoots callback created = 0xb042d890
,W/Settings( 5836): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5836): startup - clean
,I/art     ( 5836): CheckpointMarkThreadRoots callback created = 0xb042d870
I/Babel   ( 5836): deleted: false for 0
,W/AudioCapabilities( 5836): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5836): Unsupported mime audio/adpcm
W/AudioCapabilities( 5836): Unsupported mime audio/g726
W/AudioCapabilities( 5836): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5836): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5836): Unsupported mime video/mjpg
W/VideoCapabilities( 5836): Unsupported mime video/theora
,W/AudioCapabilities( 5836): Unsupported mime audio/evrc
,W/AudioCapabilities( 5836): Unsupported mime audio/qcelp
W/VideoCapabilities( 5836): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5836): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5836): Unsupported mime audio/qcelp
W/AudioCapabilities( 5836): Unsupported mime audio/evrc
W/VideoCapabilities( 5836): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5836): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5836): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5836): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5836): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5836): Unrecognized profile 2130706433 for video/avc
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/vclib   ( 5836): onServiceConnected
W/Babel   ( 5836): Attempted to change video mute state without an active call.
I/wpa_supplicant( 2801): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/NotificationManager( 5836): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LocSvc_java(  853): onReceive
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:44.922 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:44.927 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/ResourcesManager( 5836): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5836): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  853): Process com.google.android.apps.docs (pid 5469) has died
,I/Icing   ( 5675): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5876 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5189): getMode name:com.lge.qremote
,V/JNIHelp ( 5836): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5189): getMode name:com.lge.qremote
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2801): wlan0: Associated with c0:ff:d4:d3:aa:48
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.188 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.192 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/wpa_supplicant( 2801): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2801): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/AudioManager( 5189): getMode name:com.lge.qremote
I/WifiServiceExtension(  853): setVHTCapabilityType  : false
,D/Icing   ( 5675): Loaded CLD2 Version V2.0 - 20141016
W/art     ( 5836): Suspending all threads took: 7.700ms
I/WifiServerServiceExt(  853): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  853): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  853): setSecurityType  : 2
I/AudioManager( 5189): getMode name:com.lge.qremote
D/UEI.SmartControl( 5876): Quickset Services start...
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.264 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.277 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/UEI.SmartControl( 5876): Manufacture = LGE
D/ConnectivityService(  853): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  853): Got NetworkAgent Messenger
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  853): NetworkAgent connected
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/UEI.SmartControl( 5876): File observer start...
E/UEI.SmartControl( 5876): IR Port is disabled: false
D/UEI.SmartControl( 5876): Starting file observer...
D/UEI.SmartControl( 5876): Extracting JNI libs...
I/Icing   ( 5675): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/AudioManager( 5189): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5876): --- this system supports 32-bit or 64-bit only
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/MDM     ( 1733): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Setting iface cfg
E/WifiStateMachine(  853): Start Dhcp Watchdog 2
D/DhcpStateMachine(  853): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): WaitBeforeStartState
D/LocationInitializer( 5675): Restart initialization of location
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateGROUP_HANDSHAKE
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
W/System  ( 5836): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5836): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 5189): getMode name:com.lge.qremote
I/NotificationManager( 5836): com.google.android.talk: cancel(8) by com.google.android.talk
,E/WifiStateMachine(  853): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21ce8db7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21ce8db7 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): DHCP Start wake lock is acquired.
D/CommandListener(  277): Setting iface cfg
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  853): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5905 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateCOMPLETED
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  853): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  853): ignoring duplicate network state non-change
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  853): Adding iface wlan0 to network 101
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine(  853): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.531 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.535 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  853): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  853): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.537 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  853): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:45.539 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; a,i_family=0
E/Netd    (  277): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  853): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/ConnectivityService(  853): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  853): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  853): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  853): currentScore = 0, newScore = 20
D/ConnectivityService(  853):    accepting network in place of null
D/ConnectivityService(  853): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1752): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] Start DNSResolver start to wait
D/UEI.SmartControl( 5876): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/UEI.SmartControl( 5876): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5876): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/WIFI    (  853): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  853): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  853): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wait 500ms before dns check
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  853): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  853): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  853): MasterInitialState.processMessage what=3
,W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  853): validation of new default Network = false
D/ConnectivityService(  853): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  853): enableDataServiceNotify 
D/DSQN    (  853): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/NetworkPolicy(  853): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/CheckinService( 5675): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 8465
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
I/DSQN    ( 5930): DSQN samuel.seo ver 141203
E/DSQN    ( 5930): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5930): created command queue thread
I/DSQN    ( 5930): Interface wlan0 address 192.168.1.134 0xc0a80186
,I/DSQN    ( 5930): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/DhcpStateMachine(  853): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  853): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  853): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5934): version 5.5.6 starting
,E/dhcpcd  ( 5934): get_duid: Read-only file system
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/CheckinService( 5675): Checking schedule, now: 1454578905650 next: 1454578927114
I/CheckinService( 5675): active receiver: disabled
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/UEI.SmartControl( 5876): --- Selecting new region: 2
,I/UEI.SmartControl( 5876): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5876): Platform has CIR...
D/UEI.SmartControl( 5876): NO CIR support, need to check package...
I/UEI.SmartControl( 5876): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5876): QS Service created
,I/dhcpcd  ( 5934): wlan0: rebinding lease of 192.168.1.134
,I/AppUp4:AppBoxCP( 5905): onCreate
W/AppUp4:DB( 5905):  [AppBoxDatabaseHelper] construct
E/UEI.SmartControl( 5876): QS start get config
,I/AppUp4:DB( 5905):  setFingerPrint start
I/AppUp4:DB( 5905):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5905):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5905):  SDK version = 0
I/AppUp4:DB( 5905):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5905): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5905): onReceive
I/AppUp4:CustModeStarterReceiver( 5905): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5905): Context : android.app.ReceiverRestrictedContext@128efb6e
D/AppUp4:CustFacade( 5905): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5905): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5905): begin check event
I/AppUp4:CustModeStarterReceiver( 5905): Event For Nothing, skip.
D/UEI.SmartControl( 5876): Loading JNI Libs...
D/UEI.SmartControl( 5876):  configuring local db...
,I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5943 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5876):  ---- Has DB8: true
,I/AppConfig( 5943): Total System Memory = 906309632
D/UEI.SmartControl( 5876): QS start statue = true Error code = 0
D/UEI.SmartControl( 5876): QS version = v2.7.11.1_RC1
I/GalleryUtils( 5943): Application Heap = 96 MB
D/UEI.SmartControl( 5876): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5876): IRRCDataComm has AudioManager!!!!.
I/AppConfig( 5943): App Tier : NOT_DEF
,W/irrc_jni( 5876): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5876): IrrcClient ++ 
D/irrcClient( 5876): getIrrcService ++ 
D/SystemHelper( 5943): region [EU], country [EU], operator [OPEN], sub-operator []
D/irrcClient( 5876): getIrrcService -- 
D/irrcClient( 5876): IrrcClient -- 
W/irrc_jni( 5876): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5876): Services init done
I/UEI.SmartControl( 5876): Device manager: loading config....
D/UEI.SmartControl( 5876): QS Service init finished
D/UEI.SmartControl( 5876): QS Service version name: 0.1.73
D/UEI.SmartControl( 5876): QS Service version code: 1073
,D/UEI.SmartControl( 5876): Service requested: Control
D/UEI.SmartControl( 5876): Config is loaded...
D/UEI.SmartControl( 5876): Internal service binding...
D/UEI.SmartControl( 5876): -----IControl: 11
D/UEI.SmartControl( 5876): Caller: com.lge.qremote
D/UEI.SmartControl( 5876): ------------ IControl registerCallback...
I/UEI.SmartControl( 5876): Registering callback...
D/UEI.SmartControl( 5876): -----IControl: 19
,D/UEI.SmartControl( 5876): Caller: com.lge.qremote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver start dns
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/UEI.SmartControl( 5876): Registering Services Ready callback...
I/UEI.SmartControl( 5876): Notify client services are ready...
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/UEI.SmartControl( 5876): -----IControl: 8
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 5876): Caller: com.lge.qremote
D/UEI.SmartControl( 5876):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5876): Notify AllClients services are ready: 0
I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5966 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3816:com.android.calendar/u0a13 (adj 15): empty #11
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  853): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_3816/cgroup.procs: No such file or directory
,W/ResourcesManager( 5966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5966): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5966): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5966): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5966): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/DSQN    ( 5930): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5930): restart monitoring
,D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5930): dsqn report finish
D/DSQN    (  853): DSQM DsqnNotification wlan0  1
D/DSQN    (  853): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 09:41:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454578906581], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454578906558]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Validated
D/ConnectivityService(  853): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  853): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1752): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  853): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  853): set CMD_CAPTIVE_CHECK_COMPLETED
,D/ConnectivityService(  853): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/SystemConfig( 5966): BUILD Country: EU
I/SystemConfig( 5966): BUILD Operator: OPEN
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/SystemConfig( 5966): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5966): existFile = false
,I/SystemConfig( 5966): canReadFile = false
I/SystemConfig( 5966): systemFeature RCS result false
D/SystemConfig( 5966): refreshRcsSupport() :false
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5996 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 5548:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  853): identical MTU - not setting
D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  853): enableDataServiceNotify 
D/DSQN    (  853): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
,D/DSQN    (  853): dsqn is running restart
I/DSQN    ( 6008): DSQN samuel.seo ver 141203
E/DSQN    ( 6008): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6008): created command queue thread
I/DSQN    ( 6008): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6008): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_5548/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:46.88 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/dhcpcd  ( 5934): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/dhcpcd  ( 5934): wlan0: leased 192.168.1.134 for 86400 seconds
,D/LocSvc_java(  853): broadcast - no network connections
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): broadcast - no network connections
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
,I/LockScreenSettings( 5996): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5996): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5996): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5996): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5996): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5996): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6027 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 5628:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10036/pid_5628/cgroup.procs: No such file or directory
,W/ResourcesManager( 6027): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
D/DhcpStateMachine(  853): DHCPV4 succeeded on wlan0
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,D/LgDhcpStateMachineHelper(  853): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  853): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  853): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  853): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  853): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  853): RunningState
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  853): Handling package changes for user 0
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3614c926
,I/ActivityManager(  853): Process com.google.android.gm (pid 5742) has died
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6062 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 102 ms] updated apps [took 101 ms] 
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  853): applying state to connected service
,I/ActivityManager(  853): Process com.lge.qremote (pid 5189) has died
,D/Finsky  ( 6062): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{36cb761 type 2 when 90397 com.android.providers.calendar} when 90397
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 10:41:48.357 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/Finsky  ( 6062): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6062): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6062): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6062): com.android.vending: cancel(-1050172287) by com.android.vending
V/WifiInternetCheck(  853): Single check msg out of sync, ignoring.
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@c97e739 on behalf of 6062
,D/Finsky  ( 6062): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6062): [1] Libraries$2.run: Finished loading 1 libraries.
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
,D/Ads     ( 6062): Skipping gmscore version check
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PackageBroadcastService( 5675): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6062): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6114 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PackageBroadcastService( 5675): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5675): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6062): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 5675): Background sticky concurrent mark sweep GC freed 11351(674KB) AllocSpace objects, 2(32KB) LOS objects, 4% free, 13MB/14MB, paused 9.790ms total 92.074ms
,W/ResourcesManager( 6114): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Process com.uei.lg.quicksetsdk.lite (pid 5876) has died
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fb162c2:true
,D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6140 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6114): Create singleton instance
,I/AudioManager( 6114): getMode name:com.lge.qremote
,I/art     (  853): Explicit concurrent mark sweep GC freed 84381(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.312ms total 185.241ms
,I/AudioManager( 6114): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  853): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6161 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.212ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 26.321ms
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.123ms
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
,D/UEI.SmartControl( 6140): Quickset Services start...
,I/UEI.SmartControl( 6140): Manufacture = LGE
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 6140): File observer start...
E/UEI.SmartControl( 6140): IR Port is disabled: false
D/UEI.SmartControl( 6140): Starting file observer...
D/UEI.SmartControl( 6140): Extracting JNI libs...
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/UEI.SmartControl( 6140): --- this system supports 32-bit or 64-bit only
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  853): propertyValue:false
I/DSQN    ( 6008): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6008): restart monitoring
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6008): dsqn report finish
,D/DSQN    (  853): DSQM DsqnNotification wlan0  1
,D/DSQN    (  853): start to monitor internet connection
,I/ActivityManager(  853): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6197 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6140): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6140): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6140): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6140): --- Selecting new region: 2
I/UEI.SmartControl( 6140): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6140): Platform has CIR...
D/UEI.SmartControl( 6140): NO CIR support, need to check package...
I/UEI.SmartControl( 6140): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6140): QS Service created
,E/UEI.SmartControl( 6140): QS start get config
,D/UEI.SmartControl( 6140): Loading JNI Libs...
,D/UEI.SmartControl( 6140):  configuring local db...
E/UpdateRequestReceiver( 6197): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6197): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6197): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6197): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  853): Killing 5575:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/Icing   ( 5675): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,V/WifiInternetCheck(  853): isHttpConnectionAvailable - We got a valid response : 204
,I/Icing   ( 5675): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_5575/cgroup.procs: No such file or directory
,I/CheckinService( 5675): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 13164
,I/GservicesUpdateTask( 1943): Updating Gservices keys
I/CheckinService( 5675): Checking schedule, now: 1454578910324 next: 1454578927114
I/CheckinService( 5675): active receiver: disabled
I/SystemUpdateService( 5675): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5675): onCreate
,D/UEI.SmartControl( 6140):  ---- Has DB8: true
,D/UEI.SmartControl( 6140): QS start statue = true Error code = 0
D/UEI.SmartControl( 6140): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6140): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6140): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6140): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6140): IrrcClient ++ 
D/irrcClient( 6140): getIrrcService ++ 
D/irrcClient( 6140): getIrrcService -- 
D/irrcClient( 6140): IrrcClient -- 
W/irrc_jni( 6140): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6140): Services init done
I/UEI.SmartControl( 6140): Device manager: loading config....
D/UEI.SmartControl( 6140): Config is loaded...
,D/SystemUpdateService( 5675): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/UEI.SmartControl( 6140): QS Service init finished
D/UEI.SmartControl( 6140): QS Service version name: 0.1.73
D/UEI.SmartControl( 6140): QS Service version code: 1073
D/UEI.SmartControl( 6140): Service requested: Control
D/UEI.SmartControl( 6140): Internal service binding...
,D/UEI.SmartControl( 6140): -----IControl: 11
D/UEI.SmartControl( 6140): Caller: com.lge.qremote
D/UEI.SmartControl( 6140): ------------ IControl registerCallback...
I/UEI.SmartControl( 6140): Registering callback...
D/UEI.SmartControl( 6140): -----IControl: 19
D/UEI.SmartControl( 6140): Caller: com.lge.qremote
I/UEI.SmartControl( 6140): Registering Services Ready callback...
I/UEI.SmartControl( 6140): Notify client services are ready...
I/SystemUpdateService( 5675): cancelUpdate (empty URL)
I/SystemUpdateService( 5675): active receiver: disabled
,D/UEI.SmartControl( 6140): -----IControl: 8
D/UEI.SmartControl( 6140): Caller: com.lge.qremote
I/ActivityManager(  853): Killing 5836:com.google.android.talk/u0a61 (adj 15): empty #11
,D/UEI.SmartControl( 6140):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6140): Notify AllClients services are ready: 0
I/NotificationManager( 5675): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 5675): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/ActivityManager(  853): Killing 5795:com.google.android.setupwizard/u0a38 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_5836/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_5795/cgroup.procs: No such file or directory
,I/art     ( 3991): Explicit concurrent mark sweep GC freed 4240(182KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 402us total 29.125ms
,I/art     ( 3991): Explicit concurrent mark sweep GC freed 2726(106KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 550us total 26.063ms
I/ActivityManager(  853): Killing 5905:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_5905/cgroup.procs: No such file or directory
,D/SystemUpdateService( 5675): onDestroy
E/DynamiteModule( 5675): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5675): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5675): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5675): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5675): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5675): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5675): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5675): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5675): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5675): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5675): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5675): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5675): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5675): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5675): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5675): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5675): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5675): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5675): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5675): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5675): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5675): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5675): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5675): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5675): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5675): 		... 17 more
E/DynamiteModule( 5675): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 5675): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5675): Selected local version of com.google.android.gms.flags
,I/art     ( 5675): Explicit concurrent mark sweep GC freed 14308(955KB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/17MB, paused 823us total 64.819ms
,D/SystemEventReceiver( 5675): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5675): Updating ocr activity enabled=false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5675): Updating downloaded model state (gservices changed)
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{173a1b7a type 0 when 1454578911577 com.android.vending} when 1454578911577
,D/Finsky  ( 6062): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/art     ( 1733): Explicit concurrent mark sweep GC freed 21062(1459KB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 13MB/22MB, paused 1.412ms total 99.078ms
,I/NotificationManager(  853): android: cancelAsUser(-591465577) by android
I/art     ( 3991): Explicit concurrent mark sweep GC freed 2532(100KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 889us total 27.626ms
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
D/GCM     ( 1733): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1733): DispatchingService.onCreate()
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6271 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd( 6062): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6062): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6062): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6062): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/GCoreUlr( 1733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 6062): propertyValue:false
D/libc-netbsd( 6062): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6062): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1733): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6271): Register our PhoneStateListener
V/SetupWizard( 6271): Connected to Gservices successfully
,D/PhoneMonitor( 6271): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6271): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6271): [parse] Load xml
,V/TelephonyAutoProfiling( 6271): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6271): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
W/ctxmgr  ( 1733): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
D/PhoneMonitor( 6271): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  853): Killing 5943:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/GCoreUlr( 1733): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/libc-netbsd( 6062): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6062): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/ctxmgr  ( 1733): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_5943/cgroup.procs: No such file or directory
I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1733): DispatchingService.onDestroy()
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/LocationInitializer( 5675): Restart initialization of location
E/MDM     ( 1733): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5508): 
,I/art     (  853): Explicit concurrent mark sweep GC freed 26404(1350KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.865ms total 149.762ms
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/NotificationManager(  853): android: cancelAsUser(2) by android
,I/ActivityManager(  853): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6306 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/qtaguid ( 6062): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6062): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6062): untagSocket(41) failed with errno -22
D/Finsky  ( 6062): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  853): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6327 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,W/ResourcesManager( 6327): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6327): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 6306): getAccountsCursor
I/MultiDex( 6327): VM with version 2.1.0 has multidex support
I/MultiDex( 6327): install
I/MultiDex( 6327): VM has multidex support, MultiDex support library is disabled.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6306): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/JNIHelp ( 6327): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6306): Error finding the version of the Email provider.....
E/Gmail   ( 6306): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6306): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6306): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6306): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6306): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6306): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6306): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6306): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6306): We do not support migrating this version of the Email provider.
I/Gmail   ( 6306): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 6327): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6327): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3437017e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6327): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6327): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6327): com.google.android.gms: cancel(39789) by com.google.android.gms
I/qtaguid ( 6062): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6062): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6062): untagSocket(41) failed with errno -22
,W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ChimeraCfgMgr( 6327): Reading stored module config
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6306): Observing account changes for notifications
,D/ChimeraCfgMgr( 6327): Loading module com.google.android.gms.car from APK com.google.android.gms
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1733): Explicit concurrent mark sweep GC freed 23185(1397KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 1.359ms total 99.596ms
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 95700962208; DSPS: 3228025; Offset : -2820275260
,D/CAR.SERVICE( 6327): Connecting to CarCallService...
,I/art     ( 6327): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6327): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6371 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/NativeLibraryUtils( 6327): Install completed successfully. count=14 extracted=0
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{2521f59a type 0 when 1454578913718 com.google.android.googlequicksearchbox} when 1454578913718
D/CAR.SERVICE( 6327): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6327): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6327): Creating a new PhoneAdapter instance
,I/Gmail   ( 6306): notifyAccountChanged
,I/Gmail   ( 6306): getAccountsCursor
I/Gmail   ( 6306): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6306): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6306): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  853): Process com.google.android.apps.plus (pid 6027) has died
I/Gmail   ( 6306): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6327): setListener: com.google.android.gms.car.dn@22c40e65
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.TEL.PhoneAdapter( 6327): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6327): Starting CarCallService with initial phone null
,I/NotificationManager( 6327): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 3991): Explicit concurrent mark sweep GC freed 2974(116KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 442us total 27.518ms
,I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5508): 
,W/ResourcesManager( 6371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6371): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6371): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6371): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6371): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 6062): CheckpointMarkThreadRoots callback created = 0xb0570440
I/art     ( 6062): CheckpointMarkThreadRoots callback created = 0xb0570410
,D/CAR.SERVICE( 6327): Package validated; name: com.android.vending
,I/NotificationManager( 6062): com.android.vending: cancel(10436) by com.android.vending
I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5508): 
,V/Finsky  ( 6062): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5508): 
I/IndexDatabaseHelper( 6371): Using schema version: 115
,I/IndexDatabaseHelper( 6371): Index is fine
I/Gmail   ( 6306): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5508): 
,I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5508): 
,I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5508): 
I/ActivityManager(  853): Process com.android.contacts (pid 5966) has died
,I/jxcore-log( 5508): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5508): 
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
I/ActivityManager(  853): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6400 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6400): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  853): Process com.lge.qremote (pid 6114) has died
I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6422 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6422): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2276cd97:true
D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
,D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
,V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6400): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6446 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/qtaguid ( 6062): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6062): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6062): untagSocket(41) failed with errno -22
,D/Finsky  ( 6062): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
D/Finsky  ( 6062): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
,I/ActivityManager(  853): Process com.uei.lg.quicksetsdk.lite (pid 6140) has died
,W/ResourcesManager( 6446): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6062): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6062): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6062): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6062): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{276fef25 type 0 when 1454578915598 com.android.vending} when 1454578915598
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/DeviceConnectionService( 1733): client connected with version: 8296000
,D/Finsky  ( 6062): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6062): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/Babel_SMS( 6446): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6446): MmsConfig.loadMmsSettings
I/Babel_SMS( 6446): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6446): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6446): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6446): MmsConfig.loadFromResources
E/Babel_SMS( 6446): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6446): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6446): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6446): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6446): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6446): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6446): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6446): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6446): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6446): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6446): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6446): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6446): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6446): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6446): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6446): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6446): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6446): found sensor: Motion Accel, handle=46
I/ActivityManager(  853): Process com.google.android.setupwizard (pid 6271) has died
,I/art     ( 6446): CheckpointMarkThreadRoots callback created = 0xaaf3d410
W/Settings( 6446): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6446): startup - clean
I/art     ( 6446): CheckpointMarkThreadRoots callback created = 0xaaf3d3f0
,I/Babel   ( 6446): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6400): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6446): Unsupported mime audio/x-lg-flac
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6446): Unsupported mime audio/adpcm
W/AudioCapabilities( 6446): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
W/AudioCapabilities( 6446): Unsupported mime audio/x-ms-wma
I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6400): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6446): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6446): Unsupported mime video/mjpg
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
W/VideoCapabilities( 6446): Unsupported mime video/theora
,W/AudioCapabilities( 6446): Unsupported mime audio/evrc
W/AudioCapabilities( 6446): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6446): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6446): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6446): Unsupported mime audio/qcelp
I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6480 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
W/AudioCapabilities( 6446): Unsupported mime audio/evrc
,W/VideoCapabilities( 6446): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6446): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6446): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6446): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6446): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6446): Unrecognized profile 2130706433 for video/avc
D/PhoneMonitor( 6480): Register our PhoneStateListener
,I/art     (  853): Explicit concurrent mark sweep GC freed 17218(827KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.181ms total 148.313ms
,I/vclib   ( 6446): onServiceConnected
W/Babel   ( 6446): Attempted to change video mute state without an active call.
I/ActivityManager(  853): Killing 5996:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/NotificationManager( 6446): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/PhoneMonitor( 6480): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6480): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6480): [parse] Load xml
V/TelephonyAutoProfiling( 6480): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6480): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6480): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_5996/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5675): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 19339
,I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6501 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5675): Checking schedule, now: 1454578916516 next: 1454578927114
I/CheckinService( 5675): active receiver: disabled
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 6501): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/CalendarApplication( 6501): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6501): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6501): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@62cd2e9, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@128efb6e, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1c90c20f, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2b5d629c, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@b76b4a5, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2933607a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@aa1702b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@232c0c88, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1ec2f621, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3e870a46, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3cc4e407, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1b96934, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@c37d35d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@d1984d2, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@26c1b9a3, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3e1de4a0, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2234859, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@36e71c1e, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@282c4cff, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@268caacc, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2bb71115, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2f64dc2a, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1b82ba1b, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@173fa7b8, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3b84a991, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3a4c90f6, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3b08dcf7, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@34238764, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@21b94dcd, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@b28c682, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@37645193, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1143b5d0, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2a19f9c9, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@11a0c8ce, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1bf873ef, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@35f65efc, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3dbf6985, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3e84a3da, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1d02600b, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@26c86ee8, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@4921901, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@d9923a6
D/GeneralP,referenceUtils( 6501): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6501): [init]
,I/Config  ( 6501): LGCalendar ver.4.40.17
I/Config  ( 6501): start check model
I/Config  ( 6501): start check native_ca
I/Config  ( 6501): Config Operator=OPEN, Country=EU
D/Config  ( 6501): [setDefaultValuesToPref]
D/Config  ( 6501): [parseProfiles]
D/ProfilesParser( 6501): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6501): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6501): [updateProfiletoCountryInfo]
D/GeneralPreference( 6501): [checkAndMigrateOldPreference]
D/AlertReceiver( 6501): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6501): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6501): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6501): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6501): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6501): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6501): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6501): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6501): onHandleIntent
,D/HolidayDataLoader( 6501): readJsonAsset : holiday.json
D/AlertService( 6501): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6501): [updateWidgets] 
D/MonthWidgetProvider( 6501): [onReceive]
D/CalendarWidgetProvider( 6501): [onReceive]
D/CalendarWidgetProvider( 6501): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6501): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6501): [onReceive]
D/CalendarWidgetProvider( 6501): [onReceive]
D/CalendarWidgetProvider( 6501): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6501): [onCreate] mContext.getPackageName() = com.android.calendar
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6371): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/HolidayIntentService( 6501): onHandleIntent:holiday data empty
D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6371): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6371): MCCMNC not supported: null
I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6535 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6422): Create singleton instance
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 21.287ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 20.758ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.081ms
,D/UEI.SmartControl( 6535): Quickset Services start...
,I/UEI.SmartControl( 6535): Manufacture = LGE
D/UEI.SmartControl( 6535): File observer start...
E/UEI.SmartControl( 6535): IR Port is disabled: false
D/UEI.SmartControl( 6535): Starting file observer...
D/UEI.SmartControl( 6535): Extracting JNI libs...
D/UEI.SmartControl( 6535): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6422): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6535): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6535): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6535): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6553 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UEI.SmartControl( 6535): --- Selecting new region: 2
,I/UEI.SmartControl( 6535): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6535): Platform has CIR...
D/UEI.SmartControl( 6535): NO CIR support, need to check package...
I/UEI.SmartControl( 6535): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6535): QS Service created
E/UEI.SmartControl( 6535): QS start get config
,D/UEI.SmartControl( 6535): Loading JNI Libs...
,D/UEI.SmartControl( 6535):  configuring local db...
I/ActivityManager(  853): Killing 6161:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,D/UEI.SmartControl( 6535):  ---- Has DB8: true
I/MusicStore( 6553): Database version: 120
,D/UEI.SmartControl( 6535): QS start statue = true Error code = 0
D/UEI.SmartControl( 6535): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6535): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6535): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6535): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6535): IrrcClient ++ 
D/irrcClient( 6535): getIrrcService ++ 
,D/irrcClient( 6535): getIrrcService -- 
D/irrcClient( 6535): IrrcClient -- 
W/irrc_jni( 6535): IRRCPlayer_nativeInit -- 
W/libprocessgroup(  853): failed to open /acct/uid_10009/pid_6161/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6535): Services init done
,I/UEI.SmartControl( 6535): Device manager: loading config....
D/UEI.SmartControl( 6535): QS Service init finished
D/UEI.SmartControl( 6535): QS Service version name: 0.1.73
D/UEI.SmartControl( 6535): QS Service version code: 1073
D/UEI.SmartControl( 6535): Service requested: Control
D/UEI.SmartControl( 6535): Config is loaded...
D/UEI.SmartControl( 6535):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6535): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6535): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6535): Internal service binding...
D/UEI.SmartControl( 6535): -----IControl: 11
,D/UEI.SmartControl( 6535): Caller: com.lge.qremote
D/UEI.SmartControl( 6535): ------------ IControl registerCallback...
I/UEI.SmartControl( 6535): Registering callback...
D/UEI.SmartControl( 6535): -----IControl: 19
D/UEI.SmartControl( 6535): Caller: com.lge.qremote
I/UEI.SmartControl( 6535): Registering Services Ready callback...
I/UEI.SmartControl( 6535): Notify client services are ready...
D/UEI.SmartControl( 6535): -----IControl: 8
,D/UEI.SmartControl( 6535): Caller: com.lge.qremote
I/ActivityManager(  853): Process com.android.vending (pid 6062) has died
,D/CAR.SERVICE( 6327): mConnectedToCar = false, abort
E/ActivityThread( 6327): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2675b6ad that was originally bound here
E/ActivityThread( 6327): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2675b6ad that was originally bound here
E/ActivityThread( 6327): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6327): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6327): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6327): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6327): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6327): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6327): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6327): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6327): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6327): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6327): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3a050b5c that was originally bound here
E/ActivityThread( 6327): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3a050b5c that was originally bound here
E/ActivityThread( 6327): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6327): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6327): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6327): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6327): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6327): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6327): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  853): Unbind failed: could not find connection for android.os.BinderProxy@3853df80
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6553): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6553): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6553): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6553): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6553): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6553): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GAv4-SVC( 5675): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 6306): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityThread( 6553): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6553): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1446cf51: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6553): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6553): GMSCore installation verified
I/ConfigStore( 6553): Config Database version: 1
,I/MediaRouter( 6553): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6553): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6553): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Killing 6197:com.google.android.configupdater/u0a3 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  853): failed to open /acct/uid_10003/pid_6197/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6553): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6592 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6553): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6553): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  853): Killing 6306:com.google.android.gm/u0a53 (adj 15): empty #11
,W/ResourcesManager( 6592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6592): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6592): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  853): failed to open /acct/uid_10053/pid_6306/cgroup.procs: No such file or directory
,I/NotificationManager( 6553): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6592): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6592): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6592): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6615 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6592): JNI_OnLoad()
I/HubEmail( 6592): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6592): registerNatives()
I/HubEmail( 6592): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6592): registerNativeMethods()
I/HubEmail( 6592): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6592): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  853): Killing 6327:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_6327/cgroup.procs: No such file or directory
W/Settings( 6592): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/LGDMClient( 6615): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6615): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6615): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6615): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6615): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6615): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6615): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6615): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6639 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6615): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6615): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6615): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6615): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6615): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6615): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  853): Killing 6446:com.google.android.talk/u0a61 (adj 15): empty #11
,W/PackageSettings(  853): Skipping PackageSetting{31a3b94e com.example.hello/10317} due to missing metadata
,W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_6446/cgroup.procs: No such file or directory
,D/WeatherService( 2679): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:42:0
,D/WeatherService( 2679): 2 : TimeTick Intent And Screen On
D/WeatherService( 2679): 2 : SDK version : 21
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2679): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
D/WeatherService( 2679): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2679): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2679): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2679): 2 : Fixed theme : optimus
D/WeatherReflect( 2679): 2 : Map key string is -2
,D/lim     ( 2679): 2 : time = 10:42
,I/WeatherReflect( 2679): Model Name : LG-D722
D/WeatherTheme( 2679): 2 : Different view - status_min_formatted : 41 != 42
D/WeatherTheme( 2679): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2679): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2679): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2679): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/AppUp4:AppBoxCP( 6639): onCreate
,W/AppUp4:DB( 6639):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6639):  setFingerPrint start
I/AppUp4:DB( 6639):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/Weather4x2_optimus( 2679): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2679): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2679): forecast size is 0
D/Theme   ( 2679): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2679): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2679): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2679): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2679): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2679): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/AppUp4:DB( 6639):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6639):  SDK version = 0
D/Theme_WeatherAncestor_optimus( 2679): setTouchIntent, appWidgetId: 2
I/AppUp4:DB( 6639):  beforefinger == newfinger no write in DB
D/Theme_WeatherAncestor_optimus( 2679): url is : null
D/AppUp4:AppBoxApplication( 6639): AppBoxApplication onCreate()
D/Theme   ( 2679): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2679): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2679): 2 : update view, appWidgetId: 2
I/NetworkStateForAutoUpdateMonitor( 6639): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6639): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
D/WeatherService( 2679): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:42:0
I/NetworkStateForAutoUpdateMonitor( 6639): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6639): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6639): onReceive
I/AppUp4:CustModeStarterReceiver( 6639): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6639): Context : android.app.ReceiverRestrictedContext@b76b4a5
D/AppUp4:CustFacade( 6639): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6639): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6639): begin check event
I/AppUp4:CustModeStarterReceiver( 6639): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6639): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6639): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6639): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6639): handleAsyncCustNotification do not startCustService
I/ActivityManager(  853): Killing 6371:com.android.settings/1000 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6371/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3224): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3224): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3224): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6480): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6480): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3255): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3255): DownloadService onCreate
,I/DownloadManager( 3255): in removeSpuriousFiles
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/NotificationManager( 3255): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6660 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@3437017e on behalf of 3255
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/DownloadManager( 3255): in trimDatabase
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@235436df on behalf of 3255
V/DownloadManager( 3255): DownloadService onStartCommand
,V/DownloadManager( 3255): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@4bdb78a on behalf of 3255
V/DownloadManager( 3255): DownloadService onDestroy
,I/ActivityManager(  853): Killing 6400:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6400/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2679): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:0
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
D/WeatherAncestor( 2679): connectivity changed - connection : true
D/Weather_cast( 2679): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2679): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:0
D/WeatherService( 2679): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6684 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6684): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6684): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6684): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6684): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6684): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6684): MmsConfig.loadFromResources
E/Babel_SMS( 6684): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6684): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6684): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6684): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6684): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6684): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6684): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6684): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6684): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6684): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6684): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6684): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6684): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6684): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6684): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6684): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6684): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6684): found sensor: Motion Accel, handle=46
,W/art     ( 6684): Suspending all threads took: 7.001ms
,W/Settings( 6684): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6684): startup - clean
,I/art     ( 6684): CheckpointMarkThreadRoots callback created = 0xb042d4c0
I/Babel   ( 6684): deleted: false for 0
,I/art     ( 6684): CheckpointMarkThreadRoots callback created = 0xb042d4a0
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6719 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/AudioCapabilities( 6684): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6684): Unsupported mime audio/adpcm
W/AudioCapabilities( 6684): Unsupported mime audio/g726
W/AudioCapabilities( 6684): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6684): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6684): Unsupported mime video/mjpg
W/VideoCapabilities( 6684): Unsupported mime video/theora
,W/AudioCapabilities( 6684): Unsupported mime audio/evrc
W/AudioCapabilities( 6684): Unsupported mime audio/qcelp
W/VideoCapabilities( 6684): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6684): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6684): Unsupported mime audio/qcelp
W/AudioCapabilities( 6684): Unsupported mime audio/evrc
W/VideoCapabilities( 6684): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6684): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6684): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6684): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6684): Unrecognized profile 2130706433 for video/avc
I/art     (  853): Explicit concurrent mark sweep GC freed 19158(1156KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.176ms total 150.298ms
,W/VideoCapabilities( 6684): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6684): onServiceConnected
,W/Babel   ( 6684): Attempted to change video mute state without an active call.
I/NotificationManager( 6684): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6684): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6684): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6684): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6684): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6684): propertyValue:false
I/Babel   ( 6684): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  853): Killing 6422:com.lge.qremote/u0a106 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_6422/cgroup.procs: No such file or directory
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  853): Process com.google.android.gms (pid 5675) has died
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6719): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6719):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6719):   adb logcat -s GAv4
,W/GAv4    ( 6719): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6719): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6719): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/AlertService( 6501): Beginning updateAlertNotification
,I/ActivityManager(  853): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6766 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6766): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6784 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/CalendarProvider2( 6766): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@153dfdb3
D/CalendarProvider2( 6766): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6766): Created com.android.providers.calendar.CalendarAlarmManager@2b5d629c(com.android.providers.calendar.CalendarProvider2@153dfdb3)
I/WebViewFactory( 6719): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/AlertService( 6501): No fired or scheduled alerts
I/NotificationManager( 6501): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6501): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(4) by com.android.calendar
,I/NotificationManager( 6501): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6501): com.android.calendar: cancel(20) by com.android.calendar
W/ResourcesManager( 6784): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6784): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AlertService( 6501): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/LibraryLoader( 6719): Time to load native libraries: 2 ms (timestamps 4448-4450)
I/LibraryLoader( 6719): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6719): Binding Chromium to main looper Looper (main, tid 1) {4e4c62e}
I/LibraryLoader( 6719): Expected native library version number "",actual native library version number ""
,I/chromium( 6719): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/AlarmScheduler( 6501): No events found starting within 1 week.
I/BrowserStartupController( 6719): Initializing chromium process, singleProcess=true
W/art     ( 6719): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6719): ApplicationContext is null in ApplicationStatus
,I/MultiDex( 6784): VM with version 2.1.0 has multidex support
I/MultiDex( 6784): install
I/MultiDex( 6784): VM has multidex support, MultiDex support library is disabled.
W/chromium( 6719): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6719): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6719): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6719): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6719): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6719): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6719): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6719): Remote Branch: 
I/Adreno-EGL( 6719): Local Patches: 
I/Adreno-EGL( 6719): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb57e6560, uid 10079
,W/AudioManagerAndroid( 6719): Requires BLUETOOTH permission
I/NSApplication( 6719): Starting up...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6826 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6535:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/ActivityManager(  853): Killing 6501:com.android.calendar/u0a13 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_6535/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_6501/cgroup.procs: No such file or directory
V/JNIHelp ( 6784): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6784): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6784): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f1569f4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6784): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6784): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6784): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  853): Killing 6553:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_6553/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 6784): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6867 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6592:com.lge.email/u0a21 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.213ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.557ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.952ms
,W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_6592/cgroup.procs: No such file or directory
,W/ResourcesManager( 6867): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5508): Test app app.js loaded
I/jxcore-log( 5508): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5508): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa3e521 added. We now have 1 listener(s)
D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
I/jxcore-log( 5508): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5508): 
I/chromium( 5508): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/iu.SyncManager( 6784): SYNC; picasa accounts
,D/NetworkLogImpl( 6784): Loaded NetworkSpeedPredictor
I/iu.Environment( 6784): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  853): Killing 6615:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 6784): num queued entries: 0
I/iu.UploadsManager( 6784): num updated entries: 0
I/iu.SyncManager( 6784): NEXT; no task
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6615/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6904 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6904): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6904): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6904): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6904): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6904): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6904): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6904): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6904): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6904): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1446cf51: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6904): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6904): GMSCore installation verified
I/ConfigStore( 6904): Config Database version: 1
,I/MediaRouter( 6904): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6904): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6904): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6904): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6935 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6904): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6904): Using platform SSLCertificateSocketFactory
I/ActivityManager(  853): Killing 6639:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6935): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6935): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6935): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_6639/cgroup.procs: No such file or directory
,I/NotificationManager( 6904): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6935): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6935): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6935): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6958 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6935): JNI_OnLoad()
I/HubEmail( 6935): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6935): registerNatives()
I/HubEmail( 6935): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6935): registerNativeMethods()
I/HubEmail( 6935): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6935): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  853): Killing 6480:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_6480/cgroup.procs: No such file or directory
,W/Settings( 6935): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6958): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6958): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6958): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6958): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6958): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6958): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6982 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6958): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6958): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6958): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6958): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6958): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  853): Killing 6660:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6982): onCreate
,W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_6660/cgroup.procs: No such file or directory
,W/AppUp4:DB( 6982):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6982):  setFingerPrint start
I/AppUp4:DB( 6982):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6982):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6982):  SDK version = 0
I/AppUp4:DB( 6982):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6982): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6982): onReceive
,I/AppUp4:CustModeStarterReceiver( 6982): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6982): Context : android.app.ReceiverRestrictedContext@b76b4a5
D/AppUp4:CustFacade( 6982): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6982): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6982): begin check event
I/AppUp4:CustModeStarterReceiver( 6982): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6982): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6982): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6982): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6982): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  853): Killing 6684:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_6684/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3224): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3224): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3224): networkInfo.isConnected() = false
I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7011 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7011): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7011): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7011): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  853): Killing 6719:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
V/DownloadManager( 3255): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  853): failed to open /acct/uid_10079/pid_6719/cgroup.procs: No such file or directory
V/DownloadManager( 3255): DownloadService onCreate
I/DownloadManager( 3255): in removeSpuriousFiles
I/NotificationManager( 3255): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7039 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/PhoneMonitor( 7011): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7011): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7011): [parse] Load xml
,V/TelephonyAutoProfiling( 7011): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7011): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7011): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     (  853): Explicit concurrent mark sweep GC freed 18670(908KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.922ms total 157.853ms
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@32524471 on behalf of 3255
I/DownloadManager( 3255): in trimDatabase
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3255): DownloadService onStartCommand
V/DownloadManager( 3255): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@264822d7 on behalf of 3255
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@109e87c4 on behalf of 3255
I/CheckinService( 6784): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 29413
,I/CheckinService( 6784): Disabling old GoogleServicesFramework version
,D/WeatherAncestor( 2679): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:6
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
D/WeatherAncestor( 2679): connectivity changed - connection : true
D/Weather_cast( 2679): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2679): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:6
D/WeatherService( 2679): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7071 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3255): DownloadService onDestroy
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinService( 6784): Checking schedule, now: 1454578926658 next: 1454578927114
I/CheckinService( 6784): active receiver: disabled
,W/ResourcesManager( 7071): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Killing 6766:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_6766/cgroup.procs: No such file or directory
,I/Babel_SMS( 7071): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7071): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7071): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7071): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7071): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7071): MmsConfig.loadFromResources
E/Babel_SMS( 7071): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7071): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7071): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7071): found sensor: LGE Magnetometer Sensor, handle=10
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
W/Settings( 7071): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7071): startup - clean
,I/art     ( 7071): CheckpointMarkThreadRoots callback created = 0xb042d920
,I/Babel   ( 7071): deleted: false for 0
I/art     ( 7071): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7101 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7071): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7071): Unsupported mime audio/adpcm
W/AudioCapabilities( 7071): Unsupported mime audio/g726
W/AudioCapabilities( 7071): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7071): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7071): Unsupported mime video/mjpg
W/VideoCapabilities( 7071): Unsupported mime video/theora
,W/AudioCapabilities( 7071): Unsupported mime audio/evrc
W/AudioCapabilities( 7071): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7071): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7071): Unsupported mime audio/qcelp
W/AudioCapabilities( 7071): Unsupported mime audio/evrc
W/VideoCapabilities( 7071): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7071): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7071): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7071): onServiceConnected
W/Babel   ( 7071): Attempted to change video mute state without an active call.
I/NotificationManager( 7071): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7071): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7071): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7071): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7071): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 7071): propertyValue:false
I/Babel   ( 7071): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  853): Killing 6826:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_6826/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7101): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7101): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7101): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7101): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7101): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7101):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7101):   adb logcat -s GAv4
,W/GAv4    ( 7101): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7101): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7101): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7101): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7101): Time to load native libraries: 1 ms (timestamps 45-46)
I/LibraryLoader( 7101): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7101): Binding Chromium to main looper Looper (main, tid 1) {4e4c62e}
I/LibraryLoader( 7101): Expected native library version number "",actual native library version number ""
I/chromium( 7101): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7101): Initializing chromium process, singleProcess=true
,W/art     ( 7101): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7101): ApplicationContext is null in ApplicationStatus
W/chromium( 7101): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7101): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7101): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7101): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7101): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7101): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7101): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7101): Remote Branch: 
I/Adreno-EGL( 7101): Local Patches: 
I/Adreno-EGL( 7101): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb57e6580, uid 10079
,W/AudioManagerAndroid( 7101): Requires BLUETOOTH permission
I/NSApplication( 7101): Starting up...
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7173 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6867:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_6867/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7192 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6904:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_6904/cgroup.procs: No such file or directory
,W/ResourcesManager( 7192): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Killing 6935:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_6935/cgroup.procs: No such file or directory
,I/AppUp4:CustModeStarterReceiver( 6982): onReceive
I/AppUp4:CustModeStarterReceiver( 6982): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6982): Context : android.app.ReceiverRestrictedContext@b76b4a5
D/AppUp4:CustFacade( 6982): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6982): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6982): begin check event
I/AppUp4:CustModeStarterReceiver( 6982): Event For Nothing, skip.
I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7218 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 320us total 24.746ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.148ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 23.373ms
W/ResourcesManager( 7218): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7218): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7218): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationManager( 7071): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7071): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7071): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7071): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7218): Total System Memory = 906309632
,I/GalleryUtils( 7218): Application Heap = 96 MB
I/AppConfig( 7218): App Tier : NOT_DEF
D/SystemHelper( 7218): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7248 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7248): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7248): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7248): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7248): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7248): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7248): BUILD Country: EU
I/SystemConfig( 7248): BUILD Operator: OPEN
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7274 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6958:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6958/cgroup.procs: No such file or directory
I/SystemConfig( 7248): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7248): existFile = false
I/SystemConfig( 7248): canReadFile = false
I/SystemConfig( 7248): systemFeature RCS result false
D/SystemConfig( 7248): refreshRcsSupport() :false
I/LockScreenSettings( 7274): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7274): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7274): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7274): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7274): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7274): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  853): Killing 7011:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 67 ms] updated apps [took 66 ms] 
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7295 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{39ec8162 type 0 when 1454578927114 com.google.android.gms} when 1454578927114
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{2ceb22f3 type 0 when 1454578929569 com.android.vending} when 1454578929569
W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7011/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 7295): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7295): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7295): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7295): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7295): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Ads     ( 7295): Skipping gmscore version check
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@3495ade2 on behalf of 7295
D/Finsky  ( 7295): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7295): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 6784): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  853): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7336 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7295): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/PackageBroadcastService( 6784): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7295): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7336): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 7336): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@153dfdb3
,D/CalendarProvider2( 7336): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7336): Created com.android.providers.calendar.CalendarAlarmManager@2b5d629c(com.android.providers.calendar.CalendarProvider2@153dfdb3)
D/CalendarProviderBroadcastReceiver( 7336): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7336): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 7336): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7336): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7336): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7373 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6784): Storage manager: low false usage 1.70MB avail 2.38GB capacity 4.06GB
,D/CalendarProvider2( 7336): [IntentService] Release Lock
D/CalendarProvider2( 7336): CalendarProviderIntentService.onDestroy()
D/Finsky  ( 7295): [915] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7295): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  853): Killing 7039:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_7039/cgroup.procs: No such file or directory
,I/MusicStore( 7373): Database version: 120
,I/art     ( 6784): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6784): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7373): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     (  853): Explicit concurrent mark sweep GC freed 24718(1150KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.604ms total 148.377ms
,I/ActivityManager(  853): Process com.google.android.apps.magazines (pid 7101) has died
,I/Icing   ( 6784): updateResources: need to parse f{com.google.android.gms}
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7373): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7373): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7373): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7373): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7373): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 6784): Internal init done: storage state 0
,I/NotificationManager( 6784): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 6784): Post-init done
I/Icing   ( 6784): updateResources: need to parse f{com.google.android.gms}
W/ActivityThread( 7373): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7373): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1446cf51: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7373): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7373): GMSCore installation verified
,I/ConfigStore( 7373): Config Database version: 1
,I/MediaRouter( 7373): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7373): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7373): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7373): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7421 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/GHttpClientFactory( 7373): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7373): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/NotificationManager( 7373): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 7421): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7421): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7421): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7451 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7421): JNI_OnLoad()
I/HubEmail( 7421): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7421): registerNatives()
I/HubEmail( 7421): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7421): registerNativeMethods()
I/HubEmail( 7421): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7421): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  853): Killing 7173:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_7173/cgroup.procs: No such file or directory
,W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7451): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7451): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6982): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6982): onReceive
I/AppUp4:CustModeStarterReceiver( 6982): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6982): Context : android.app.ReceiverRestrictedContext@b76b4a5
D/AppUp4:CustFacade( 6982): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6982): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6982): begin check event
I/AppUp4:CustModeStarterReceiver( 6982): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3224): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3224): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3224): networkInfo.isConnected() = true
D/PhoneState( 3224): setPdpRejectCasuse : false
D/LGDMClient( 7451): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7451): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7451): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7451): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7475 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7451): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7451): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7451): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7451): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7451): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  853): Killing 7218:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_7218/cgroup.procs: No such file or directory
,I/Icing   ( 6784): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 6784): Loaded CLD2 Version V2.0 - 20141016
,D/PhoneMonitor( 7475): Register our PhoneStateListener
I/Icing   ( 6784): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/MobileConnectivityChangeReceiver( 7475): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7475): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  853): Killing 7248:com.android.contacts/u0a18 (adj 15): empty #11
D/PhoneMonitor( 7475): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,W/libprocessgroup(  853): failed to open /acct/uid_10018/pid_7248/cgroup.procs: No such file or directory
,V/DownloadManager( 3255): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/TelephonyAutoProfiling( 7475): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7475): [parse] Load xml
V/DownloadManager( 3255): DownloadService onCreate
I/ActivityManager(  853): Killing 7274:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/DownloadManager( 3255): in removeSpuriousFiles
V/TelephonyAutoProfiling( 7475): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7475): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/NotificationManager( 3255): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@1d821573 on behalf of 3255
,I/DownloadManager( 3255): in trimDatabase
D/PhoneMonitor( 7475): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@27e410a9 on behalf of 3255
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7502 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_7274/cgroup.procs: No such file or directory
V/DownloadManager( 3255): DownloadService onStartCommand
V/DownloadManager( 3255): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@3f5e95cf on behalf of 3255
I/CheckinService( 6784): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 35551
,I/CheckinService( 6784): Checking schedule, now: 1454578932710 next: 1454578927114
I/CheckinService( 6784): active receiver: enabled
,V/DownloadManager( 3255): DownloadService onDestroy
I/CheckinService( 6784): Preparing to send checkin request
I/EventLogService( 6784): Accumulating logs since 1454578887942
,D/WeatherAncestor( 2679): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:12
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
D/WeatherAncestor( 2679): connectivity changed - connection : true
D/Weather_cast( 2679): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2679): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:12
D/WeatherService( 2679): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     ( 3991): Explicit concurrent mark sweep GC freed 2217(82KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 413us total 33.586ms
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7523 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6784): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6784): Failed to find provider info for com.google.android.wearable.settings
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7523): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7523):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7523):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7523): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7523): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAv4    ( 7523): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  853): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7553 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 21.815ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.037ms
W/ResourcesManager( 7553): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7553): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.820ms
I/MultiDex( 7553): VM with version 2.1.0 has multidex support
I/MultiDex( 7553): install
I/MultiDex( 7553): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7553): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WebViewFactory( 7523): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7523): Time to load native libraries: 2 ms (timestamps 5547-5549)
I/LibraryLoader( 7523): Expected native library version number "",actual native library version number ""
W/ActivityThread( 7553): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7553): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3437017e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7553): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7553): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7553): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WebViewChromiumFactoryProvider( 7523): Binding Chromium to main looper Looper (main, tid 1) {4e4c62e}
I/LibraryLoader( 7523): Expected native library version number "",actual native library version number ""
I/chromium( 7523): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7523): Initializing chromium process, singleProcess=true
,W/art     ( 7523): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7523): ApplicationContext is null in ApplicationStatus
I/art     ( 7553): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7553): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/chromium( 7523): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7523): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7523): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7523): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7523): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7523): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7523): Remote Branch: 
I/Adreno-EGL( 7523): Local Patches: 
I/Adreno-EGL( 7523): Reconstruct Branch: 
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 115701698400; DSPS: 3883409; Offset : -2820268912
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AudioPolicyService(  281): registerClient() client 0xb57e65a0, uid 10079
W/AudioManagerAndroid( 7523): Requires BLUETOOTH permission
,I/NSApplication( 7523): Starting up...
,D/WVCdm   (  281): Instantiating CDM.
D/NativeLibraryUtils( 7553): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  281): CdmEngine::OpenSession
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7611 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7192:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=1695394187
I/art     ( 7553): CheckpointMarkThreadRoots callback created = 0xb042d550
W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_7192/cgroup.procs: No such file or directory
,I/art     ( 7553): CheckpointMarkThreadRoots callback created = 0xb042d530
,I/MusicWidget( 2576): mDelayedStopHandler : unbind
,I/art     (  853): Explicit concurrent mark sweep GC freed 15069(729KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.856ms total 162.833ms
,I/ActivityManager(  853): Killing 7295:com.android.vending/u0a36 (adj 15): empty #11
I/MusicBrowser( 2691): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2691): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2691): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2691): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2691): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2691): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
W/libprocessgroup(  853): failed to open /acct/uid_10036/pid_7295/cgroup.procs: No such file or directory
,I/MusicBrowser( 2691): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  853):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2f64dc2acom.lge.music.MediaPlaybackService$6@1b82ba1b
,D/MusicBrowser( 2691): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7633 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 7336:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/dex2oat ( 7630): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_7336/cgroup.procs: No such file or directory
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1ec2f621
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,W/ResourcesManager( 7633): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/MusicBrowser( 2691): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/dex2oat ( 7630): dex2oat took 102.387ms (threads: 4)
I/MusicBrowser( 2691): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
,I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2691): [MediaPlaybackService.java:6745:release()] oooooo 
I/Adreno-EGL( 7553): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7553): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7553): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7553): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7553): Remote Branch: 
I/Adreno-EGL( 7553): Local Patches: 
I/Adreno-EGL( 7553): Reconstruct Branch: 
I/MusicBrowser( 2691): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2691): reset
V/MediaPlayer[Native]( 2691): setListener
V/MediaPlayer[Native]( 2691): disconnect
V/MediaPlayer[Native]( 2691): destructor
,V/AudioFlinger(  281): releasing 19 from 2691 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2691): disconnect
D/MusicBrowser( 2691): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2691): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2691): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2691): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2691): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2691): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2691): [SmartShareManagerClient] unregisterListener: 390047672
W/SmartShareClient( 2691): [SmartShareManagerClient] unregisterListener invalid listener: 390047672
I/SmartShareClient( 2691): [SmartShareManagerClient] terminate service: 2691/MediaPlaybackService/479248911
E/HomeCloudIF( 2691): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2691): [SmartShareManagerClient] unbindService context:android.app.Application@3b84a991
,V/CloudHub( 2691): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2691): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2691): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2691): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2691): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  853): Killing 7373:com.google.android.music:main/u0a81 (adj 15): empty #11
I/CloudHub( 2691): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29973
,W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_7373/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  853): Killing 7421:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_7421/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7662 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7662): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af3dc89:true
,D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
D/BluetoothAdapterService(590089352)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36e71c1e
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7683 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7662): Create singleton instance
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/UEI.SmartControl( 7683): Quickset Services start...
I/UEI.SmartControl( 7683): Manufacture = LGE
D/UEI.SmartControl( 7683): File observer start...
E/UEI.SmartControl( 7683): IR Port is disabled: false
D/UEI.SmartControl( 7683): Starting file observer...
,D/UEI.SmartControl( 7683): Extracting JNI libs...
D/UEI.SmartControl( 7683): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7662): getMode name:com.lge.qremote
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 7662): getMode name:com.lge.qremote
I/ActivityManager(  853): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7709 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7683): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7683): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7683): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7683): --- Selecting new region: 2
,I/UEI.SmartControl( 7683): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7683): Platform has CIR...
,D/UEI.SmartControl( 7683): NO CIR support, need to check package...
I/UEI.SmartControl( 7683): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7683): QS Service created
,E/UEI.SmartControl( 7683): QS start get config
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 7683): Loading JNI Libs...
D/UEI.SmartControl( 7683):  configuring local db...
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7709): getAccountsCursor
,D/UEI.SmartControl( 7683):  ---- Has DB8: true
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7683): QS start statue = true Error code = 0
D/UEI.SmartControl( 7683): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7683): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7683): IRRCDataComm has AudioManager!!!!.
,W/GAV2    ( 7709): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/irrc_jni( 7683): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7683): IrrcClient ++ 
D/irrcClient( 7683): getIrrcService ++ 
D/irrcClient( 7683): getIrrcService -- 
D/irrcClient( 7683): IrrcClient -- 
W/irrc_jni( 7683): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7683): Services init done
I/UEI.SmartControl( 7683): Device manager: loading config....
D/UEI.SmartControl( 7683): QS Service init finished
D/UEI.SmartControl( 7683): QS Service version name: 0.1.73
D/UEI.SmartControl( 7683): QS Service version code: 1073
D/UEI.SmartControl( 7683): Service requested: Control
,D/UEI.SmartControl( 7683): Config is loaded...
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7709): Error finding the version of the Email provider.....
E/Gmail   ( 7709): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7709): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7709): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7709): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7709): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7709): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7709): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7709): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7709): getAccountsCursor
D/UEI.SmartControl( 7683):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7683): Notify AllClients services are ready: 0
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7683): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7683): Internal service binding...
D/UEI.SmartControl( 7683): -----IControl: 11
D/UEI.SmartControl( 7683): Caller: com.lge.qremote
,D/UEI.SmartControl( 7683): ------------ IControl registerCallback...
I/UEI.SmartControl( 7683): Registering callback...
D/UEI.SmartControl( 7683): -----IControl: 19
D/UEI.SmartControl( 7683): Caller: com.lge.qremote
I/UEI.SmartControl( 7683): Registering Services Ready callback...
I/UEI.SmartControl( 7683): Notify client services are ready...
D/UEI.SmartControl( 7683): -----IControl: 8
I/ActivityManager(  853): Killing 6982:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7683): Caller: com.lge.qremote
I/WVCdm   (  281): CdmEngine::CloseSession
,W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_6982/cgroup.procs: No such file or directory
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  853): Killing 7502:com.lge.drmservice/u0a51 (adj 15): empty #11
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  281): PrepareKeyRequest: nonce=1807046128
I/Gmail   ( 7709): Observing account changes for notifications
I/ActivityManager(  853): Killing 7451:com.lge.lgdmsclient/1000 (adj 15): empty #12
,I/Gmail   ( 7709): notifyAccountChanged
,I/Gmail   ( 7709): getAccountsCursor
I/Gmail   ( 7709): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7709): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7709): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7709): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_7502/cgroup.procs: No such file or directory
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7451/cgroup.procs: No such file or directory
D/WearableService( 1733): callingUid 10006, callindPid: 1733
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1733): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6784): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7662): getMode name:com.lge.qremote
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7761 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/SQLiteConnectionPool( 6784): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/IcingInternalCorpora( 6784): getNumBytesRead when not calculated.
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/Gmail   ( 7709): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7761): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7761): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7761): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7761): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7761): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 7761): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7761): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7761): Skipping gmscore version check
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7662): getMode name:com.lge.qremote
,D/Finsky  ( 7761): [988] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
E/MDM     ( 1733): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6784): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/NotificationManager(  853): android: cancelAsUser(2) by android
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 6784): Checkin interval check for package: unspecified last checkin: 1454578897150 min interval config: 0 actual interval: 40037
,I/art     (  853): Explicit concurrent mark sweep GC freed 23031(1046KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.437ms total 200.910ms
,D/LocationInitializer( 6784): Restart initialization of location
E/MDM     ( 1733): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/ContextImpl( 3616): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@22c40e65 on behalf of 7761
I/AudioManager( 7662): getMode name:com.lge.qremote
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 7662): getMode name:com.lge.qremote
,D/Finsky  ( 7761): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/AudioManager( 7662): getMode name:com.lge.qremote
D/libc-netbsd( 7761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/Finsky  ( 7761): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/AudioManager( 7662): getMode name:com.lge.qremote
,I/AudioManager( 7662): getMode name:com.lge.qremote
I/AudioManager( 7662): getMode name:com.lge.qremote
I/AudioManager( 7662): getMode name:com.lge.qremote
,I/AudioManager( 7662): getMode name:com.lge.qremote
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/AudioManager( 7662): getMode name:com.lge.qremote
,I/System.out( 7761): propertyValue:false
I/ActivityManager(  853): Killing 7523:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  853): failed to open /acct/uid_10079/pid_7523/cgroup.procs: No such file or directory
,I/WVCdm   (  281): CdmEngine::CloseSession
,I/WVCdm   (  281): L3 Terminate.
I/Adreno-EGL( 7553): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7553): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7553): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7553): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7553): Remote Branch: 
I/Adreno-EGL( 7553): Local Patches: 
I/Adreno-EGL( 7553): Reconstruct Branch: 
,I/Adreno-EGL( 7553): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7553): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7553): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7553): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7553): Remote Branch: 
I/Adreno-EGL( 7553): Local Patches: 
I/Adreno-EGL( 7553): Reconstruct Branch: 
,I/CheckinRequestBuilder( 6784): Classify the device as Phone.
,D/libc-netbsd( 6784): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6784): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6784): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6784): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6784): propertyValue:false
D/libc-netbsd( 6784): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6784): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6784): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6784): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6784): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6784): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 6784): Sending checkin request (9808 bytes)
,I/CheckinRequestBuilder( 6784): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6784): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6784): Classify the device as Phone.
,I/CheckinTask( 6784): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6784): Checking schedule, now: 1454578939355 next: 1455106188350
I/CheckinService( 6784): active receiver: disabled
,I/CheckinService( 6784): Checking schedule, now: 1454578939398 next: 1455106188350
I/CheckinService( 6784): active receiver: disabled
,D/CheckinService( 6784): Recording last checkin time for package unspecified as 1454578939410
V/SetupWizard( 7475): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7683): Internal timer expired: 1
,I/art     ( 3991): Explicit concurrent mark sweep GC freed 3422(141KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.033ms total 32.244ms
,I/GAv4-SVC( 6784): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 7709): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  853): Killing 2691:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  281): 2691 died, releasing its sessions
V/AudioFlinger(  281):  pid 1752 @ 0
V/AudioFlinger(  281):  pid 3224 @ 1
V/AudioFlinger(  281):  pid 3224 @ 2
,I/ActivityManager(  853): Killing 7611:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_10028/pid_2691/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_7611/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/NotificationManager( 7071): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7889 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  853): Handling package changes for user 0
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7889): onCreate
W/AppUp4:DB( 7889):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7889):  setFingerPrint start
I/AppUp4:DB( 7889):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7889):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7889):  SDK version = 0
I/AppUp4:DB( 7889):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7889): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7889): onReceive
I/AppUp4:CustModeStarterReceiver( 7889): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7889): Context : android.app.ReceiverRestrictedContext@128efb6e
,D/AppUp4:CustFacade( 7889): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7889): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7889): begin check event
I/AppUp4:CustModeStarterReceiver( 7889): Event For Nothing, skip.
I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7911 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7911): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7911): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7911): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@19918ee9
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,I/AppConfig( 7911): Total System Memory = 906309632
,I/GalleryUtils( 7911): Application Heap = 96 MB
I/AppConfig( 7911): App Tier : NOT_DEF
D/SystemHelper( 7911): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7931 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  853): Killing 7633:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_7633/cgroup.procs: No such file or directory
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7931): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7931): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  853): applying state to connected service
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  853): Process com.android.vending (pid 7761) has died
I/SystemConfig( 7931): BUILD Country: EU
I/SystemConfig( 7931): BUILD Operator: OPEN
,I/SystemConfig( 7931): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7931): existFile = false
I/SystemConfig( 7931): canReadFile = false
I/SystemConfig( 7931): systemFeature RCS result false
D/SystemConfig( 7931): refreshRcsSupport() :false
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7955 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 7955): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7955): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7955): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7955): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7955): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7955): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7975 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7709:com.google.android.gm/u0a53 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 36.943ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 28.514ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.637ms
,W/libprocessgroup(  853): failed to open /acct/uid_10053/pid_7709/cgroup.procs: No such file or directory
W/ResourcesManager( 7975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8014 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
,I/ActivityManager(  853): Killing 7475:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7475/cgroup.procs: No such file or directory
,D/Finsky  ( 8014): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8014): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8014): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8014): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 8014): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 8014): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8014): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@10fb173a on behalf of 8014
D/Ads     ( 8014): Skipping gmscore version check
,I/ActivityManager(  853): Killing 7683:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7662): android.os.DeadObjectException
,W/System.err( 7662): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7662): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7662): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7662): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7662): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7662): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7662): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7662): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7662): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7662): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7662): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7662): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7662): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7662): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7662): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7662): android.os.DeadObjectException
W/System.err( 7662): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7662): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7662): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7662): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7662): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7662): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7662): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7662): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7662): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7662): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7662): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7662): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7662): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7662): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7662): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_7683/cgroup.procs: No such file or directory
,W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/PackageBroadcastService( 6784): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8057 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 6784): Null package name or gms related package.  Ignoreing.
,D/charger_monitor(  486): init target 500000
D/Finsky  ( 8014): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/art     (  853): Explicit concurrent mark sweep GC freed 29918(1533KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.286ms total 184.283ms
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 8057): Quickset Services start...
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/UEI.SmartControl( 8057): Manufacture = LGE
D/WifiController(  853): battery changed pluggedType: 2
,D/UEI.SmartControl( 8057): File observer start...
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
E/UEI.SmartControl( 8057): IR Port is disabled: false
D/UEI.SmartControl( 8057): Starting file observer...
D/UEI.SmartControl( 8057): Extracting JNI libs...
D/UEI.SmartControl( 8057): --- this system supports 32-bit or 64-bit only
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
I/Icing   ( 6784): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8014): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/UEI.SmartControl( 8057): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8057): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8057): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/UEI.SmartControl( 8057): --- Selecting new region: 2
I/UEI.SmartControl( 8057): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8057): Platform has CIR...
D/UEI.SmartControl( 8057): NO CIR support, need to check package...
,I/UEI.SmartControl( 8057): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8057): QS Service created
E/UEI.SmartControl( 8057): QS start get config
,D/UEI.SmartControl( 8057): Loading JNI Libs...
,D/UEI.SmartControl( 8057):  configuring local db...
,D/UEI.SmartControl( 8057):  ---- Has DB8: true
,D/UEI.SmartControl( 8057): QS start statue = true Error code = 0
D/UEI.SmartControl( 8057): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8057): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8057): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8057): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8057): IrrcClient ++ 
D/irrcClient( 8057): getIrrcService ++ 
D/irrcClient( 8057): getIrrcService -- 
D/irrcClient( 8057): IrrcClient -- 
W/irrc_jni( 8057): IRRCPlayer_nativeInit -- 
I/UEI.SmartControl( 8057): Device manager: loading config....
D/UEI.SmartControl( 8057): Services init done
,D/UEI.SmartControl( 8057): QS Service init finished
D/UEI.SmartControl( 8057): QS Service version name: 0.1.73
D/UEI.SmartControl( 8057): QS Service version code: 1073
D/UEI.SmartControl( 8057): Config is loaded...
D/UEI.SmartControl( 8057): Service requested: Control
D/UEI.SmartControl( 8057): Internal service binding...
D/UEI.SmartControl( 8057): -----IControl: 11
,D/UEI.SmartControl( 8057): Caller: com.lge.qremote
D/UEI.SmartControl( 8057): ------------ IControl registerCallback...
I/UEI.SmartControl( 8057): Registering callback...
D/UEI.SmartControl( 8057): -----IControl: 19
D/UEI.SmartControl( 8057): Caller: com.lge.qremote
I/UEI.SmartControl( 8057): Registering Services Ready callback...
I/UEI.SmartControl( 8057): Notify client services are ready...
D/UEI.SmartControl( 8057): -----IControl: 8
D/UEI.SmartControl( 8057): Caller: com.lge.qremote
I/AudioManager( 7662): getMode name:com.lge.qremote
,I/AudioManager( 7662): getMode name:com.lge.qremote
I/AudioManager( 7662): getMode name:com.lge.qremote
,D/UEI.SmartControl( 8057):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8057): Notify AllClients services are ready: 0
I/Icing   ( 6784): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 6784): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  853): Killing 7553:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_7553/cgroup.procs: No such file or directory
,I/CheckinService( 6784): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  853): Killing 7071:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_7071/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/UEI.SmartControl( 8057): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 135702452246; DSPS: 4538794; Offset : -2820280481
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{c1a4e56 type 2 when 147521 com.google.android.gms} when 147521
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1454578965703 tag=VacuumService
,W/InstanceID/Rpc( 6784): Found 10006
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29061 ms ago)
,D/qdlights(  853): set_light_backlight: 253
,D/qdlights(  853): set_light_backlight: 250
D/qdlights(  853): set_light_backlight: 246
,D/qdlights(  853): set_light_backlight: 243
,D/qdlights(  853): set_light_backlight: 240
,D/qdlights(  853): set_light_backlight: 236
,D/qdlights(  853): set_light_backlight: 233
,D/qdlights(  853): set_light_backlight: 230
,D/qdlights(  853): set_light_backlight: 226
,D/qdlights(  853): set_light_backlight: 223
,D/qdlights(  853): set_light_backlight: 220
,D/qdlights(  853): set_light_backlight: 216
,D/qdlights(  853): set_light_backlight: 213
,D/qdlights(  853): set_light_backlight: 210
,D/qdlights(  853): set_light_backlight: 206
,D/qdlights(  853): set_light_backlight: 203
,D/qdlights(  853): set_light_backlight: 200
,D/qdlights(  853): set_light_backlight: 196
,D/qdlights(  853): set_light_backlight: 193
,D/qdlights(  853): set_light_backlight: 190
,D/qdlights(  853): set_light_backlight: 186
,D/qdlights(  853): set_light_backlight: 183
,D/qdlights(  853): set_light_backlight: 180
,D/qdlights(  853): set_light_backlight: 176
,D/qdlights(  853): set_light_backlight: 173
,D/qdlights(  853): set_light_backlight: 170
,D/qdlights(  853): set_light_backlight: 166
,D/qdlights(  853): set_light_backlight: 163
,D/qdlights(  853): set_light_backlight: 160
,D/qdlights(  853): set_light_backlight: 156
,D/qdlights(  853): set_light_backlight: 153
,D/qdlights(  853): set_light_backlight: 150
,D/qdlights(  853): set_light_backlight: 146
,D/qdlights(  853): set_light_backlight: 143
,D/qdlights(  853): set_light_backlight: 140
,D/qdlights(  853): set_light_backlight: 136
,D/qdlights(  853): set_light_backlight: 133
,D/qdlights(  853): set_light_backlight: 130
,D/qdlights(  853): set_light_backlight: 126
,D/qdlights(  853): set_light_backlight: 123
,D/qdlights(  853): set_light_backlight: 120
,D/qdlights(  853): set_light_backlight: 116
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  853): set_light_backlight: 113
,D/qdlights(  853): set_light_backlight: 110
,D/qdlights(  853): set_light_backlight: 106
,D/qdlights(  853): set_light_backlight: 103
,D/qdlights(  853): set_light_backlight: 100
,D/qdlights(  853): set_light_backlight: 96
,D/qdlights(  853): set_light_backlight: 93
,D/qdlights(  853): set_light_backlight: 90
,D/qdlights(  853): set_light_backlight: 86
,D/qdlights(  853): set_light_backlight: 83
,D/qdlights(  853): set_light_backlight: 80
,D/qdlights(  853): set_light_backlight: 76
,D/qdlights(  853): set_light_backlight: 73
,D/qdlights(  853): set_light_backlight: 70
,D/qdlights(  853): set_light_backlight: 66
,D/qdlights(  853): set_light_backlight: 63
,D/qdlights(  853): set_light_backlight: 60
,D/qdlights(  853): set_light_backlight: 56
,D/qdlights(  853): set_light_backlight: 53
,D/qdlights(  853): set_light_backlight: 50
,D/qdlights(  853): set_light_backlight: 46
,D/qdlights(  853): set_light_backlight: 43
,D/qdlights(  853): set_light_backlight: 40
,D/qdlights(  853): set_light_backlight: 36
,D/qdlights(  853): set_light_backlight: 33
,D/qdlights(  853): set_light_backlight: 30
,D/qdlights(  853): set_light_backlight: 26
,D/qdlights(  853): set_light_backlight: 23
,D/qdlights(  853): set_light_backlight: 20
,D/qdlights(  853): set_light_backlight: 16
,D/qdlights(  853): set_light_backlight: 13
,D/qdlights(  853): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 155703119999; DSPS: 5194176; Offset : -2820282057
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36056 ms ago)
I/PowerManagerService(  853): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36066 ms ago)
W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  853): Sleeping (uid 1000)...
D/LPWGController(  853): [updateScreenState] screen on = false
D/LPWGController(  853): disable proximity sensor
D/LPWGController(  853): enable proximity sensor
I/SensorManager(  853): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2143b1cf] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  853): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  853): activate: handle is 48, enable
V/sensors_hal_Ctx(  853): activate sensors is 1400000000000
D/sensors_hal_Thresh(  853): enable: handle=48
I/sensors_hal_SAM(  853): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  853): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  853): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  853): enable: Received response: 0
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36105 ms ago)
I/Adreno-EGL(  853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  853): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  853): Build Date: 03/02/15 Mon
I/Adreno-EGL(  853): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  853): Remote Branch: 
I/Adreno-EGL(  853): Local Patches: 
I/Adreno-EGL(  853): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (540 us)
,I/Sensors (  418): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  853): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  853): processInd: handle 48, count=1
V/sensors_hal_Thresh(  853): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  853): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  853): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  853): poll: count: 256
I/sensors_hal_Ctx(  853): poll: released wakelock sensor_ind
D/sensors_hal_Util(  853): waitForResponse: timeout=0
D/LPWGController(  853): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  853): current mode = 1  value = 1 1
I/LPWGController(  853): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  853): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  853): set_light_backlight: 0
,I/SensorManager(  853): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  853): activate: handle is 46, disable
V/sensors_hal_Ctx(  853): activate sensors is 1000000000000
D/sensors_hal_LP2(  853): enable: handle=46
D/sensors_hal_LP2(  853): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  853): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  853): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  853): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  853): Display changed displayId=0
,D/DSDPConnection( 1752): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  853): Excessive delay in setPowerMode(): 188ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  853): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1335): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1335): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1335): handleNotifyScreenOFF
D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/WifiServerServiceExt(  853): sendKtScanInterval  mRtspPlay : false
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
I/WifiServerServiceExt(  853): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 853
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
,V/voice   (  281): voice_set_parameters: enter: screen_state=on
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
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1805): lockStatus = 0
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1805): RESTART MSG
,D/Ulp_jni (  853): JNI:system_update. Event-0
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 3
,D/NfcService( 1788): Discovery configuration equal, not updating.
D/SplitWindow(  853): check instance of lgWin Window{3487e33a u0 SearchPanel}
,I/Sensors (  418): sns_pwr.c(301):releasing wakelock
D/InputDispatcher(  853): Window went away: Window{17668ad7 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2679): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:42:55
,D/WeatherService( 2679): 2 : ACTION screen on
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2679): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2679): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:42:55
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_ON
D/AppCleanupService( 4099): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 853
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  853): CMD_SCREEN_OFF 
D/WifiController(  853): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2679): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:42:56
D/WeatherService( 2679): 2 : ACTION screen off
D/WeatherService( 2679): 2 : TimeTick Receiver Unregister
D/WeatherService( 2679): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:42:56
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_OFF
D/AppCleanupService( 4099): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4099): AppUsageStatsSaveTask
E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: 0
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{3df39beb type 2 when 161962 com.android.systemui} when 161962
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1752): getCallState : 0
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 175703874731; DSPS: 5849561; Offset : -2820290420
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=140581534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{1cfd2d48 type 2 when 183042 android} when 183042
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=140581534 [*alarm*], flags=0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{94867e1 type 2 when 188090 com.google.android.gms} when 188090
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 8660 seconds from now (1454579006400)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 47402(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 14MB/23MB, paused 1.850ms total 97.843ms
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 195705285921; DSPS: 6504967; Offset : -2820283898
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 215706002789; DSPS: 7160350; Offset : -2820267528
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 235706708249; DSPS: 7815733; Offset : -2820264232
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 255707415742; DSPS: 8471117; Offset : -2820289474
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=140581534, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{162a0b51 type 2 when 269045 android} when 269045
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=140581534 [*alarm*], flags=0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 275708164484; DSPS: 9126501; Offset : -2820272634
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 295708842862; DSPS: 9781883; Offset : -2820266111
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5508): --= Surplus to requirements =--
I/jxcore-log( 5508): 
I/jxcore-log( 5508): ****TEST TOOK:  ms ****
I/jxcore-log( 5508): 
I/jxcore-log( 5508): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5508): 
,D/AndroidRuntime( 8211): 
D/AndroidRuntime( 8211): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8211): CheckJNI is OFF
,D/AndroidRuntime( 8211): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  853): Killing 5508:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  853): WIN DEATH: Window{21b06061 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  853): Skipping PackageSetting{31a3b94e com.example.hello/10317} due to missing metadata
D/InputDispatcher(  853): Focus left window: Window{21b06061 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  853): Window went away: Window{21b06061 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  853):   Force finishing activity ActivityRecord{2476994c u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  853): Display changed displayId=0
,D/DSDPConnection( 1752): Display #0 changed.
W/ActivityManager(  853): Spurious death for ProcessRecord{10ffafb6 5508:com.test.thalitest/u0a316}, curProc for 5508: null
,I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3616): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8236 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
W/System.err( 3616): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3616): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3616): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3616): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3616): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3616): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3616): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3616): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3616): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3616): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3616): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 1943): Explicit concurrent mark sweep GC freed 22404(1335KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/21MB, paused 2.255ms total 163.431ms
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
,D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1372): handleShortcutListChanged...
,D/InputDispatcher(  853): Focus entered window: Window{1910d2e0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cae59be,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cae59be,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 8236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8236): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8236): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     (  853): Explicit concurrent mark sweep GC freed 52548(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 18.904ms total 316.440ms
I/art     (  853): WaitForGcToComplete blocked for 141.166ms for cause Explicit
,I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
D/administrator(  853): Handling package changes for user 0
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  853): Got RemoteException sending setActive(false) notification to pid 5508 uid 10316
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{3a4b14f2 u0 com.lge.launcher2/.Launcher t221} time:306167
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService(  853): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
I/LGEmail ( 8236): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/PhoneStatusBar( 1372): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  853): removeObsoleteFile: deleting file=222_task.xml
W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1594): Unable to connect to the editor to retrieve text... will retry later
D/LGEmail ( 8236): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/art     (  853): Explicit concurrent mark sweep GC freed 8464(508KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 17.572ms total 347.498ms
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1788): getDefaultRoute
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,D/AndroidRuntime( 8211): Shutting down VM
,I/PackageChangeReceiver( 8236): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/AppUp4:PreloadHelper( 7889): added Exclude : com.test.thalitest
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8269 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 7911:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_7911/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@2e7c2ea time:306796
,I/art     ( 1879): Explicit concurrent mark sweep GC freed 28252(1543KB) AllocSpace objects, 21(2MB) LOS objects, 40% free, 15MB/25MB, paused 2.440ms total 75.267ms

```
