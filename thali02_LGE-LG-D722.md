#### Test 57924002a578a80_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/libprocessgroup(  997): failed to open /acct/uid_10010/pid_5124/cgroup.procs: No such file or directory
--------- beginning of main
D/EulaProviderUpdateObserver( 5456): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5456): uri : package:com.test.thalitest
,D/[BNRAppListMgrReceiver]( 5221): android.intent.action.PACKAGE_ADDED : com.test.thalitest
I/ActivityManager(  997): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5478 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  997): Killing 4270:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10006/pid_4270/cgroup.procs: No such file or directory
D/AndroidRuntime( 5476): 
D/AndroidRuntime( 5476): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5476): CheckJNI is OFF
W/ProcessCpuTracker(  997): Skipping unknown process pid 5495
W/ProcessCpuTracker(  997): Skipping unknown process pid 5498
V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{e004984 type 2 when 81784 android} when 81784
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AndroidRuntime( 5476): Calling main entry com.android.commands.am.Am
I/ActivityManager(  997): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  997): setTaskToReturnTo : TaskRecord{2c9db56d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  997): setTaskToReturnTo : TaskRecord{2c9db56d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  997): AppWindowTokenEx init.. 
D/ContextHelper(  997): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  997): Focus left window: Window{4628dbb u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5476): Shutting down VM
D/SplitWindow(  997): check instance of lgWin Window{d89e8f u0 Starting com.test.thalitest}
I/ActivityManager(  997): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5518 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  997): Starting window displayed
I/SystemUI[Framework](  997): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  997): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  997): setLGSystemUiVisibility(0x0)
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx(  997): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  997): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a64fd9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  997): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1373): draw background and invalidate : color = 10000000
I/HotwordDetector( 1937): Closing mic
D/BarTransitions( 1373): draw background and invalidate : color = f0e0e0e
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@1768dc6d
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
D/AlertService( 3826): Beginning updateAlertNotification
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
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb3840000
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,D/AlertService( 3826): No fired or scheduled alerts
I/NotificationManager( 3826): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(5) by com.android.calendar
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
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb3840000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
I/NotificationManager( 3826): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(7) by com.android.calendar
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
I/NotificationManager( 3826): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(9) by com.android.calendar
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioSystem( 1970): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  997): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): releasing 16 from 1937 for -1
V/AudioSystem( 2705): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/AudioFlinger(  284): RecordThread 0xb3840000 exiting
V/AudioSystem( 3197): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): releaseInput() exit
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  284): removeClient_l() pid 1937, calling pid 284
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1743): ioConfigChanged() event 4, ioHandle 17
I/NotificationManager( 3826): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(18) by com.android.calendar
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/NotificationManager( 3826): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3826): com.android.calendar: cancel(20) by com.android.calendar
I/HotwordRecognitionRnr( 1937): Hotword detection finished
D/AlertService( 3826): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3826): No events found starting within 1 week.
I/GAv4    ( 5478): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5478):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5478):   adb logcat -s GAv4
W/GAv4    ( 5478): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ContextHelper( 5518): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/GAv4    ( 5478): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5478): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5478): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/WebViewFactory( 5518): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5518): Time to load native libraries: 2 ms (timestamps 2631-2633)
I/LibraryLoader( 5518): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5518): Binding Chromium to main looper Looper (main, tid 1) {3d535835}
I/LibraryLoader( 5518): Expected native library version number "",actual native library version number ""
I/chromium( 5518): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5518): Initializing chromium process, singleProcess=true
W/art     ( 5518): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5518): ApplicationContext is null in ApplicationStatus
W/chromium( 5518): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5518): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5518): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5518): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5518): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5518): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5518): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5518): Remote Branch: 
I/Adreno-EGL( 5518): Local Patches: 
I/Adreno-EGL( 5518): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5478): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5478): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5478): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  997): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5566 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  997): Killing 5255:com.google.android.music:main/u0a81 (adj 15): empty #11
V/AudioPolicyService(  284): registerClient() client 0xb383ad20, uid 10316
D/BluetoothManagerService(  997): Message: 20
D/BluetoothManagerService(  997): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b8ed0d9:true
,D/BluetoothAdapterService(418267825)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f35260f
W/libprocessgroup(  997): failed to open /acct/uid_10081/pid_5255/cgroup.procs: No such file or directory
I/art     ( 5478): CheckpointMarkThreadRoots callback created = 0xb050fa10
,I/ActivityManager(  997): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5594 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 5478): CheckpointMarkThreadRoots callback created = 0xb050f9e0
,V/JNIHelp ( 5478): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GservicesProvider( 5594): Gservices pushing to system: true; secure/global: true
,W/System  ( 5478): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5478): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 5518): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5518): onDetachedFromWindow called when already detached. Ignoring
,I/GoogleHttpClient( 5594): GMS http client unavailable, use old client
D/SystemWebViewEngine( 5518): CordovaWebView is running on device made by: LGE
,W/art     ( 5518): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5518): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5594): GMS http client unavailable, use old client
,I/Activity( 5518): Activity.onPostResume() called 
,D/OpenGLRenderer( 5518): Render dirty regions requested: true
I/OpenGLRenderer( 5518): Initialized EGL, version 1.4
D/OpenGLRenderer( 5518): Enabling debug mode 0
,D/Atlas   ( 5518): Validating map...
,D/SplitWindow(  997): check instance of lgWin Window{5244ab2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5518): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  997): Killing 5311:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10014/pid_5311/cgroup.procs: No such file or directory
,D/InputDispatcher(  997): Focus entered window: Window{5244ab2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  997): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  997): Displayed com.test.thalitest/.MainActivity: +1s472ms
I/Timeline(  997): Timeline: Activity_windows_visible id: ActivityRecord{bbba5a2 u0 com.test.thalitest/.MainActivity t222} time:83625
I/Timeline( 5518): Timeline: Activity_idle id: android.os.BinderProxy@477e088 time:83649
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,W/BindingManager( 5518): Cannot call determinedVisibility() - never saw a connection for the pid: 5518
,I/ActivityManager(  997): Killing 5333:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10021/pid_5333/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5651 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/JsMessageQueue( 5518): Set native->JS mode to OnlineEventsBridgeMode
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,D/Finsky  ( 5651): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/jxcore_app_log( 5518): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426151936
,I/chromium( 5518): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/Finsky  ( 5651): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5651): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5651): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5651): com.android.vending: cancel(-1050172287) by com.android.vending
I/art     ( 5518): CheckpointMarkThreadRoots callback created = 0x9c5bf480
,I/art     ( 5518): CheckpointMarkThreadRoots callback created = 0x9c5bf450
I/NotificationManager( 5651): com.android.vending: cancel(1003285959) by com.android.vending
,D/Ads     ( 5651): Skipping gmscore version check
,D/Finsky  ( 5651): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5651): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@1aaafa82 on behalf of 5651
,D/Finsky  ( 5651): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  997): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5693 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 5361:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10009/pid_5361/cgroup.procs: No such file or directory
,D/Finsky  ( 5651): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 5693): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5693): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 5651): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/MultiDex( 5693): VM with version 2.1.0 has multidex support
I/MultiDex( 5693): install
I/MultiDex( 5693): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5693): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5693): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5693): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36223aad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5693): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5693): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5693): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5693): Reading stored module config
,D/PackageBroadcastService( 5693): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5693): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5693): Loading module APK com.google.android.play.games
D/NativeLibraryUtils( 5693): Install completed successfully. count=14 extracted=0
,I/art     ( 5693): CheckpointMarkThreadRoots callback created = 0xb042d410
,I/art     ( 5693): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,D/ChimeraCfgMgr( 5693): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5693): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5693): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5693): Submit a task: k
,I/art     (  997): Explicit concurrent mark sweep GC freed 20681(1002KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.420ms total 161.081ms
,D/ChimeraCfgMgr( 5693): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5693): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5693): Processing package: com.test.thalitest
,I/Icing   ( 5693): Storage manager: low false usage 1.77MB avail 2.37GB capacity 4.06GB
W/BaseAppContext( 5693): Using Auth Proxy for data requests.
,D/GassUtils( 5693): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5693): Found info for package com.test.thalitest in db.
,I/art     ( 5693): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5693): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/PeopleDatabaseHelper( 5693): cleanUpNonGplusAccounts done.
,E/BaseAppContext( 5693): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/BaseAppContext( 5693): Using Auth Proxy for data requests.
D/LocationInitializer( 5693): Restart initialization of location
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,W/art     ( 5518): Suspending all threads took: 13.101ms
,W/jxcore-log( 5518): Initializing JXcore engine
W/jxcore-log( 5518): JXcore engine is ready
I/art     ( 5518): Background sticky concurrent mark sweep GC freed 12477(1174KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 14.344ms total 43.332ms
I/ActivityManager(  997): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5753 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 5693): Using Auth Proxy for data requests.
,W/BaseAppContext( 5693): Using Auth Proxy for data requests.
,W/BaseAppContext( 5693): Using Auth Proxy for data requests.
W/BaseAppContext( 5693): Using Auth Proxy for data requests.
W/BaseAppContext( 5693): Using Auth Proxy for data requests.
,E/Icing   ( 5693): Array storage bad crc 2709708402 vs 850469057
W/Thread-651( 5678): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5953]" dev="sockfs" ino=5953 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-651( 5678): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-651( 5678): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7487]" dev="sockfs" ino=7487 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-651( 5678): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5678): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5678): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24474]" dev="sockfs" ino=24474 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5518): Starting JXcore engine
,E/Icing   ( 5693): Array storage bad crc 2881407783 vs 2693982007
,W/IcingInternalCorpora( 5693): getNumBytesRead when not calculated.
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/InitAlarmsService( 3826): Clearing and rescheduling alarms.
E/Icing   ( 5693): Array storage bad crc 3904043657 vs 1969603120
E/Icing   ( 5693): Trie mmap suffix failed
,I/ActivityManager(  997): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5776 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 24.502ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 522us total 21.684ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.287ms
,W/Icing   ( 5693): Docstore bad crc 0xfc746ebd vs 0x30a175d1
,W/jxcore-log( 5518): Platform android
W/jxcore-log( 5518): 
W/jxcore-log( 5518): Process ARCH arm
W/jxcore-log( 5518): 
,W/ResourcesManager( 5776): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5776): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@258a9a40
,W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/CalendarProvider2( 5776): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5776): Created com.android.providers.calendar.CalendarAlarmManager@3d535835(com.android.providers.calendar.CalendarProvider2@258a9a40)
D/CalendarProvider2( 5776): Scheduling check of next Alarm
,D/CalendarProvider2( 5776): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5753): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Icing   ( 5693): Array storage bad crc 2024692317 vs 0
E/Icing   ( 5693): Trie mmap node failed
W/GAV2    ( 5753): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  997): Killing 3826:com.android.calendar/u0a13 (adj 15): empty #11
,W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  997): failed to open /acct/uid_10013/pid_3826/cgroup.procs: No such file or directory
,W/ActivityManager(  997): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5753): Error finding the version of the Email provider.....
E/Gmail   ( 5753): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5753): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5753): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5753): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5753): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5753): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5753): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5753): We do not support migrating this version of the Email provider.
D/ChimeraCfgMgr( 5693): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5693): Module APK com.google.android.play.games already loaded
,I/Gmail   ( 5753): getAccountsCursor
I/ActivityManager(  997): Killing 5381:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 5753): Observing account changes for notifications
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5693): updateResources: need to parse f{com.google.android.gms}
,I/jxcore-log( 5518): JXcore Cordova bridge is ready!
I/jxcore-log( 5518): 
W/jxcore-log( 5518): JXcore engine is started
,W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_5381/cgroup.procs: No such file or directory
,W/ActivityManager(  997): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  997): RTC_WAKEUP set : Alarm{30eb7a6c type 0 when 1454287251369 com.android.providers.contacts} when 1454287251369
V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{2f183835 type 2 when 61669 com.google.android.talk} when 61669
V/AlarmManager(  997): RTC_WAKEUP set : Alarm{3225063b type 0 when 1454460102202 com.google.android.googlequicksearchbox} when 1454460102202
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@35ac7593 on behalf of 5693
,I/art     ( 5693): Background sticky concurrent mark sweep GC freed 10394(824KB) AllocSpace objects, 9(144KB) LOS objects, 6% free, 13MB/14MB, paused 9.144ms total 84.427ms
,W/InstanceID/Rpc( 5693): Found 10006
,I/art     ( 5594): Explicit concurrent mark sweep GC freed 7963(400KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.078ms total 67.977ms
,I/ActivityManager(  997): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5829 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/Gmail   ( 5753): notifyAccountChanged
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@28f309d0 on behalf of 5693
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@2358bdc9 on behalf of 5693
,I/Gmail   ( 5753): getAccountsCursor
I/Gmail   ( 5753): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5518): Toggling radios to true
I/jxcore-log( 5518): 
I/Gmail   ( 5753): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/BluetoothAdapter( 5518): enable(): BT is already enabled..!
D/WifiServiceImplEx(  997): setWifiEnabled: true pid=5518, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  997): setWifiEnabled: true pid=5518, uid=10316
I/Gmail   ( 5753): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5753): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/WifiServiceImplEx(  997): disconnect pid=5518, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  997): reconnect pid=5518, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5518): Radios toggled
I/jxcore-log( 5518): 
I/jxcore-log( 5518): My device name is: LGE-LG-D722
I/jxcore-log( 5518): 
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2809): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  997): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  997): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1793): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  997): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  997): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  997): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Clearing all IP addresses on wlan0
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1733): Read error: ssl=0xb045a200: I/O error during system call, Connection timed out
,D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xb045a200: I/O error during system call, Broken pipe
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
,D/WifiHS20(  997): hidePasspointNotification off =false
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  997): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  997): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:42.714 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  997): hidePasspointNotification off =false
E/WifiStateMachine(  997): Start Disconnecting Watchdog 1
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:42.721 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService(  997): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  997): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/LGWifiP2pService(  997): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  997): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CalendarProvider2( 5776): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): ValidatedState{ when=-8ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): DefaultState{ when=-15ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): Forcing reevaluation
,W/ContentResolver( 5776): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{2b9e18d2 type 2 when 87918 com.google.android.gms} when 87918
I/ActivityManager(  997): Killing 5398:com.android.gallery3d/u0a23 (adj 15): empty #11
D/WifiServiceExtension( 1793): isInternetCheckAvailable return false
D/PhoneMonitor( 5829): Register our PhoneStateListener
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  997): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  997): disableDataServiceNotify
D/DSQN    (  997): stop dsqn bin
W/libprocessgroup(  997): failed to open /acct/uid_10023/pid_5398/cgroup.procs: No such file or directory
D/ConnectivityService(  997): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiHS20(  997): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  997): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  997): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:42.867 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/CSLegacyTypeTracker(  997): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  997): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): Disconnected - quitting
D/WifiServiceExtension( 1793): isInternetCheckAvailable return false
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiNetworkAgent(  997): NetworkAgent: NetworkAgent channel lost
D/DhcpStateMachine(  997): StoppedState
D/DhcpStateMachine(  997): StoppedState{ when=-148ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  997): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20(  997): hidePasspointNotification off =false
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:42.882 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Tethering(  997): MasterInitialState.processMessage what=3
V/NetworkPolicy(  997): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1841): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  997): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  997): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  997): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1743): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  997): Removing idletimer
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:42.893 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/QCNEJ   ( 1841): |CORE| No family connected
V/NetworkPolicy(  997): [LG_RESTRICTED] !!!isConnected  type  :1
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  997): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = -1
,D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateDISCONNECTED
D/WIFI    (  997): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateSCANNING
D/WIFI    (  997):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/Icing   ( 5693): Internal init done: storage state 0
I/ActivityManager(  997): Killing 5417:com.android.contacts/u0a18 (adj 15): empty #11
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/NotificationManager( 5693): com.google.android.gms: cancel(10436) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,D/PhoneMonitor( 5829): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5829): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5829): [parse] Load xml
V/TelephonyAutoProfiling( 5829): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5829): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5829): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  997): failed to open /acct/uid_10018/pid_5417/cgroup.procs: No such file or directory
,I/Icing   ( 5693): 22 corpora need re-polling
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5693): Post-init done
I/Gmail   ( 5753): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  997): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5862 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  997): Explicit concurrent mark sweep GC freed 30414(1426KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.452ms total 147.387ms
,I/Icing   ( 5693): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
W/ResourcesManager( 5862): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  997): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5886 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/MusicStore( 5886): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5886): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2809): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/Babel_SMS( 5862): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5862): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5862): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5862): MmsConfig.loadFromDatabase
D/LocSvc_java(  997): onReceive
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:43.925 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:43.929 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5886): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2809): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateASSOCIATED
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/ContextImpl( 5886): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:43.957 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:43.965 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
E/Babel_SMS( 5862): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5862): MmsConfig.loadFromResources
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/Babel_SMS( 5862): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5862): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/wpa_supplicant( 2809): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateGROUP_HANDSHAKE
,I/WifiServiceExtension(  997): setVHTCapabilityType  : false
W/ResourcesManager( 5886): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5886): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WifiServerServiceExt(  997): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  997): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  997): setSecurityType  : 2
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.049 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.05 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/SensorManager( 5862): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5862): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5862): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManage,r( 5862): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5862): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5862): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5862): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5862): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5862): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5862): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5862): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5862): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5862): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5862): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5862): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5862): found sensor: Motion Accel, handle=46
D/ConnectivityService(  997): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  997): Got NetworkAgent Messenger
D/ConnectivityService(  997): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  997): NetworkAgent connected
D/WifiServiceExtension( 1793): isInternetCheckAvailable return false
E/WifiConfigStore(  997): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/JNIHelp ( 5886): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/WifiConfigStore(  997): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
E/WifiStateMachine(  997): Start Dhcp Watchdog 2
D/DhcpStateMachine(  997): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  997): WaitBeforeStartState
I/ActivityManager(  997): Process com.lge.bnr (pid 5221) has died
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-67 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.155 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  997): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,W/ActivityThread( 5886): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5886): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@307e7df4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5886): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5886): GMSCore installation verified
I/ConfigStore( 5886): Config Database version: 1
,I/art     ( 5862): CheckpointMarkThreadRoots callback created = 0xb042d870
I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  997): Reconfiguring input devices.  changes=0x00000010
E/WifiStateMachine(  997): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  997): Current State is mWaitBeforeStartState.
,W/Settings( 5862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService(  997): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36b90b4a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  997): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36b90b4a target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  997): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  997): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/Babel_Crash( 5862): startup - clean
D/DhcpStateMachine(  997): DHCP Start wake lock is acquired.
D/CommandListener(  280): Setting iface cfg
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  997): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/art     ( 5886): Background sticky concurrent mark sweep GC freed 23400(1168KB) AllocSpace objects, 4(64KB) LOS objects, 9% free, 10MB/11MB, paused 20.118ms total 125.720ms
,D/administrator(  997): Handling package changes for user 0
D/ConnectivityService(  997): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  997): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  997): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  997): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  997): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  997): ignoring duplicate network state non-change
,I/Babel   ( 5862): deleted: false for 0
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
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.299 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  997): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.307 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  997): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.319 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,E/ConnectivityService(  997): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  997): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  997): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  997): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  280): netlink response contains error (File exists)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  997): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  997): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  997): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  997): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:44.344 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/Nat464Xlat(  997): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  997): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  997):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  997):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  997):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  997): currentScore = 0, newScore = 20
D/ConnectivityService(  997):    accepting network in place of null
D/ConnectivityService(  997): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  997): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  997):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  997): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  997): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1743): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): [LWD] Start DNSResolver start to wait
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): [LWD] wait 500ms before dns check
D/ConnectivityService(  997): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  997): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  997): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
,I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  997): validation of new default Network = false
D/ConnectivityService(  997): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  997): enableDataServiceNotify 
D/DSQN    (  997): start dsqn bin
I/art     ( 5862): CheckpointMarkThreadRoots callback created = 0xb042d840
,D/ConnectivityService(  997): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/DhcpStateMachine(  997): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  997): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  997): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/NotificationService(  997): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  997): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  997): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/NetworkPolicy(  997): [LG_RESTRICTED] checkMobilePolicy_type()
I/DSQN    ( 5934): DSQN samuel.seo ver 141203
E/DSQN    ( 5934): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5934): created command queue thread
I/DSQN    ( 5934): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5934): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/dhcpcd  ( 5935): version 5.5.6 starting
,E/dhcpcd  ( 5935): get_duid: Read-only file system
I/BackupManagerService(  997): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  997): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  997): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  997): setSupplicantStateCOMPLETED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  997): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  997): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Tethering(  997): MasterInitialState.processMessage what=3
,V/BackupManagerService(  997): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  997): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1e9f6cf0
,D/WifiServiceExtension( 1793): isInternetCheckAvailable return false
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
D/WifiServiceExtension( 1793): isInternetCheckAvailable return false
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/dhcpcd  ( 5935): wlan0: rebinding lease of 192.168.1.134
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinService( 5693): Checkin interval check for package: unspecified last checkin: 1454460094162 min interval config: 0 actual interval: 10421
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 5693): Disabling old GoogleServicesFramework version
,I/Icing   ( 5693): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
,I/Icing   ( 5693): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
I/art     ( 5693): Background sticky concurrent mark sweep GC freed 8843(548KB) AllocSpace objects, 4(64KB) LOS objects, 4% free, 13MB/14MB, paused 5.067ms total 62.461ms
W/ActivityManager(  997): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{20bf259d 5693:com.google.android.gms/u0a6} (pid=5693, uid=10006) that is not exported from uid 10046
E/Icing   ( 5693): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{20bf259d 5693:com.google.android.gms/u0a6} (pid=5693, uid=10006) that is not exported from uid 10046
I/Icing   ( 5693): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
E/Icing   ( 5693): Aborting indexing of corpus volumes__id
I/Icing   ( 5693): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/MediaRouter( 5886): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5886): type=WIFI subType= reason=null isConnected=true
,W/AudioCapabilities( 5862): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5862): Unsupported mime audio/adpcm
W/AudioCapabilities( 5862): Unsupported mime audio/g726
W/AudioCapabilities( 5862): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5862): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5862): Unsupported mime video/mjpg
,W/VideoCapabilities( 5862): Unsupported mime video/theora
I/NetworkMonitor( 5886): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5886): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5886): Using platform SSLCertificateSocketFactory
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): [LWD] DNSResolver start dns
,D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/art     ( 5693): Suspending all threads took: 6.772ms
,I/CheckinService( 5693): Checking schedule, now: 1454460104971 next: 1454460124092
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  997): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): [LWD] DNSResolver end dns
I/art     ( 5693): Background partial concurrent mark sweep GC freed 20294(1181KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 13MB/22MB, paused 11.144ms total 95.324ms
I/CheckinService( 5693): active receiver: disabled
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): Checking http://clients3.google.com/generate_204 on "NG700"
W/AudioCapabilities( 5862): Unsupported mime audio/evrc
,W/AudioCapabilities( 5862): Unsupported mime audio/qcelp
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  997): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5955 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DSQN    ( 5934): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5934): restart monitoring
,I/DSQN    ( 5934): dsqn report finish
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  997): DSQM DsqnNotification wlan0  1
D/DSQN    (  997): start to monitor internet connection
W/AudioCapabilities( 5862): Unsupported mime audio/amr-wb-plus
,I/AudioManager( 5195): getMode name:com.lge.qremote
W/AudioCapabilities( 5862): Unsupported mime audio/qcelp
I/ActivityManager(  997): Process com.lge.lockscreensettings (pid 5437) has died
I/AudioManager( 5195): getMode name:com.lge.qremote
,W/AudioCapabilities( 5862): Unsupported mime audio/evrc
,I/AudioManager( 5195): getMode name:com.lge.qremote
,I/NotificationManager( 5886): com.google.android.music: cancel(1061) by com.google.android.music
,W/VideoCapabilities( 5862): Unsupported mime video/mp4v-esdp
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/AudioManager( 5195): getMode name:com.lge.qremote
D/UEI.SmartControl( 5955): Quickset Services start...
I/UEI.SmartControl( 5955): Manufacture = LGE
D/UEI.SmartControl( 5955): File observer start...
,E/UEI.SmartControl( 5955): IR Port is disabled: false
D/UEI.SmartControl( 5955): Starting file observer...
D/UEI.SmartControl( 5955): Extracting JNI libs...
D/UEI.SmartControl( 5955): --- this system supports 32-bit or 64-bit only
I/VideoCapabilities( 5862): Unsupported profile 4 for video/mp4v-es
,I/AudioManager( 5195): getMode name:com.lge.qremote
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 00:41:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454460105295], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454460105055]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1793): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  997): Validated
D/ConnectivityService(  997): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  997):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  997): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  997): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  997): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  997):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1743): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/ResourcesManager(  997): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  997): Process com.google.android.apps.docs (pid 5478) has died
,D/WifiDataContinuityService(  997): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  997): set CMD_CAPTIVE_CHECK_COMPLETED
E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/vclib   ( 5862): onServiceConnected
,W/Babel   ( 5862): Attempted to change video mute state without an active call.
D/LocationInitializer( 5693): Restart initialization of location
,I/NotificationManager( 5862): com.google.android.talk: cancel(10436) by com.google.android.talk
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/UEI.SmartControl( 5955): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5955): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5955): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  997): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/UEI.SmartControl( 5955): --- Selecting new region: 2
,I/UEI.SmartControl( 5955): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5955): Platform has CIR...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 5955): NO CIR support, need to check package...
,I/UEI.SmartControl( 5955): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5955): QS Service created
E/UEI.SmartControl( 5955): QS start get config
,W/ResourceType(  997): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/NotificationManager( 5862): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5862): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5862): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5982 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5955): Loading JNI Libs...
D/UEI.SmartControl( 5955):  configuring local db...
,I/dhcpcd  ( 5935): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/dhcpcd  ( 5935): wlan0: leased 192.168.1.134 for 86400 seconds
,I/ActivityManager(  997): Process com.google.android.apps.plus (pid 5566) has died
,D/LocationProviderProxy(  997): applying state to connected service
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  997): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  997): identical MTU - not setting
D/Nat464Xlat(  997): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  997): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  997):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  997): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  997): enableDataServiceNotify 
D/DSQN    (  997): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:45.875 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/JNIHelp ( 5862): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/DSQN    (  997): dsqn is running restart
,D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/DSQN    ( 6012): DSQN samuel.seo ver 141203
E/DSQN    ( 6012): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6012): created command queue thread
I/DSQN    ( 6012): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6012): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/NetworkMonitor( 5886): type=WIFI subType= reason=null isConnected=true
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  997): onReceive
D/LocSvc_java(  997): got connectivity action
,D/LocSvc_java(  997): broadcast - no network connections
D/LocSvc_java(  997): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  997): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  997): onReceive
D/LocSvc_java(  997): got connectivity action
D/LocSvc_java(  997): broadcast - no network connections
D/LocSvc_java(  997): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  997): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  997): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  997): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  997): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  997): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  997): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  997): ignore wifi update if we are not in OPENING or CLOSING
I/AppUp4:AppBoxCP( 5982): onCreate
W/AppUp4:DB( 5982):  [AppBoxDatabaseHelper] construct
,I/NetworkMonitor( 5886): type=WIFI subType= reason=null isConnected=true
I/AppUp4:DB( 5982):  setFingerPrint start
,I/AppUp4:DB( 5982):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5982):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5982):  SDK version = 0
I/AppUp4:DB( 5982):  beforefinger == newfinger no write in DB
,D/GpsLocationProvider(  997): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/System  ( 5862): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5862): Installed default security provider GmsCore_OpenSSL
,D/GpsLocationProvider(  997): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  997): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  997): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  997): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  997): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  997): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  997): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  997): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  997): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  997): RunningState
I/ActivityManager(  997): Process com.lge.eula (pid 5456) has died
,D/AppUp4:AppBoxApplication( 5982): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 5982): onReceive
I/AppUp4:CustModeStarterReceiver( 5982): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5982): Context : android.app.ReceiverRestrictedContext@c8a371f
D/AppUp4:CustFacade( 5982): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5982): isSimDevice : true
,D/GpsLocationProvider(  997): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AppUp4:CustModeStarterReceiver( 5982): begin check event
I/AppUp4:CustModeStarterReceiver( 5982): Event For Nothing, skip.
D/GpsLocationProvider(  997): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UEI.SmartControl( 5955):  ---- Has DB8: true
,D/UEI.SmartControl( 5955): QS start statue = true Error code = 0
D/UEI.SmartControl( 5955): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5955): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/ActivityManager(  997): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6026 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5955): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5955): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5955): IrrcClient ++ 
D/irrcClient( 5955): getIrrcService ++ 
D/irrcClient( 5955): getIrrcService -- 
D/irrcClient( 5955): IrrcClient -- 
W/irrc_jni( 5955): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5955): Services init done
I/UEI.SmartControl( 5955): Device manager: loading config....
D/UEI.SmartControl( 5955): QS Service init finished
D/UEI.SmartControl( 5955): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5955): QS Service version code: 1073
D/UEI.SmartControl( 5955): Service requested: Control
D/UEI.SmartControl( 5955): Config is loaded...
,W/ResourcesManager( 6026): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6026): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6026): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5955): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5955):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5955): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5955): Internal service binding...
D/UEI.SmartControl( 5955): -----IControl: 11
D/UEI.SmartControl( 5955): Caller: com.lge.qremote
D/UEI.SmartControl( 5955): ------------ IControl registerCallback...
I/UEI.SmartControl( 5955): Registering callback...
D/UEI.SmartControl( 5955): -----IControl: 19
D/UEI.SmartControl( 5955): Caller: com.lge.qremote
I/UEI.SmartControl( 5955): Registering Services Ready callback...
I/UEI.SmartControl( 5955): Notify client services are ready...
D/UEI.SmartControl( 5955): -----IControl: 8
,D/UEI.SmartControl( 5955): Caller: com.lge.qremote
D/Icing   ( 5693): Loaded CLD2 Version V2.0 - 20141016
,I/AppConfig( 6026): Total System Memory = 906309632
I/GalleryUtils( 6026): Application Heap = 96 MB
I/AppConfig( 6026): App Tier : NOT_DEF
D/SystemHelper( 6026): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  997): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6048 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  997): Process com.google.android.gm (pid 5753) has died
,W/ResourcesManager( 6048): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6048): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6048): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6048): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6048): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{23d4370d type 2 when 91868 com.android.providers.calendar} when 91868
,I/SystemConfig( 6048): BUILD Country: EU
I/SystemConfig( 6048): BUILD Operator: OPEN
,I/ActivityManager(  997): Process com.android.vending (pid 5651) has died
,I/SystemConfig( 6048): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6048): existFile = false
I/SystemConfig( 6048): canReadFile = false
I/SystemConfig( 6048): systemFeature RCS result false
D/SystemConfig( 6048): refreshRcsSupport() :false
,I/ActivityManager(  997): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6067 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 6067): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6067): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6067): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6067): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6067): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6067): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  997): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6084 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  997): Explicit concurrent mark sweep GC freed 62150(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.575ms total 187.836ms
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:41:47.224 DNS addrs= 192.168.1.1, 0.0.0.0, 
,W/ResourcesManager( 6084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ConnectivityService(  997): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  997): Process com.google.android.music:main (pid 5886) has died
,D/LocSvc_java(  997): onReceive
D/LocSvc_java(  997): got connectivity action
D/LocSvc_java(  997): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  997): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  997): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  997): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  997): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  997): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
V/WifiInternetCheck(  997): Single check msg out of sync, ignoring.
,D/GpsLocationProvider(  997): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 1733): Explicit concurrent mark sweep GC freed 36229(2MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 13MB/22MB, paused 7.205ms total 140.872ms
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  997): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6114 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{31e56128 type 2 when 93419 com.google.android.gms} when 93419
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 6114): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/Icing   ( 5693): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  997): propertyValue:false
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  997): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  997): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  997): propertyValue:false
,I/ActivityManager(  997): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=6145 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
I/DSQN    ( 6012): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6012): restart monitoring
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  997): DSQM DsqnNotification wlan0  1
D/DSQN    (  997): start to monitor internet connection
I/DSQN    ( 6012): dsqn report finish
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 23.895ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.326ms
V/WifiInternetCheck(  997): isHttpConnectionAvailable - We got a valid response : 204
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.836ms
,D/Finsky  ( 6114): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ResourcesManager( 6145): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
W/Settings( 6114): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6114): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6114): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@29123cce on behalf of 6114
D/Finsky  ( 6114): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6114): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6114): Skipping gmscore version check
D/PackageBroadcastService( 5693): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/AudioManager( 5195): getMode name:com.lge.qremote
D/Finsky  ( 6114): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/PackageBroadcastService( 5693): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 5195): getMode name:com.lge.qremote
,D/Finsky  ( 6114): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/SetupWizard( 5829): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
E/MDM     ( 1733): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5693): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
I/ActivityManager(  997): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6208 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  997): Killing 5776:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  997): failed to open /acct/uid_10014/pid_5776/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Killing 5982:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_5982/cgroup.procs: No such file or directory
,W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Icing   ( 5693): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
I/Icing   ( 5693): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
,W/PlayMovies( 6145): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6145): 
,I/Gmail   ( 6208): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5693): Indexing done FC5805F301A6400196925772B79FE617968B1409
I/Icing   ( 5693): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
,W/PlayMovies( 6145): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6145): 
W/GAV2    ( 6208): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 5693): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
I/Icing   ( 5693): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
I/Icing   ( 5693): Indexing done 261F31C44790DA98645222D6E4244392E5409193
I/Icing   ( 5693): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
,W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/PlayMovies( 6145): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 6145): 
D/Finsky  ( 6114): [710] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
,D/Finsky  ( 6114): [710] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
E/Gmail   ( 6208): Error finding the version of the Email provider.....
E/Gmail   ( 6208): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6208): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6208): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6208): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6208): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6208): We do not support migrating this version of the Email provider.
D/PlayMovies( 6145): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 6145): 
,W/AudioCapabilities( 6145): Unsupported mime audio/x-lg-flac
I/Gmail   ( 6208): getAccountsCursor
W/AudioCapabilities( 6145): Unsupported mime audio/adpcm
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioCapabilities( 6145): Unsupported mime audio/g726
W/AudioCapabilities( 6145): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6145): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6145): Unsupported mime video/mjpg
,I/art     ( 5594): Explicit concurrent mark sweep GC freed 3065(121KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 461us total 36.635ms
I/Icing   ( 5693): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
I/Icing   ( 5693): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
W/VideoCapabilities( 6145): Unsupported mime video/theora
,W/ActivityManager(  997): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6208): Observing account changes for notifications
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5693): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
I/Icing   ( 5693): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
,W/AudioCapabilities( 6145): Unsupported mime audio/evrc
W/AudioCapabilities( 6145): Unsupported mime audio/qcelp
W/VideoCapabilities( 6145): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6145): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6145): Unsupported mime audio/qcelp
W/AudioCapabilities( 6145): Unsupported mime audio/evrc
W/VideoCapabilities( 6145): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6145): Unsupported profile 4 for video/mp4v-es
,D/WVCdm   (  284): Instantiating CDM.
I/WVCdm   (  284): CdmEngine::QueryStatus
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
,V/AlarmManager(  997): RTC_WAKEUP set : Alarm{8db0ff7 type 0 when 1454460110030 com.android.vending} when 1454460110030
D/Finsky  ( 6114): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
I/WVCdm   (  284): L3 Terminate.
D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 95250125959; DSPS: 3218994; Offset : -2997246063
,I/art     (  997): Explicit concurrent mark sweep GC freed 34113(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.488ms total 167.104ms
,W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Icing   ( 5693): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
I/Icing   ( 5693): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6145): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  997): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6278 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6292 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/Gmail   ( 6208): notifyAccountChanged
,I/Gmail   ( 6208): getAccountsCursor
,I/Gmail   ( 6208): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6208): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/NotificationManager(  997): android: cancelAsUser(2) by android
,I/Gmail   ( 6208): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6208): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/MusicStore( 6278): Database version: 120
,D/libc-netbsd( 6114): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6114): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6114): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6114): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/Gmail   ( 6208): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6114): propertyValue:false
D/libc-netbsd( 6114): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6114): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6292): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd( 6114): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6114): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 6278): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6278): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 6292): Using schema version: 115
,I/IndexDatabaseHelper( 6292): Index is fine
I/ActivityManager(  997): Process com.android.contacts (pid 6048) has died
,V/JNIHelp ( 6278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Icing   ( 5693): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
,I/Icing   ( 5693): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 5693): Aborting indexing of corpus omnibox
I/Icing   ( 5693): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
I/Icing   ( 5693): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 5693): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
,I/Icing   ( 5693): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
I/Icing   ( 5693): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
I/art     ( 6278): Background sticky concurrent mark sweep GC freed 18743(999KB) AllocSpace objects, 4(64KB) LOS objects, 8% free, 10MB/11MB, paused 10.865ms total 84.563ms
,I/Icing   ( 5693): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
I/Icing   ( 5693): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
W/ActivityThread( 6278): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6278): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@307e7df4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6278): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6278): GMSCore installation verified
I/ConfigStore( 6278): Config Database version: 1
,I/Icing   ( 5693): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Icing   ( 5693): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
I/ActivityManager(  997): Process com.android.gallery3d (pid 6026) has died
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  997): android: cancelAsUser(2) by android
,I/Icing   ( 5693): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
I/Icing   ( 5693): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
D/UEI.SmartControl( 5955): Internal timer expired: 1
,I/ActivityManager(  997): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6328 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/qtaguid ( 6114): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6114): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6114): untagSocket(41) failed with errno -22
I/Icing   ( 5693): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
D/Finsky  ( 6114): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/Icing   ( 5693): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
,I/Icing   ( 5693): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
I/Icing   ( 5693): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,I/MediaRouter( 6278): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/NetworkMonitor( 6278): type=WIFI subType= reason=null isConnected=true
,I/art     ( 6278): CheckpointMarkThreadRoots callback created = 0xaaf60a90
,I/art     ( 6278): CheckpointMarkThreadRoots callback created = 0xaaf60a70
I/ActivityManager(  997): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6347 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  997): android: cancelAsUser(2) by android
,D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/NetworkMonitor( 6278): type=WIFI subType= reason=null isConnected=true
,I/Icing   ( 5693): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/Icing   ( 5693): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
,I/GHttpClientFactory( 6278): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/Icing   ( 5693): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
I/Icing   ( 5693): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
I/GoogleURLConnFactory( 6278): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6347): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6347): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/Icing   ( 5693): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
I/ActivityManager(  997): Killing 6067:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/Icing   ( 5693): updateResources: need to parse f{com.google.android.gms}
,I/MultiDex( 6347): VM with version 2.1.0 has multidex support
I/MultiDex( 6347): install
I/MultiDex( 6347): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  997): failed to open /acct/uid_10069/pid_6067/cgroup.procs: No such file or directory
,I/NotificationManager( 6278): com.google.android.music: cancel(1061) by com.google.android.music
,I/ActivityManager(  997): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6374 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 6114): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6114): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6114): untagSocket(41) failed with errno -22
V/JNIHelp ( 6347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 5693): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/ResourcesManager( 6374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityThread( 6347): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6347): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@209ed7ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6347): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  997): Process com.google.android.apps.plus (pid 6084) has died
,D/CalendarApplication( 6374): CalendarApplication.onCreate()
I/NotificationManager( 6347): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6347): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6347): Reading stored module config
,D/PreferenceKeysParser( 6374): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6374): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@36ffdabe, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@c8a371f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@349f1a6c, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3d535835, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2f5ae4ca, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@19a5263b, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@9997158, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@18ee42b1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3baa8396, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@37b5eb17, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@10e04b04, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@f7358ed, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2d834322, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2da421b3, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@34991370, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1b996e9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@29366f6e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3f35260f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@19d3f69c, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2d0bb8a5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@34de147a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3d28142b, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@477e088, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea43a21, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2c28fe46, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3b11c807, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@dee7d34, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@22e9575d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@24e6b8d2, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@6f8dda3, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1a9038a0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2c690c59, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1053901e, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb1b0ff, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@39d03ecc, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2e951515, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2524902a, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1efa5e1b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1d287bb8, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@283eed91, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1e5384f6, lg_preferences_re,cent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2856c
,D/ChimeraCfgMgr( 6347): Loading module com.google.android.gms.car from APK com.google.android.gms
I/art     ( 6114): CheckpointMarkThreadRoots callback created = 0xaaf0e8d0
D/GeneralPreferenceUtils( 6374): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6374): [init]
I/Config  ( 6374): LGCalendar ver.4.40.17
I/Config  ( 6374): start check model
I/Config  ( 6374): start check native_ca
I/Config  ( 6374): Config Operator=OPEN, Country=EU
D/Config  ( 6374): [setDefaultValuesToPref]
D/Config  ( 6374): [parseProfiles]
,D/ProfilesParser( 6374): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6374): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6374): [updateProfiletoCountryInfo]
D/GeneralPreference( 6374): [checkAndMigrateOldPreference]
D/AlertReceiver( 6374): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6374): Start InitializeAlertRingtoneService.onHandleIntent
,I/art     ( 6114): CheckpointMarkThreadRoots callback created = 0xb042d190
I/AlertUtils( 6374): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6374): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/CAR.SERVICE( 6347): Connecting to CarCallService...
,I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/art     ( 6347): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6347): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6347): Install completed successfully. count=14 extracted=0
V/AlarmManager(  997): RTC_WAKEUP set : Alarm{15761dd type 0 when 1454460112496 com.google.android.googlequicksearchbox} when 1454460112496
,W/HolidayIntentService( 6374): onHandleIntent
D/HolidayDataLoader( 6374): readJsonAsset : holiday.json
W/art     ( 6114): Suspending all threads took: 6.951ms
,D/CAR.SERVICE( 6347): com.google.android.projection.gearhead isn't installed.
,I/jxcore-log( 5518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5518): 
,D/AlertService( 6374): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6374): [updateWidgets] 
,D/MonthWidgetProvider( 6374): [onReceive]
D/CalendarWidgetProvider( 6374): [onReceive]
D/CalendarWidgetProvider( 6374): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6374): [onCreate] mContext.getPackageName() = com.android.calendar
,I/art     (  997): Explicit concurrent mark sweep GC freed 18542(1255KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.247ms total 191.181ms
I/AlertUtils( 6374): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6374): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/CAR.TEL.Service( 6347): Creating a new CarCallService.
,I/AlertUtils( 6374): set default noti to content://media/internal/audio/media/38
D/CAR.TEL.PhoneAdapter( 6347): Creating a new PhoneAdapter instance
D/WeekWidgetProvider( 6374): [onReceive]
D/CalendarWidgetProvider( 6374): [onReceive]
D/CalendarWidgetProvider( 6374): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,I/InitNotificationRingtoneService( 6374): End InitializeAlertRingtoneService.onHandleIntent
E/HolidayIntentService( 6374): onHandleIntent:holiday data empty
,I/ActivityManager(  997): Process com.google.android.videos (pid 6145) has died
,W/ActivityManager(  997): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6347): setListener: com.google.android.gms.car.dn@2c676b8a
W/ActivityManager(  997): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6347): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6347): Starting CarCallService with initial phone null
,V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CalendarTypeController( 6374): [onCreate] mContext.getPackageName() = com.android.calendar
D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/NotificationManager( 6347): com.google.android.gms: cancel(10436) by com.google.android.gms
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6292): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CAR.SERVICE( 6347): Package validated; name: com.android.vending
D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6292): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager( 6114): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6114): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/WiFiOffLoadBroadcast( 6292): MCCMNC not supported: null
I/Icing   ( 5693): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6416 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/Icing   ( 5693): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/AppUp4:AppBoxCP( 6416): onCreate
,W/AppUp4:DB( 6416):  [AppBoxDatabaseHelper] construct
I/NotificationManager( 5862): com.google.android.talk: cancel(8) by com.google.android.talk
I/AppUp4:DB( 6416):  setFingerPrint start
I/AppUp4:DB( 6416):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6416):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6416):  SDK version = 0
I/AppUp4:DB( 6416):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6416): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6416): onReceive
I/AppUp4:CustModeStarterReceiver( 6416): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6416): Context : android.app.ReceiverRestrictedContext@c8a371f
D/AppUp4:CustFacade( 6416): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6416): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6416): begin check event
I/AppUp4:CustModeStarterReceiver( 6416): Event For Nothing, skip.
,I/ActivityManager(  997): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6437 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6437): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6437): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6437): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  997): android: cancelAsUser(2) by android
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/AppConfig( 6437): Total System Memory = 906309632
,I/GalleryUtils( 6437): Application Heap = 96 MB
I/AppConfig( 6437): App Tier : NOT_DEF
,D/SystemHelper( 6437): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  997): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6456 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/qtaguid ( 6114): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6114): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6114): untagSocket(41) failed with errno -22
,D/Finsky  ( 6114): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.android.chrome to false
,I/jxcore-log( 5518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5518): 
,W/ResourcesManager( 6456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6456): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/jxcore-log( 5518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5518): 
,I/jxcore-log( 5518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5518): 
W/ResourcesManager( 6114): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/jxcore-log( 5518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5518): 
W/ResourcesManager( 6114): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SystemConfig( 6456): BUILD Country: EU
I/SystemConfig( 6456): BUILD Operator: OPEN
,W/ResourcesManager( 6114): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 6114): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  997): RTC_WAKEUP set : Alarm{4ea9650 type 0 when 1454460114016 com.android.vending} when 1454460114016
,I/SystemConfig( 6456): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6456): existFile = false
I/SystemConfig( 6456): canReadFile = false
I/SystemConfig( 6456): systemFeature RCS result false
D/SystemConfig( 6456): refreshRcsSupport() :false
I/ActivityManager(  997): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6475 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  997): Killing 5829:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10038/pid_5829/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Killing 6208:com.google.android.gm/u0a53 (adj 15): empty #11
I/LockScreenSettings( 6475): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/libprocessgroup(  997): failed to open /acct/uid_10053/pid_6208/cgroup.procs: No such file or directory
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/DeviceConnectionService( 1733): client connected with version: 8296000
D/LockScreenSettings( 6475): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6475): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6475): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6475): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6475): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  997): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6492 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 6278:com.google.android.music:main/u0a81 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 25.195ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.399ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.062ms
,W/libprocessgroup(  997): failed to open /acct/uid_10081/pid_6278/cgroup.procs: No such file or directory
,D/Finsky  ( 6114): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ResourcesManager( 6492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6114): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  997): Killing 6292:com.android.settings/1000 (adj 15): empty #11
I/ActivityManager(  997): Killing 5594:com.google.process.gapps/u0a6 (adj 15): empty #12
,W/libprocessgroup(  997): failed to open /acct/uid_1000/pid_6292/cgroup.procs: No such file or directory
,W/libprocessgroup(  997): failed to open /acct/uid_10006/pid_5594/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
,I/ActivityManager(  997): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6521 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/PackageBroadcastService( 5693): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  997): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6539 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PackageBroadcastService( 5693): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5693): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6539): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6539): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6539): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6539): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6539): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/GservicesProvider( 6521): Gservices pushing to system: true; secure/global: true
,I/IndexDatabaseHelper( 6539): Using schema version: 115
,I/IndexDatabaseHelper( 6539): Index is fine
I/GoogleHttpClient( 6521): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6521): GMS http client unavailable, use old client
,I/ActivityManager(  997): Killing 5955:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,V/WiFiOffLoadBroadcast( 6539): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/System.err( 5195): android.os.DeadObjectException
W/System.err( 5195): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5195): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5195): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5195): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5195): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5195): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 5195): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5195): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5195): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5195): android.os.DeadObjectException
W/System.err( 5195): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5195): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5195): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5195): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5195): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5195): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5195): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5195): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5195): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,D/WiFiOffLoadBroadcast( 6539): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  997): failed to open /acct/uid_10089/pid_5955/cgroup.procs: No such file or directory
W/ActivityManager(  997): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  997): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6574 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/WiFiOffLoadBroadcast( 6539): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6539): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6539): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6539): MCCMNC not supported: null
,I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6539): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6539): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/UEI.SmartControl( 6574): Quickset Services start...
,I/UEI.SmartControl( 6574): Manufacture = LGE
D/UEI.SmartControl( 6574): File observer start...
E/UEI.SmartControl( 6574): IR Port is disabled: false
D/UEI.SmartControl( 6574): Starting file observer...
D/UEI.SmartControl( 6574): Extracting JNI libs...
D/UEI.SmartControl( 6574): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6574): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,I/ActivityManager(  997): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6592 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  997): Killing 6416:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 6574): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6574): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6574): --- Selecting new region: 2
I/UEI.SmartControl( 6574): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6574): Platform has CIR...
D/UEI.SmartControl( 6574): NO CIR support, need to check package...
I/UEI.SmartControl( 6574): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6574): QS Service created
W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_6416/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6574): QS start get config
,D/UEI.SmartControl( 6574): Loading JNI Libs...
D/UEI.SmartControl( 6574):  configuring local db...
,D/PhoneMonitor( 6592): Register our PhoneStateListener
,I/ActivityManager(  997): Killing 6437:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10023/pid_6437/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5693): Checkin interval check for package: unspecified last checkin: 1454460094162 min interval config: 0 actual interval: 21997
D/PhoneMonitor( 6592): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/ActivityManager(  997): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6613 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 5693): Checking schedule, now: 1454460116194 next: 1454460124092
I/CheckinService( 5693): active receiver: disabled
V/TelephonyAutoProfiling( 6592): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6592): [parse] Load xml
V/TelephonyAutoProfiling( 6592): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6592): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6592): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/UEI.SmartControl( 6574):  ---- Has DB8: true
,D/UEI.SmartControl( 6574): QS start statue = true Error code = 0
D/UEI.SmartControl( 6574): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6574): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6574): IRRCDataComm has AudioManager!!!!.
I/Icing   ( 5693): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/irrc_jni( 6574): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6574): IrrcClient ++ 
D/irrcClient( 6574): getIrrcService ++ 
D/irrcClient( 6574): getIrrcService -- 
D/irrcClient( 6574): IrrcClient -- 
W/irrc_jni( 6574): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6574): Services init done
I/UEI.SmartControl( 6574): Device manager: loading config....
,D/UEI.SmartControl( 6574): QS Service init finished
D/UEI.SmartControl( 6574): QS Service version name: 0.1.73
D/UEI.SmartControl( 6574): QS Service version code: 1073
D/UEI.SmartControl( 6574): Config is loaded...
D/UEI.SmartControl( 6574): Service requested: Control
I/ActivityManager(  997): Killing 6456:com.android.contacts/u0a18 (adj 15): empty #11
,D/UEI.SmartControl( 6574): -----IControl: 11
D/UEI.SmartControl( 6574): Caller: com.lge.qremote
D/UEI.SmartControl( 6574): ------------ IControl registerCallback...
I/UEI.SmartControl( 6574): Registering callback...
D/UEI.SmartControl( 6574): -----IControl: 19
D/UEI.SmartControl( 6574): Caller: com.lge.qremote
I/UEI.SmartControl( 6574): Registering Services Ready callback...
,D/UEI.SmartControl( 6574):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6574): Notify AllClients services are ready: 0
I/Icing   ( 5693): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/UEI.SmartControl( 6574): -----IControl: 8
D/UEI.SmartControl( 6574): Caller: com.lge.qremote
I/MusicStore( 6613): Database version: 120
,W/libprocessgroup(  997): failed to open /acct/uid_10018/pid_6456/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6574): Internal service binding...
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6613): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6613): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6613): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6613): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6613): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19a96106: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6613): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6613): GMSCore installation verified
,I/ConfigStore( 6613): Config Database version: 1
,I/MediaRouter( 6613): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6613): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6613): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  997): Killing 6475:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10069/pid_6475/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6613): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  997): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6654 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/charger_monitor(  491): init target 500000
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GHttpClientFactory( 6613): Using our fixed implementation of GMSCore's GoogleHttpClient
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/GoogleURLConnFactory( 6613): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     (  997): Explicit concurrent mark sweep GC freed 18785(886KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.775ms total 163.603ms
,I/ActivityManager(  997): Killing 6347:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10006/pid_6347/cgroup.procs: No such file or directory
W/ActivityManager(  997): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/NotificationManager( 6613): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6654): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6654): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AlertService( 6374): Beginning updateAlertNotification
I/ActivityManager(  997): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6681 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6681): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6681): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@258a9a40
,D/CalendarProvider2( 6681): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6681): Created com.android.providers.calendar.CalendarAlarmManager@3d535835(com.android.providers.calendar.CalendarProvider2@258a9a40)
D/AlertService( 6374): No fired or scheduled alerts
,I/NotificationManager( 6374): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(4) by com.android.calendar
,I/NotificationManager( 6374): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6374): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  997): Killing 6492:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/eas_req ( 6654): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/AlertService( 6374): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/libprocessgroup(  997): failed to open /acct/uid_10086/pid_6492/cgroup.procs: No such file or directory
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/ActivityManager(  997): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6705 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/AlarmScheduler( 6374): No events found starting within 1 week.
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ActivityManager(  997): Killing 6374:com.android.calendar/u0a13 (adj 15): empty #11
I/HubEmail( 6654): JNI_OnLoad()
I/HubEmail( 6654): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6654): registerNatives()
I/HubEmail( 6654): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6654): registerNativeMethods()
I/HubEmail( 6654): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6654): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/libprocessgroup(  997): failed to open /acct/uid_10013/pid_6374/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Killing 6114:com.android.vending/u0a36 (adj 15): empty #11
W/Settings( 6654): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  997): failed to open /acct/uid_10036/pid_6114/cgroup.procs: No such file or directory
I/ActivityManager(  997): Killing 5862:com.google.android.talk/u0a61 (adj 15): empty #11
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  997): failed to open /acct/uid_10061/pid_5862/cgroup.procs: No such file or directory
,D/LGDMClient( 6705): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6705): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LGDMClient( 6705): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6705): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6705): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6705): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6729 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6705): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6705): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6705): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6705): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6705): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  997): Killing 6539:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_1000/pid_6539/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6729): onCreate
,W/AppUp4:DB( 6729):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6729):  setFingerPrint start
I/AppUp4:DB( 6729):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6729):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6729):  SDK version = 0
I/AppUp4:DB( 6729):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6729): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6729): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6729): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6729): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6729): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6729): onReceive
I/AppUp4:CustModeStarterReceiver( 6729): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6729): Context : android.app.ReceiverRestrictedContext@2f5ae4ca
D/AppUp4:CustFacade( 6729): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6729): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6729): begin check event
I/AppUp4:CustModeStarterReceiver( 6729): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6729): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6729): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6729): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6729): handleAsyncCustNotification do not startCustService
I/ActivityManager(  997): Killing 6574:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5195): android.os.DeadObjectException
W/System.err( 5195): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5195): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5195): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5195): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5195): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5195): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5195): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5195): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 5195): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5195): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5195): android.os.DeadObjectException
W/System.err( 5195): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5195): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5195): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5195): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5195): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5195): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5195): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5195): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5195): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5195): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5195): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5195): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  997): failed to open /acct/uid_10089/pid_6574/cgroup.procs: No such file or directory
W/ActivityManager(  997): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  997): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6751 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LgeMiscReceiver( 3197): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3197): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3197): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6592): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6592): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3242): DownloadService onCreate
,I/DownloadManager( 3242): in removeSpuriousFiles
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@209ed7ef on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@6266d85 on behalf of 3242
I/ActivityManager(  997): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6777 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3242): DownloadService onStartCommand
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 24.903ms
,V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.289ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 20.908ms
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@fab040b on behalf of 3242
D/UEI.SmartControl( 6751): Quickset Services start...
I/UEI.SmartControl( 6751): Manufacture = LGE
D/UEI.SmartControl( 6751): File observer start...
E/UEI.SmartControl( 6751): IR Port is disabled: false
D/UEI.SmartControl( 6751): Starting file observer...
D/UEI.SmartControl( 6751): Extracting JNI libs...
D/UEI.SmartControl( 6751): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  997): Killing 6328:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6751): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6751): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6751): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6751): --- Selecting new region: 2
,I/UEI.SmartControl( 6751): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6751): Platform has CIR...
D/UEI.SmartControl( 6751): NO CIR support, need to check package...
I/UEI.SmartControl( 6751): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6751): QS Service created
W/libprocessgroup(  997): failed to open /acct/uid_1000/pid_6328/cgroup.procs: No such file or directory
,V/DownloadManager( 3242): DownloadService onDestroy
D/WeatherAncestor( 2683): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:41:59
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
,D/WeatherAncestor( 2683): connectivity changed - connection : true
D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:41:59
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
E/UEI.SmartControl( 6751): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  997): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6801 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  997): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/UEI.SmartControl( 6751): Loading JNI Libs...
,D/UEI.SmartControl( 6751):  configuring local db...
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6801): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6751):  ---- Has DB8: true
,D/UEI.SmartControl( 6751): QS start statue = true Error code = 0
D/UEI.SmartControl( 6751): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6751): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6751): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6751): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6751): IrrcClient ++ 
D/irrcClient( 6751): getIrrcService ++ 
D/irrcClient( 6751): getIrrcService -- 
D/irrcClient( 6751): IrrcClient -- 
W/irrc_jni( 6751): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6751): Services init done
,D/UEI.SmartControl( 6751): QS Service init finished
D/UEI.SmartControl( 6751): QS Service version name: 0.1.73
D/UEI.SmartControl( 6751): QS Service version code: 1073
D/UEI.SmartControl( 6751): Service requested: Control
I/UEI.SmartControl( 6751): Device manager: loading config....
D/UEI.SmartControl( 6751): Config is loaded...
,D/UEI.SmartControl( 6751):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6751): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6751): Request IControl service: devices are loaded...
I/ActivityManager(  997): Killing 5195:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6751): -----IControl: 11
D/UEI.SmartControl( 6751): Caller: com.lge.qremote
D/UEI.SmartControl( 6751): ------------ IControl registerCallback...
I/UEI.SmartControl( 6751): Registering callback...
,W/libprocessgroup(  997): failed to open /acct/uid_10106/pid_5195/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6751): Internal service binding...
D/WeatherService( 2683): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:42:0
D/WeatherService( 2683): 2 : TimeTick Intent And Screen On
D/WeatherService( 2683): 2 : SDK version : 21
W/ActivityManager(  997): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2683): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2683): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2683): 2 : Fixed theme : optimus
D/WeatherReflect( 2683): 2 : Map key string is -2
D/lim     ( 2683): 2 : time = 01:42
,I/WeatherReflect( 2683): Model Name : LG-D722
D/WeatherTheme( 2683): 2 : Different view - status_min_formatted : 41 != 42
D/WeatherTheme( 2683): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2683): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2683): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/art     ( 6801): CheckpointMarkThreadRoots callback created = 0xb042d4d0
D/Weather4x2_optimus( 2683): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2683): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2683): forecast size is 0
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2683): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2683): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
I/Babel_SMS( 6801): MmsConfig: mnc/mcc: 0/0
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Babel_SMS( 6801): MmsConfig.loadMmsSettings
D/Theme_WeatherAncestor_optimus( 2683): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2683): url is : null
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2683): 2 : update view, appWidgetId: 2
I/Babel_SMS( 6801): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6801): MmsConfig.loadFromDatabase
D/WeatherService( 2683): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:42:0
,I/art     ( 6801): CheckpointMarkThreadRoots callback created = 0xb042d4b0
E/Babel_SMS( 6801): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6801): MmsConfig.loadFromResources
E/Babel_SMS( 6801): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6801): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6801): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6801): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6801): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6801): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6801): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6801): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6801): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 6801): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6801): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6801): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6801): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6801): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6801): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6801): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6801): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6801): found sensor: Motion Accel, handle=46
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/Settings( 6801): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6801): startup - clean
I/Babel   ( 6801): deleted: false for 0
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/ActivityManager(  997): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6832 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6801): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6801): Unsupported mime audio/adpcm
W/AudioCapabilities( 6801): Unsupported mime audio/g726
W/AudioCapabilities( 6801): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6801): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6801): Unsupported mime video/mjpg
W/VideoCapabilities( 6801): Unsupported mime video/theora
,W/AudioCapabilities( 6801): Unsupported mime audio/evrc
,W/AudioCapabilities( 6801): Unsupported mime audio/qcelp
W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6801): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6801): Unsupported mime audio/qcelp
W/AudioCapabilities( 6801): Unsupported mime audio/evrc
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/VideoCapabilities( 6801): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6801): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6801): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6801): onServiceConnected
,W/Babel   ( 6801): Attempted to change video mute state without an active call.
I/NotificationManager( 6801): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6801): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6801): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6801): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6801): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6801): propertyValue:false
,I/Babel   ( 6801): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  997): Killing 6613:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
W/libprocessgroup(  997): failed to open /acct/uid_10081/pid_6613/cgroup.procs: No such file or directory
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6832): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6832): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6832): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6832): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6832): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6832):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6832):   adb logcat -s GAv4
W/GAv4    ( 6832): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6832): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6832): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6832): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6832): Time to load native libraries: 3 ms (timestamps 6484-6487)
,I/LibraryLoader( 6832): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6832): Binding Chromium to main looper Looper (main, tid 1) {205b9adf}
,I/LibraryLoader( 6832): Expected native library version number "",actual native library version number ""
I/chromium( 6832): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6832): Initializing chromium process, singleProcess=true
,W/art     ( 6832): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6832): ApplicationContext is null in ApplicationStatus
W/chromium( 6832): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6832): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6832): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6832): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6832): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6832): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6832): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6832): Remote Branch: 
I/Adreno-EGL( 6832): Local Patches: 
I/Adreno-EGL( 6832): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb4027400, uid 10079
,W/AudioManagerAndroid( 6832): Requires BLUETOOTH permission
I/NSApplication( 6832): Starting up...
,I/ActivityManager(  997): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6896 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 6681:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  997): failed to open /acct/uid_10014/pid_6681/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6918 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 6654:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10021/pid_6654/cgroup.procs: No such file or directory
,W/ResourcesManager( 6918): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5693): SYNC; picasa accounts
,D/NetworkLogImpl( 5693): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5693): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  997): Killing 6705:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 5693): num queued entries: 0
I/iu.UploadsManager( 5693): num updated entries: 0
I/iu.SyncManager( 5693): NEXT; no task
,W/libprocessgroup(  997): failed to open /acct/uid_1000/pid_6705/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6945 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicStore( 6945): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6945): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6945): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6945): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6945): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6945): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19a96106: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6945): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6945): GMSCore installation verified
,I/ConfigStore( 6945): Config Database version: 1
,I/MediaRouter( 6945): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6945): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6945): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6945): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  997): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6989 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6945): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/jxcore-log( 5518): Test app app.js loaded
I/jxcore-log( 5518): 
I/GoogleURLConnFactory( 6945): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6989): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6989): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5518): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18264904 added. We now have 1 listener(s)
D/BluetoothAdapterService(418267825)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f35260f
I/jxcore-log( 5518): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5518): 
,I/chromium( 5518): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     (  997): Explicit concurrent mark sweep GC freed 21436(1067KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.021ms total 152.210ms
,I/LGEmail ( 6989): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/ActivityManager(  997): Killing 6729:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/LGEmail ( 6989): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_6729/cgroup.procs: No such file or directory
,I/NotificationManager( 6945): com.google.android.music: cancel(1061) by com.google.android.music
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 6989): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  997): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7015 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6989): JNI_OnLoad()
,I/HubEmail( 6989): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6989): registerNatives()
I/HubEmail( 6989): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6989): registerNativeMethods()
I/HubEmail( 6989): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6989): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  997): Killing 6592:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10038/pid_6592/cgroup.procs: No such file or directory
W/Settings( 6989): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7015): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7015): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7015): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7015): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7015): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7015): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7045 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7015): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7015): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7015): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7015): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7015): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  997): Killing 6751:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10089/pid_6751/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7045): onCreate
,W/AppUp4:DB( 7045):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7045):  setFingerPrint start
I/AppUp4:DB( 7045):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7045):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7045):  SDK version = 0
I/AppUp4:DB( 7045):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7045): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7045): onReceive
I/AppUp4:CustModeStarterReceiver( 7045): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7045): Context : android.app.ReceiverRestrictedContext@2f5ae4ca
D/AppUp4:CustFacade( 7045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7045): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7045): begin check event
I/AppUp4:CustModeStarterReceiver( 7045): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7045): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7045): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7045): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7045): handleAsyncCustNotification do not startCustService
I/ActivityManager(  997): Killing 6777:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10051/pid_6777/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3197): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3197): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3197): networkInfo.isConnected() = false
I/ActivityManager(  997): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7064 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7064): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7064): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7064): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  997): Killing 6801:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7064): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7064): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7064): [parse] Load xml
,V/TelephonyAutoProfiling( 7064): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7064): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7064): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  997): failed to open /acct/uid_10061/pid_6801/cgroup.procs: No such file or directory
,V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3242): DownloadService onCreate
I/DownloadManager( 3242): in removeSpuriousFiles
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@6655d01 on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@a03d5e7 on behalf of 3242
,I/ActivityManager(  997): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7087 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3242): DownloadService onStartCommand
V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5693): Checkin interval check for package: unspecified last checkin: 1454460094162 min interval config: 0 actual interval: 30202
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@2849c83d on behalf of 3242
,I/CheckinService( 5693): Checking schedule, now: 1454460124401 next: 1454460124092
I/CheckinService( 5693): active receiver: enabled
V/DownloadManager( 3242): DownloadService onDestroy
,I/CheckinService( 5693): Preparing to send checkin request
D/WeatherAncestor( 2683): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:42:4
,D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherAncestor( 2683): connectivity changed - connection : true
D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:42:4
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/EventLogService( 5693): Accumulating logs since 1454460086364
I/ActivityManager(  997): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7111 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  997): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 22.260ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.795ms
W/ResourcesManager( 7111): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.947ms
,I/CheckinRequestBuilder( 5693): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5693): Failed to find provider info for com.google.android.wearable.settings
I/CheckinService( 5693): Done disabling old GoogleServicesFramework version
,I/Babel_SMS( 7111): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7111): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7111): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7111): MmsConfig.loadFromDatabase
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel_SMS( 7111): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7111): MmsConfig.loadFromResources
E/Babel_SMS( 7111): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7111): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7111): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7111): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7111): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7111): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7111): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7111): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7111): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7111): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7111): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7111): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7111): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7111): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7111): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7111): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7111): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7111): found sensor: Motion Accel, handle=46
,W/Settings( 7111): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7111): startup - clean
I/art     ( 7111): CheckpointMarkThreadRoots callback created = 0xaaf527f0
,I/Babel   ( 7111): deleted: false for 0
,I/art     ( 7111): CheckpointMarkThreadRoots callback created = 0xaaf527d0
I/ActivityManager(  997): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7147 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/AudioCapabilities( 7111): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7111): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7111): Unsupported mime audio/g726
W/AudioCapabilities( 7111): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7111): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7111): Unsupported mime video/mjpg
W/VideoCapabilities( 7111): Unsupported mime video/theora
W/ResourcesManager( 7147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioCapabilities( 7111): Unsupported mime audio/evrc
,W/AudioCapabilities( 7111): Unsupported mime audio/qcelp
W/VideoCapabilities( 7111): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7111): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7111): Unsupported mime audio/qcelp
W/AudioCapabilities( 7111): Unsupported mime audio/evrc
I/ActivityManager(  997): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7165 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/VideoCapabilities( 7111): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7111): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7111): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7111): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7111): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7111): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7111): onServiceConnected
W/Babel   ( 7111): Attempted to change video mute state without an active call.
I/MultiDex( 7147): VM with version 2.1.0 has multidex support
,I/MultiDex( 7147): install
I/MultiDex( 7147): VM has multidex support, MultiDex support library is disabled.
I/NotificationManager( 7111): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7111): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7111): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7111): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7111): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 7111): propertyValue:false
W/ResourcesManager( 7165): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/JNIHelp ( 7147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Babel   ( 7111): connection state changed from UNKNOWN to CONNECTED
,W/ActivityThread( 7147): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@209ed7ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7147): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  997): Process com.google.android.music:main (pid 6945) has died
I/NotificationManager( 7147): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7147): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7147): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7147): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/BluetoothManagerService(  997): Message: 20
,D/BluetoothManagerService(  997): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b0fd4b9:true
D/BluetoothAdapterService(418267825)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f35260f
,D/BluetoothAdapterService(418267825)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f35260f
,I/ActivityManager(  997): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7190 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/NativeLibraryUtils( 7147): Install completed successfully. count=14 extracted=0
V/LGMDMManager( 7165): Create singleton instance
,D/WVCdm   (  284): Instantiating CDM.
I/WVCdm   (  284): CdmEngine::OpenSession
,I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
I/AudioManager( 7165): getMode name:com.lge.qremote
W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
,I/ActivityManager(  997): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7209 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=2725949849
,D/UEI.SmartControl( 7190): Quickset Services start...
I/UEI.SmartControl( 7190): Manufacture = LGE
W/ResourcesManager( 7209): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/UEI.SmartControl( 7190): File observer start...
,E/UEI.SmartControl( 7190): IR Port is disabled: false
D/UEI.SmartControl( 7190): Starting file observer...
D/UEI.SmartControl( 7190): Extracting JNI libs...
D/UEI.SmartControl( 7190): --- this system supports 32-bit or 64-bit only
D/CalendarProvider2( 7209): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@258a9a40
D/UEI.SmartControl( 7190): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7190): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7190): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/CalendarProvider2( 7209): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7209): Created com.android.providers.calendar.CalendarAlarmManager@3d535835(com.android.providers.calendar.CalendarProvider2@258a9a40)
D/CalendarProviderBroadcastReceiver( 7209): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7209): [IntentService] WakeLock acquire, start IntentSerivce
,I/UEI.SmartControl( 7190): --- Selecting new region: 2
I/UEI.SmartControl( 7190): -- Running on KitKat(19) and above! JNI will be used.
,D/CalendarProvider2( 7209): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7209): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/UEI.SmartControl( 7190): Platform has CIR...
D/CalendarProvider2( 7209): [getOrCreateCalendarAlarmManager]
D/UEI.SmartControl( 7190): NO CIR support, need to check package...
I/UEI.SmartControl( 7190): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7190): QS Service created
I/ActivityManager(  997): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7231 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/UEI.SmartControl( 7190): QS start get config
,D/UEI.SmartControl( 7190): Loading JNI Libs...
,D/UEI.SmartControl( 7190):  configuring local db...
I/ActivityManager(  997): Process com.lge.email (pid 6989) has died
,D/CalendarProvider2( 7209): [IntentService] Release Lock
,D/CalendarProvider2( 7209): CalendarProviderIntentService.onDestroy()
I/art     ( 7147): CheckpointMarkThreadRoots callback created = 0xb04ccea0
,I/art     ( 7147): CheckpointMarkThreadRoots callback created = 0xb04cce90
,I/MusicStore( 7231): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/UEI.SmartControl( 7190):  ---- Has DB8: true
D/UEI.SmartControl( 7190): QS start statue = true Error code = 0
D/UEI.SmartControl( 7190): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7190): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7190): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7190): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7190): IrrcClient ++ 
,D/irrcClient( 7190): getIrrcService ++ 
D/irrcClient( 7190): getIrrcService -- 
D/irrcClient( 7190): IrrcClient -- 
W/irrc_jni( 7190): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7190): Services init done
I/UEI.SmartControl( 7190): Device manager: loading config....
,D/UEI.SmartControl( 7190): QS Service init finished
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 7190): QS Service version name: 0.1.73
D/UEI.SmartControl( 7190): QS Service version code: 1073
,D/UEI.SmartControl( 7190): Service requested: Control
W/ResourcesManager( 7231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/UEI.SmartControl( 7190): Config is loaded...
V/JNIHelp ( 7231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 7190):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7190): Request IControl service: devices are loaded...
I/UEI.SmartControl( 7190): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7190): -----IControl: 11
D/UEI.SmartControl( 7190): Caller: com.lge.qremote
D/UEI.SmartControl( 7190): ------------ IControl registerCallback...
I/UEI.SmartControl( 7190): Registering callback...
D/UEI.SmartControl( 7190): -----IControl: 19
D/UEI.SmartControl( 7190): Caller: com.lge.qremote
I/UEI.SmartControl( 7190): Registering Services Ready callback...
I/UEI.SmartControl( 7190): Notify client services are ready...
D/UEI.SmartControl( 7190): -----IControl: 8
D/UEI.SmartControl( 7190): Caller: com.lge.qremote
D/UEI.SmartControl( 7190): Internal service binding...
I/ActivityManager(  997): Killing 7015:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ActivityThread( 7231): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19a96106: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7231): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7231): GMSCore installation verified
,W/libprocessgroup(  997): failed to open /acct/uid_1000/pid_7015/cgroup.procs: No such file or directory
,I/ConfigStore( 7231): Config Database version: 1
,I/WVCdm   (  284): CdmEngine::OpenSession
,I/art     (  997): Explicit concurrent mark sweep GC freed 18839(1101KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.138ms total 135.306ms
,I/MediaRouter( 7231): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7231): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  997): Killing 7045:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_7045/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7231): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  997): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7267 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7231): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7231): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  997): Killing 7064:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/ResourcesManager( 7267): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7267): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7267): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  997): failed to open /acct/uid_10038/pid_7064/cgroup.procs: No such file or directory
,I/LGEmail ( 7267): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 7231): com.google.android.music: cancel(1061) by com.google.android.music
,D/LGEmail ( 7267): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7267): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  997): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7290 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7267): JNI_OnLoad()
I/HubEmail( 7267): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7267): registerNatives()
I/HubEmail( 7267): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7267): registerNativeMethods()
I/HubEmail( 7267): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7267): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  997): Killing 7087:com.lge.drmservice/u0a51 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  997): failed to open /acct/uid_10051/pid_7087/cgroup.procs: No such file or directory
W/Settings( 7267): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7290): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7290): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7290): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7290): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7290): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7290): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7314 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7290): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7290): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7290): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7290): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7290): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  997): Killing 7111:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10061/pid_7111/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7314): onCreate
W/AppUp4:DB( 7314):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7314):  setFingerPrint start
I/AppUp4:DB( 7314):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7314):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7314):  SDK version = 0
I/AppUp4:DB( 7314):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7314): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7314): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7314): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7314): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7314): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7314): onReceive
I/AppUp4:CustModeStarterReceiver( 7314): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7314): Context : android.app.ReceiverRestrictedContext@2f5ae4ca
,D/AppUp4:CustFacade( 7314): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7314): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7314): begin check event
I/AppUp4:CustModeStarterReceiver( 7314): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7314): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7314): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7314): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7314): handleAsyncCustNotification do not startCustService
I/ActivityManager(  997): Killing 6832:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=1941105076
W/libprocessgroup(  997): failed to open /acct/uid_10079/pid_6832/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3197): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3197): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3197): networkInfo.isConnected() = true
D/PhoneState( 3197): setPdpRejectCasuse : false
I/ActivityManager(  997): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7334 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  997): RTC_WAKEUP set : Alarm{1f83312b type 0 when 1454460128078 com.android.vending} when 1454460128078
,I/ActivityManager(  997): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7349 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7349): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7349): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7349): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3242): DownloadService onCreate
I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3242): in removeSpuriousFiles
D/PhoneMonitor( 7349): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7349): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7349): [parse] Load xml
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 7349): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7349): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@18048700 on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@50fab39 on behalf of 3242
,D/PhoneMonitor( 7349): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  997): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7380 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3242): DownloadService onStartCommand
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 23.231ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.297ms
,V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.934ms
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@205b9adf on behalf of 3242
I/CheckinService( 5693): Checkin interval check for package: unspecified last checkin: 1454460094162 min interval config: 0 actual interval: 34365
,D/Finsky  ( 7334): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
I/ActivityManager(  997): Killing 6896:com.android.chrome/u0a48 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/WeatherAncestor( 2683): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:42:8
W/libprocessgroup(  997): failed to open /acct/uid_10048/pid_6896/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherAncestor( 2683): connectivity changed - connection : true
D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:42:8
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  997): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7406 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  997): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3242): DownloadService onDestroy
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/Finsky  ( 7334): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/ResourcesManager( 7406): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Settings( 7334): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7334): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7334): com.android.vending: cancel(-1050172287) by com.android.vending
,I/art     ( 6521): Explicit concurrent mark sweep GC freed 1983(85KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 396us total 26.712ms
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@33b6c1f5 on behalf of 7334
,D/Finsky  ( 7334): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7334): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  997): Killing 6918:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/Ads     ( 7334): Skipping gmscore version check
,W/libprocessgroup(  997): failed to open /acct/uid_10086/pid_6918/cgroup.procs: No such file or directory
,V/AlarmManager(  997): RTC_WAKEUP set : Alarm{c6d45f6 type 0 when 1454460124092 com.google.android.gms} when 1454460124092
D/Finsky  ( 7334): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7334): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel_SMS( 7406): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7406): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7406): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7406): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7406): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7406): MmsConfig.loadFromResources
E/Babel_SMS( 7406): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7406): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7406): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7406): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7406): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7406): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7406): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7406): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7406): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7406): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7406): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7406): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7406): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7406): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7406): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7406): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7406): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7406): found sensor: Motion Accel, handle=46
I/art     ( 7406): CheckpointMarkThreadRoots callback created = 0xb042d480
,W/Settings( 7406): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7406): startup - clean
I/Babel   ( 7406): deleted: false for 0
,I/art     ( 7406): CheckpointMarkThreadRoots callback created = 0xb042d460
I/ActivityManager(  997): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7447 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7406): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7406): Unsupported mime audio/adpcm
W/AudioCapabilities( 7406): Unsupported mime audio/g726
W/AudioCapabilities( 7406): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7406): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7406): Unsupported mime video/mjpg
W/VideoCapabilities( 7406): Unsupported mime video/theora
,D/Finsky  ( 7334): [945] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7334): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  997): Killing 7165:com.lge.qremote/u0a106 (adj 15): empty #11
W/AudioCapabilities( 7406): Unsupported mime audio/evrc
,W/AudioCapabilities( 7406): Unsupported mime audio/qcelp
W/VideoCapabilities( 7406): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7406): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7406): Unsupported mime audio/qcelp
W/AudioCapabilities( 7406): Unsupported mime audio/evrc
W/VideoCapabilities( 7406): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7406): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7406): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7406): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7406): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7406): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  997): failed to open /acct/uid_10106/pid_7165/cgroup.procs: No such file or directory
,I/vclib   ( 7406): onServiceConnected
W/Babel   ( 7406): Attempted to change video mute state without an active call.
,I/NotificationManager( 7406): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7406): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7406): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7406): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7406): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 7406): propertyValue:false
I/Babel   ( 7406): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  997): Killing 7190:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/libprocessgroup(  997): failed to kill 1 processes for processgroup 7190
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7447): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7447): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7447): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7447): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7447): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7447):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7447):   adb logcat -s GAv4
,W/GAv4    ( 7447): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7447): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7447): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  997): tsOffsetIs: Apps: 115251039337; DSPS: 3874385; Offset : -2997279433
I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): L3 Terminate.
I/dex2oat ( 7494): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 7447): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7447): Time to load native libraries: 2 ms (timestamps 5524-5526)
I/LibraryLoader( 7447): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7447): Binding Chromium to main looper Looper (main, tid 1) {205b9adf}
,I/LibraryLoader( 7447): Expected native library version number "",actual native library version number ""
I/chromium( 7447): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7447): Initializing chromium process, singleProcess=true
,W/art     ( 7447): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7447): ApplicationContext is null in ApplicationStatus
,I/dex2oat ( 7494): dex2oat took 135.136ms (threads: 4)
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7147): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7147): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7147): Remote Branch: 
I/Adreno-EGL( 7147): Local Patches: 
I/Adreno-EGL( 7147): Reconstruct Branch: 
,W/chromium( 7447): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7447): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7447): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7447): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7447): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7447): Remote Branch: 
I/Adreno-EGL( 7447): Local Patches: 
I/Adreno-EGL( 7447): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb4027340, uid 10079
,W/AudioManagerAndroid( 7447): Requires BLUETOOTH permission
I/NSApplication( 7447): Starting up...
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7147): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7147): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7147): Remote Branch: 
I/Adreno-EGL( 7147): Local Patches: 
I/Adreno-EGL( 7147): Reconstruct Branch: 
,I/ActivityManager(  997): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7529 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 7209:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10014/pid_7209/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7147): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7147): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7147): Remote Branch: 
I/Adreno-EGL( 7147): Local Patches: 
I/Adreno-EGL( 7147): Reconstruct Branch: 
,I/ActivityManager(  997): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7548 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  997): Killing 7231:com.google.android.music:main/u0a81 (adj 15): empty #11
I/CheckinRequestBuilder( 5693): Classify the device as Phone.
W/libprocessgroup(  997): failed to open /acct/uid_10081/pid_7231/cgroup.procs: No such file or directory
,W/ResourcesManager( 7548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 5693): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5693): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5693): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5693): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5693): propertyValue:false
D/libc-netbsd( 5693): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5693): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  997): Killing 7267:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10021/pid_7267/cgroup.procs: No such file or directory
,I/ActivityManager(  997): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7579 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/libc-netbsd( 5693): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5693): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5693): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5693): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7579): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/CheckinTask( 5693): Sending checkin request (9705 bytes)
D/BluetoothManagerService(  997): Message: 20
,D/BluetoothManagerService(  997): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@236427ea:true
,I/art     (  997): Explicit concurrent mark sweep GC freed 25683(1171KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.355ms total 140.561ms
,D/BluetoothAdapterService(418267825)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f35260f
D/BluetoothAdapterService(418267825)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f35260f
I/AudioManager( 7579): getMode name:com.lge.qremote
,I/AudioManager( 7579): getMode name:com.lge.qremote
,I/ActivityManager(  997): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7597 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/CheckinRequestBuilder( 5693): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5693): Failed to find provider info for com.google.android.wearable.settings
I/Gmail   ( 7597): getAccountsCursor
,W/GAV2    ( 7597): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicWidget( 2614): mDelayedStopHandler : unbind
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2705): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2705): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2705): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2705): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2705): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/MusicBrowser( 2705): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,E/Gmail   ( 7597): Error finding the version of the Email provider.....
E/Gmail   ( 7597): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7597): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7597): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7597): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7597): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7597): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7597): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7597): We do not support migrating this version of the Email provider.
I/MediaFocusControl(  997):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3d28142bcom.lge.music.MediaPlaybackService$6@477e088
D/MusicBrowser( 2705): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2705): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3baa8396
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2705): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2705): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2705): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/Gmail   ( 7597): getAccountsCursor
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2705): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/CheckinRequestBuilder( 5693): Classify the device as Phone.
I/MusicBrowser( 2705): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2705): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2705): reset
I/ActivityManager(  997): Killing 7290:com.lge.lgdmsclient/1000 (adj 15): empty #11
V/MediaPlayer[Native]( 2705): setListener
V/MediaPlayer[Native]( 2705): disconnect
V/MediaPlayer[Native]( 2705): destructor
,V/AudioFlinger(  284): releasing 19 from 2705 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/MediaPlayer[Native]( 2705): disconnect
D/MusicBrowser( 2705): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2705): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2705): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2705): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2705): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2705): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2705): [SmartShareManagerClient] unregisterListener: 514079265
W/SmartShareClient( 2705): [SmartShareManagerClient] unregisterListener invalid listener: 514079265
I/SmartShareClient( 2705): [SmartShareManagerClient] terminate service: 2705/MediaPlaybackService/882842220
E/HomeCloudIF( 2705): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2705): [SmartShareManagerClient] unbindService context:android.app.Application@2c28fe46
W/libprocessgroup(  997): failed to open /acct/uid_1000/pid_7290/cgroup.procs: No such file or directory
,W/ActivityManager(  997): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7597): Observing account changes for notifications
W/ActivityManager(  997): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/CheckinTask( 5693): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/LocationInitializer( 5693): Restart initialization of location
I/CheckinService( 5693): Checking schedule, now: 1454460132367 next: 1454987381359
I/CheckinService( 5693): active receiver: disabled
V/CloudHub( 2705): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2705): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2705): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2705): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2705): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  997): Killing 7314:com.lge.appbox.client/u0a11 (adj 15): empty #11
E/MDM     ( 1733): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/CloudHub( 2705): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29961
,W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_7314/cgroup.procs: No such file or directory
,I/CheckinService( 5693): Checking schedule, now: 1454460132452 next: 1454987381359
I/CheckinService( 5693): active receiver: disabled
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CheckinService( 5693): Recording last checkin time for package unspecified as 1454460132465
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
D/Finsky  ( 7334): [950] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/NotificationManager(  997): android: cancelAsUser(2) by android
,I/Gmail   ( 7597): notifyAccountChanged
,I/Gmail   ( 7597): getAccountsCursor
I/Gmail   ( 7597): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7597): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7597): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7597): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd( 7334): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7334): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7334): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7334): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  997): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7661 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 7334): propertyValue:false
V/LGMDMManager( 7579): Create singleton instance
,I/Gmail   ( 7597): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7661): Quickset Services start...
,I/UEI.SmartControl( 7661): Manufacture = LGE
D/UEI.SmartControl( 7661): File observer start...
E/UEI.SmartControl( 7661): IR Port is disabled: false
D/UEI.SmartControl( 7661): Starting file observer...
D/UEI.SmartControl( 7661): Extracting JNI libs...
D/UEI.SmartControl( 7661): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7579): getMode name:com.lge.qremote
,E/MDM     ( 1733): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5693): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7579): getMode name:com.lge.qremote
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/UEI.SmartControl( 7661): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7661): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7661): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AudioManager( 7579): getMode name:com.lge.qremote
I/CheckinService( 5693): Checkin interval check for package: unspecified last checkin: 1454460132465 min interval config: 0 actual interval: 333
,D/PowerManagerServiceEx(  997): releaseWakeLockInternal: lock=148296566 [*alarm*], flags=0x0
I/AudioManager( 7579): getMode name:com.lge.qremote
I/UEI.SmartControl( 7661): --- Selecting new region: 2
I/UEI.SmartControl( 7661): -- Running on KitKat(19) and above! JNI will be used.
I/CheckinService( 5693): Checking schedule, now: 1454460132812 next: 1454987381359
I/CheckinService( 5693): active receiver: disabled
D/UEI.SmartControl( 7661): Platform has CIR...
,D/UEI.SmartControl( 7661): NO CIR support, need to check package...
W/ContextImpl( 3619): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/UEI.SmartControl( 7661): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7661): QS Service created
E/UEI.SmartControl( 7661): QS start get config
,V/SetupWizard( 7349): Connected to Gservices successfully
,D/UEI.SmartControl( 7661): Loading JNI Libs...
,D/UEI.SmartControl( 7661):  configuring local db...
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7661):  ---- Has DB8: true
,D/UEI.SmartControl( 7661): QS start statue = true Error code = 0
D/UEI.SmartControl( 7661): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7661): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7661): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7661): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7661): IrrcClient ++ 
D/irrcClient( 7661): getIrrcService ++ 
D/irrcClient( 7661): getIrrcService -- 
D/irrcClient( 7661): IrrcClient -- 
W/irrc_jni( 7661): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7661): Services init done
,I/UEI.SmartControl( 7661): Device manager: loading config....
D/UEI.SmartControl( 7661): QS Service init finished
D/UEI.SmartControl( 7661): QS Service version name: 0.1.73
D/UEI.SmartControl( 7661): QS Service version code: 1073
D/UEI.SmartControl( 7661): Config is loaded...
D/UEI.SmartControl( 7661): Service requested: Control
D/UEI.SmartControl( 7661): Internal service binding...
D/UEI.SmartControl( 7661):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7661): -----IControl: 11
,I/UEI.SmartControl( 7661): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7661): Caller: com.lge.qremote
D/UEI.SmartControl( 7661): ------------ IControl registerCallback...
I/UEI.SmartControl( 7661): Registering callback...
D/UEI.SmartControl( 7661): -----IControl: 19
D/UEI.SmartControl( 7661): Caller: com.lge.qremote
I/UEI.SmartControl( 7661): Registering Services Ready callback...
I/UEI.SmartControl( 7661): Notify client services are ready...
D/UEI.SmartControl( 7661): -----IControl: 8
D/UEI.SmartControl( 7661): Caller: com.lge.qremote
I/AudioManager( 7579): getMode name:com.lge.qremote
,I/ActivityManager(  997): Killing 7447:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/ActivityManager(  997): Killing 7380:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  997): failed to open /acct/uid_10079/pid_7447/cgroup.procs: No such file or directory
,W/libprocessgroup(  997): failed to open /acct/uid_10051/pid_7380/cgroup.procs: No such file or directory
I/AudioManager( 7579): getMode name:com.lge.qremote
I/AudioManager( 7579): getMode name:com.lge.qremote
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:42:14.288 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  997): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  997): Handling package changes for user 0
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7730 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7406): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7730): onCreate
,W/AppUp4:DB( 7730):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7730):  setFingerPrint start
I/AppUp4:DB( 7730):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
V/JNIHelp ( 7406): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:DB( 7730):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7730):  SDK version = 0
I/AppUp4:DB( 7730):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7730): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7730): onReceive
I/AppUp4:CustModeStarterReceiver( 7730): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7730): Context : android.app.ReceiverRestrictedContext@c8a371f
D/AppUp4:CustFacade( 7730): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7730): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7730): begin check event
I/AppUp4:CustModeStarterReceiver( 7730): Event For Nothing, skip.
W/System  ( 7406): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7406): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  997): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  997): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  997): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  997): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  997): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7751 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourcesManager(  997): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  997): Explicit concurrent mark sweep GC freed 20790(1046KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.871ms total 204.035ms
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
V/BackupManagerService(  997): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  997): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@31f9c640
W/ResourcesManager( 7751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7751): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7751): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  997): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7751): Total System Memory = 906309632
I/GalleryUtils( 7751): Application Heap = 96 MB
,I/AppConfig( 7751): App Tier : NOT_DEF
D/SystemHelper( 7751): region [EU], country [EU], operator [OPEN], sub-operator []
D/LocationProviderProxy(  997): applying state to connected service
,I/ActivityManager(  997): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7774 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  997): Killing 7529:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10048/pid_7529/cgroup.procs: No such file or directory
,W/ResourcesManager( 7774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7774): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7774): BUILD Country: EU
,I/SystemConfig( 7774): BUILD Operator: OPEN
I/SystemConfig( 7774): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7774): existFile = false
I/SystemConfig( 7774): canReadFile = false
I/SystemConfig( 7774): systemFeature RCS result false
,D/SystemConfig( 7774): refreshRcsSupport() :false
I/ActivityManager(  997): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7796 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 7548:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 27.692ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.830ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 25.066ms
,W/libprocessgroup(  997): failed to open /acct/uid_10086/pid_7548/cgroup.procs: No such file or directory
I/ActivityManager(  997): Killing 2705:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  284): 2705 died, releasing its sessions
V/AudioFlinger(  284):  pid 1743 @ 0
V/AudioFlinger(  284):  pid 3197 @ 1
V/AudioFlinger(  284):  pid 3197 @ 2
,I/LockScreenSettings( 7796): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/libprocessgroup(  997): failed to open /acct/uid_10028/pid_2705/cgroup.procs: No such file or directory
,D/LockScreenSettings( 7796): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7796): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7796): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7796): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7796): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  997): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7819 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  997): Killing 7334:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10036/pid_7334/cgroup.procs: No such file or directory
,W/ResourcesManager( 7819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  997): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7844 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  997): Killing 7349:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
,W/libprocessgroup(  997): failed to open /acct/uid_10038/pid_7349/cgroup.procs: No such file or directory
,D/Finsky  ( 7844): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7844): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7844): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7844): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7844): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@2c676b8a on behalf of 7844
D/Finsky  ( 7844): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7844): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7844): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7844): Skipping gmscore version check
D/PackageBroadcastService( 5693): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5693): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7844): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  997): Killing 7661:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/Icing   ( 5693): updateResources: need to parse f{com.google.android.gms}
,W/System.err( 7579): android.os.DeadObjectException
,W/System.err( 7579): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7579): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7579): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7579): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7579): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7579): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7579): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7579): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7579): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7579): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7579): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7579): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7579): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7579): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7579): IControl.unregisterCallback error: android.os.DeadObjectException
,W/System.err( 7579): android.os.DeadObjectException
W/System.err( 7579): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7579): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7579): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7579): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7579): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7579): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7579): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7579): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7579): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7579): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7579): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7579): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7579): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7579): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7579): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  997): failed to open /acct/uid_10089/pid_7661/cgroup.procs: No such file or directory
W/ActivityManager(  997): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  997): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7901 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7901): Quickset Services start...
,I/UEI.SmartControl( 7901): Manufacture = LGE
D/UEI.SmartControl( 7901): File observer start...
E/UEI.SmartControl( 7901): IR Port is disabled: false
D/UEI.SmartControl( 7901): Starting file observer...
D/UEI.SmartControl( 7901): Extracting JNI libs...
D/UEI.SmartControl( 7901): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7901): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7901): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7901): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/GAV2    ( 7597): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 5693): Google Analytics 8.4.89 is starting up.
,I/UEI.SmartControl( 7901): --- Selecting new region: 2
,I/UEI.SmartControl( 7901): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7901): Platform has CIR...
D/UEI.SmartControl( 7901): NO CIR support, need to check package...
I/UEI.SmartControl( 7901): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7901): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/UEI.SmartControl( 7901): QS start get config
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 01:42:17.314 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7901): Loading JNI Libs...
,D/UEI.SmartControl( 7901):  configuring local db...
D/UEI.SmartControl( 7901):  ---- Has DB8: true
,D/UEI.SmartControl( 7901): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7901): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7901): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7901): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7901): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7901): IrrcClient ++ 
D/irrcClient( 7901): getIrrcService ++ 
,D/irrcClient( 7901): getIrrcService -- 
D/irrcClient( 7901): IrrcClient -- 
W/irrc_jni( 7901): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7901): Services init done
I/UEI.SmartControl( 7901): Device manager: loading config....
D/UEI.SmartControl( 7901): QS Service init finished
,D/UEI.SmartControl( 7901): QS Service version name: 0.1.73
D/UEI.SmartControl( 7901): QS Service version code: 1073
D/UEI.SmartControl( 7901): Config is loaded...
D/UEI.SmartControl( 7901): Service requested: Control
D/UEI.SmartControl( 7901):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7901): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7901): Request IControl service: devices are loaded...
,I/ActivityManager(  997): Killing 7597:com.google.android.gm/u0a53 (adj 15): empty #11
D/UEI.SmartControl( 7901): -----IControl: 11
D/UEI.SmartControl( 7901): Caller: com.lge.qremote
D/UEI.SmartControl( 7901): ------------ IControl registerCallback...
I/UEI.SmartControl( 7901): Registering callback...
D/UEI.SmartControl( 7901): -----IControl: 19
D/UEI.SmartControl( 7901): Caller: com.lge.qremote
I/UEI.SmartControl( 7901): Registering Services Ready callback...
I/UEI.SmartControl( 7901): Notify client services are ready...
D/UEI.SmartControl( 7901): -----IControl: 8
D/UEI.SmartControl( 7901): Caller: com.lge.qremote
,W/libprocessgroup(  997): failed to open /acct/uid_10053/pid_7597/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7901): Internal service binding...
I/AudioManager( 7579): getMode name:com.lge.qremote
I/AudioManager( 7579): getMode name:com.lge.qremote
,I/AudioManager( 7579): getMode name:com.lge.qremote
,I/Icing   ( 5693): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5693): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  997): Killing 7730:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10011/pid_7730/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  997): Killing 7406:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  997): failed to open /acct/uid_10061/pid_7406/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/charger_monitor(  491): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7901): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 135251873756; DSPS: 4529772; Offset : -2997268781
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{948e985 type 2 when 148207 com.google.android.gms} when 148207
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1454460163353 tag=VacuumService
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 47805(3MB) AllocSpace objects, 33(528KB) LOS objects, 40% free, 13MB/22MB, paused 1.719ms total 120.186ms
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 12356 seconds from now (1454460163899)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  997): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  997): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  997): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  997): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  997): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PowerManagerService(  997): ALS enabled for SRE
,D/PowerManagerServiceEx(  997): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (31708 ms ago)
D/qdlights(  997): set_light_backlight: 252
,D/qdlights(  997): set_light_backlight: 249
D/qdlights(  997): set_light_backlight: 246
,D/qdlights(  997): set_light_backlight: 242
,D/qdlights(  997): set_light_backlight: 239
,D/qdlights(  997): set_light_backlight: 236
,D/qdlights(  997): set_light_backlight: 232
,D/qdlights(  997): set_light_backlight: 229
,D/qdlights(  997): set_light_backlight: 226
,D/qdlights(  997): set_light_backlight: 222
,D/qdlights(  997): set_light_backlight: 219
,D/qdlights(  997): set_light_backlight: 216
,D/qdlights(  997): set_light_backlight: 212
,D/qdlights(  997): set_light_backlight: 209
,D/qdlights(  997): set_light_backlight: 206
,D/qdlights(  997): set_light_backlight: 202
,D/qdlights(  997): set_light_backlight: 199
,D/qdlights(  997): set_light_backlight: 196
,D/qdlights(  997): set_light_backlight: 192
,D/qdlights(  997): set_light_backlight: 189
,D/qdlights(  997): set_light_backlight: 186
,D/qdlights(  997): set_light_backlight: 182
,D/qdlights(  997): set_light_backlight: 179
,D/qdlights(  997): set_light_backlight: 176
,D/qdlights(  997): set_light_backlight: 172
,D/qdlights(  997): set_light_backlight: 169
,D/qdlights(  997): set_light_backlight: 166
,D/qdlights(  997): set_light_backlight: 162
,D/qdlights(  997): set_light_backlight: 159
,D/qdlights(  997): set_light_backlight: 156
,D/qdlights(  997): set_light_backlight: 152
,D/qdlights(  997): set_light_backlight: 149
,D/qdlights(  997): set_light_backlight: 146
,D/qdlights(  997): set_light_backlight: 142
,D/qdlights(  997): set_light_backlight: 139
,D/qdlights(  997): set_light_backlight: 136
,D/qdlights(  997): set_light_backlight: 132
,D/qdlights(  997): set_light_backlight: 129
,D/qdlights(  997): set_light_backlight: 126
,D/qdlights(  997): set_light_backlight: 122
,D/qdlights(  997): set_light_backlight: 119
,D/qdlights(  997): set_light_backlight: 116
,D/qdlights(  997): set_light_backlight: 112
,D/qdlights(  997): set_light_backlight: 109
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  997): set_light_backlight: 106
D/qdlights(  997): set_light_backlight: 102
,D/qdlights(  997): set_light_backlight: 99
,D/qdlights(  997): set_light_backlight: 96
,D/qdlights(  997): set_light_backlight: 92
,D/qdlights(  997): set_light_backlight: 89
,D/qdlights(  997): set_light_backlight: 86
,D/qdlights(  997): set_light_backlight: 82
,D/qdlights(  997): set_light_backlight: 79
,D/qdlights(  997): set_light_backlight: 76
,D/qdlights(  997): set_light_backlight: 72
,D/qdlights(  997): set_light_backlight: 69
,D/qdlights(  997): set_light_backlight: 66
,D/qdlights(  997): set_light_backlight: 62
,D/qdlights(  997): set_light_backlight: 59
,D/qdlights(  997): set_light_backlight: 56
,D/qdlights(  997): set_light_backlight: 52
,D/qdlights(  997): set_light_backlight: 49
,D/qdlights(  997): set_light_backlight: 46
,D/qdlights(  997): set_light_backlight: 42
,D/qdlights(  997): set_light_backlight: 39
,D/qdlights(  997): set_light_backlight: 36
,D/qdlights(  997): set_light_backlight: 32
,D/qdlights(  997): set_light_backlight: 29
,D/qdlights(  997): set_light_backlight: 26
,D/qdlights(  997): set_light_backlight: 22
,D/qdlights(  997): set_light_backlight: 19
,D/qdlights(  997): set_light_backlight: 16
,D/qdlights(  997): set_light_backlight: 12
,D/qdlights(  997): set_light_backlight: 10
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 155252560884; DSPS: 5185154; Offset : -2997255071
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  997): ALS enabled for SRE
D/PowerManagerServiceEx(  997): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (38694 ms ago)
I/PowerManagerService(  997): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  997): ALS enabled for SRE
D/PowerManagerServiceEx(  997): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (38709 ms ago)
,W/ContextImpl(  997): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  997): Sleeping (uid 1000)...
,D/LPWGController(  997): [updateScreenState] screen on = false
D/LPWGController(  997): disable proximity sensor
D/LPWGController(  997): enable proximity sensor
,I/SensorManager(  997): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2b0f36ad] by com.android.server.power.ProximitySensorListener.enable():120
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
I/sensors_hal_Ctx(  997): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  997): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  997): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  997): activate: handle is 48, enable
,V/sensors_hal_Ctx(  997): activate sensors is 1400000000000
D/sensors_hal_Thresh(  997): enable: handle=48
I/sensors_hal_SAM(  997): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  997): waitForResponse: timeout=1000
V/sensors_hal_SAM(  997): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  997): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  997): enable: Received response: 0
D/PowerManagerServiceEx(  997): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (38775 ms ago)
I/Adreno-EGL(  997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  997): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  997): Build Date: 03/02/15 Mon
I/Adreno-EGL(  997): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  997): Remote Branch: 
I/Adreno-EGL(  997): Local Patches: 
I/Adreno-EGL(  997): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (984 us)
,I/Sensors (  425): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  997): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  997): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  997): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  997): processInd: handle 48, count=1
V/sensors_hal_Thresh(  997): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  997): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  997): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  997): poll: count: 256
I/sensors_hal_Ctx(  997): poll: released wakelock sensor_ind
D/sensors_hal_Util(  997): waitForResponse: timeout=0
D/LPWGController(  997): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  997): current mode = 1  value = 1 1
I/LPWGController(  997): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  997): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  997): set_light_backlight: 0
,I/SensorManager(  997): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  997): activate: handle is 46, disable
V/sensors_hal_Ctx(  997): activate sensors is 1000000000000
D/sensors_hal_LP2(  997): enable: handle=46
D/sensors_hal_LP2(  997): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  997): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  997): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  997): Display changed displayId=0
,V/sensors_hal_SAM(  997): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  997): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  997): Excessive delay in setPowerMode(): 177ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/art     (  997): Explicit concurrent mark sweep GC freed 45051(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.721ms total 183.762ms
,I/QCOM PowerHAL(  997): Got set_interactive hint
D/DSDPConnection( 1743): Display #0 changed.
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/WifiServerServiceExt(  997): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 997
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
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
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WifiServerServiceExt(  997): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,D/GpsLocationProvider(  997): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
,I/LEDService( 1793): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1793): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1793): stopPatternFlashing()
D/qdlights( 1793): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1793): lockStatus = 0
I/LEDService( 1793): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1793): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/LEDService( 1793): updateLightsLocked : turn off led
D/qdlights( 1793): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1793): RESTART MSG
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
D/Ulp_jni (  997): JNI:system_update. Event-0
D/SplitWindow(  997): check instance of lgWin Window{3765dc30 u0 SearchPanel}
,D/InputDispatcher(  997): Window went away: Window{36cbe8b3 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:42:55
,D/WeatherService( 2683): 2 : ACTION screen on
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:42:55
,W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): ACTION_SCREEN_ON
D/AppCleanupService( 4088): android.intent.action.SCREEN_ON
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 997
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  997): CMD_SCREEN_OFF 
D/WifiController(  997): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  997): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1841): |CORE| sendScreenState: state:false
,I/LEDService( 1793): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1793): stopPatternFlashing()
D/qdlights( 1793): set_light_notifications: 0,0,0,0,3
I/LEDService( 1793): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1793): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1793): clear
I/Cliptray Service( 1793): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/LEDService( 1793): updateLightsLocked : turn on led
E/LEDService( 1793): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1793): Can't handle this request of patternId:0
D/LEDHandler( 1793): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:42:55
,D/WeatherService( 2683): 2 : ACTION screen off
D/WeatherService( 2683): 2 : TimeTick Receiver Unregister
D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:42:55
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  997): ACTION_SCREEN_OFF
D/AppCleanupService( 4088): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4088): AppUsageStatsSaveTask
,I/Sensors (  425): sns_pwr.c(301):releasing wakelock
,E/NxpNfcJni( 1785): getReconnectState = 0x0
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
,D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{1c9590a9 type 2 when 164671 com.android.systemui} when 164671
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1743): getCallState : 0
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 175253239210; DSPS: 5840537; Offset : -2997276514
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  997): acquireWakeLockInternal: lock=148296566, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=997
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{978462e type 2 when 184142 android} when 184142
D/PowerManagerServiceEx(  997): releaseWakeLockInternal: lock=148296566 [*alarm*], flags=0x0
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{232c15cf type 2 when 190458 com.google.android.gms} when 190458
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 195253919723; DSPS: 6495919; Offset : -2997267050
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 215254559351; DSPS: 7151300; Offset : -2997268889
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 235255165697; DSPS: 7806680; Offset : -2997273545
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 255255841679; DSPS: 8462062; Offset : -2997268638
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  997): acquireWakeLockInternal: lock=148296566, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=997
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{15848b5c type 2 when 272161 android} when 272161
D/PowerManagerServiceEx(  997): releaseWakeLockInternal: lock=148296566 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 275256465265; DSPS: 9117442; Offset : -2997255508
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 295257100518; DSPS: 9772823; Offset : -2997260681
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  491): init target 500000
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 315257697489; DSPS: 10428203; Offset : -2997274061
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 335258359096; DSPS: 11083584; Offset : -2997254105
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  997): remove bfa0e44
D/LocationManagerService(  997): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  997): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  997): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  997): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  997): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 355259035963; DSPS: 11738967; Offset : -2997279065
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 375259623716; DSPS: 12394346; Offset : -2997270182
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 395260516157; DSPS: 13049735; Offset : -2997263167
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 415261272035; DSPS: 13705119; Offset : -2997239502
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 435261871559; DSPS: 14360499; Offset : -2997250643
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 455262526759; DSPS: 15015881; Offset : -2997266543
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 475263113158; DSPS: 15671260; Offset : -2997259952
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 495263773619; DSPS: 16326642; Offset : -2997271059
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 515264355590; DSPS: 16982021; Offset : -2997268636
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 535264943393; DSPS: 17637400; Offset : -2997260797
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 555265536044; DSPS: 18292780; Offset : -2997278655
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 575266189421; DSPS: 18948161; Offset : -2997265861
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 595266854779; DSPS: 19603543; Offset : -2997271863
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 615267458156; DSPS: 20258922; Offset : -2997248606
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 635268105179; DSPS: 20914304; Offset : -2997273414
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 655268693974; DSPS: 21569683; Offset : -2997263722
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 675269350320; DSPS: 22225064; Offset : -2997248376
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 695269936927; DSPS: 22880444; Offset : -2997272068
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 715270902806; DSPS: 23535835; Offset : -2997252182
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 735271564777; DSPS: 24191217; Offset : -2997262092
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 755272142478; DSPS: 24846596; Offset : -2997263757
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 775272772054; DSPS: 25501977; Offset : -2997275310
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 795273366108; DSPS: 26157356; Offset : -2997261012
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 815274016049; DSPS: 26812737; Offset : -2997251914
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 835274746666; DSPS: 27468121; Offset : -2997253407
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 855275367596; DSPS: 28123502; Offset : -2997273581
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 875276077484; DSPS: 28778885; Offset : -2997265804
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 895276825133; DSPS: 29434269; Offset : -2997250578
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 915277481844; DSPS: 30089651; Offset : -2997265228
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 935278148190; DSPS: 30745033; Offset : -2997270217
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  997): acquireWakeLockInternal: lock=148296566, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=997
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{310d8e65 type 2 when 953355 com.android.bluetooth} when 953355
,W/bt-smp  ( 1970): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1970): Plain text(LSB ~ MSB) = 13 ca 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1970): Encrypted text(LSB ~ MSB) = ef 0f f4 3f e6 ca c2 95 b8 64 52 65 3b e6 30 84 
W/bt-btm  ( 1970): Stopping oneshot timer
I/ActivityManager(  997): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8111 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8111): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8111): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@c8a371f
I/ActivityManager(  997): Killing 7751:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  997): failed to open /acct/uid_10023/pid_7751/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx(  997): releaseWakeLockInternal: lock=148296566 [*alarm*], flags=0x0
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 955278668599; DSPS: 31400410; Offset : -2997268737
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 975279276665; DSPS: 32055790; Offset : -2997270813
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  997): ELAPSED_WAKEUP set : Alarm{b46973a type 2 when 994765 com.google.android.gms} when 994765
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 995279873896; DSPS: 32711169; Offset : -2997253181
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1015280777952; DSPS: 33366559; Offset : -2997264601
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1035281451121; DSPS: 34021941; Offset : -2997263001
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1055282042416; DSPS: 34677320; Offset : -2997251514
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1075282674125; DSPS: 35332701; Offset : -2997260439
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1095283273807; DSPS: 35988081; Offset : -2997271396
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1115283997028; DSPS: 36643464; Offset : -2997250001
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1135284721916; DSPS: 37298848; Offset : -2997257665
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1155285317846; DSPS: 37954228; Offset : -2997272191
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1175285993567; DSPS: 38609609; Offset : -2997237600
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1195286584706; DSPS: 39264989; Offset : -2997256499
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1215287257146; DSPS: 39920371; Offset : -2997257087
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  997): User[0] Flushing usage stats to disk
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1235287844430; DSPS: 40575750; Offset : -2997248023
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1255288439214; DSPS: 41231130; Offset : -2997263669
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  491): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1793): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1793): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1793): Battery Level Remaining: 100%
D/LEDHandler( 1793): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  997): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  997): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  997): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1275289042748; DSPS: 41886510; Offset : -2997270381
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8194): 
D/AndroidRuntime( 8194): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8194): CheckJNI is OFF
D/AndroidRuntime( 8194): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  997): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  997): Killing 5518:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  997): WIN DEATH: Window{5244ab2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  997): Skipping PackageSetting{2052777f com.example.hello/10317} due to missing metadata
D/InputDispatcher(  997): Focus left window: Window{5244ab2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  997): Window went away: Window{5244ab2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  997):   Force finishing activity ActivityRecord{bbba5a2 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  997): Display changed displayId=0
D/DSDPConnection( 1743): Display #0 changed.
W/ActivityManager(  997): Spurious death for ProcessRecord{3ffe3feb 5518:com.test.thalitest/u0a316}, curProc for 5518: null
I/ActivityManager(  997): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  997):   Force finishing activity ActivityRecord{bbba5a2 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  997): Duplicate finish request for ActivityRecord{bbba5a2 u0 com.test.thalitest/.MainActivity t222 f}
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 1937): Explicit concurrent mark sweep GC freed 7569(430KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 3.230ms total 81.566ms
I/InputReader(  997): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3619): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3619): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3619): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3619): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3619): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3619): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3619): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3619): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3619): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3619): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3619): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3619): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  997): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8224 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 5693): Explicit concurrent mark sweep GC freed 6694(347KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/18MB, paused 865us total 160.113ms
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1373): createShortcutInfo...
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     (  997): Explicit concurrent mark sweep GC freed 43225(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 2.750ms total 217.779ms
I/art     (  997): WaitForGcToComplete blocked for 40.563ms for cause Explicit
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1373): handleShortcutListChanged...
W/ResourcesManager( 8224): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8224): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8224): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/SystemUI[Framework](  997): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/InputDispatcher(  997): Focus entered window: Window{4628dbb u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/PhoneWindowManagerEx(  997): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  997): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  997): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  997): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a64fd9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  997): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  997): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  997): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  997): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  997): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  997): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a64fd9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  997): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/administrator(  997): Handling package changes for user 0
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): handleShortcutListChanged...
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  997): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  997): Got RemoteException sending setActive(false) notification to pid 5518 uid 10316
I/LGEmail ( 8224): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 8224): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  997): Timeline: Activity_windows_visible id: ActivityRecord{3ead0e24 u0 com.lge.launcher2/.Launcher t221} time:1295151
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService(  997): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  997): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  997): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  997): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1622): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/sensors_hal_Time(  997): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  997): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  997): tsOffsetIs: Apps: 1295289665813; DSPS: 42541890; Offset : -2997257251
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/art     (  997): Explicit concurrent mark sweep GC freed 6235(364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.093ms total 421.769ms
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/PackageChangeReceiver( 8224): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AndroidRuntime( 8194): Shutting down VM
I/ActivityManager(  997): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8254 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  997): Killing 7774:com.android.contacts/u0a18 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/libprocessgroup(  997): failed to open /acct/uid_10018/pid_7774/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8254): onCreate
W/AppUp4:DB( 8254):  [AppBoxDatabaseHelper] construct
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 8254):  setFingerPrint start
I/AppUp4:DB( 8254):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8254):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8254):  SDK version = 0
I/AppUp4:DB( 8254):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8254): AppBoxApplication onCreate()
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
D/AppUp4:PreloadHelper( 8254): added Exclude : com.test.thalitest
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  997): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8271 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  997): Killing 7147:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  997): failed to open /acct/uid_10006/pid_7147/cgroup.procs: No such file or directory
W/ResourcesManager( 8271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8271): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8271): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8271): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8271): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 1879): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@18a363eb time:1295816
E/SQLiteDatabase( 8271): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8271): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8271): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8271): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8271): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8271): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8271): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8271): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8271): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8271): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8271): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8271): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8271): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8271): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8271): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8271): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8271): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8271): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8271): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8271): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 8271): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8271): FATAL EXCEPTION: main
E/AndroidRuntime( 8271): Process: com.android.settings, PID: 8271
E/AndroidRuntime( 8271): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8271): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8271): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8271): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8271): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8271): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8271): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8271): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8271): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8271): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8271): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8271): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8271): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8271): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8271): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8271): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8271): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8271): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 8271): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8271): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8271): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8271): 	... 11 more
E/DropBoxManagerService(  997): Can't write: system_app_crash
E/DropBoxManagerService(  997): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  997): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  997): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  997): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  997): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  997): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  997): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  997): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  997): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  997): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  997): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  997): 	... 5 more

```
