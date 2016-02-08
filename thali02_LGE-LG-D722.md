#### Test 58380500962e22b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/SystemConfig( 5263): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5263): existFile = false
I/SystemConfig( 5263): canReadFile = false
I/SystemConfig( 5263): systemFeature RCS result false
D/SystemConfig( 5263): refreshRcsSupport() :false
,--------- beginning of system
I/ActivityManager(  841): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5287 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  841): Killing 4808:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10006/pid_4808/cgroup.procs: No such file or directory
W/ActivityManager(  841): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
I/LockScreenSettings( 5287): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5287): New app installed broadcast received ..
I/LockScreenSettings( 5287): Number of installed packages  1
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/ActivityManager(  841): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5306 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  841): Killing 4170:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10006/pid_4170/cgroup.procs: No such file or directory
D/EulaProviderUpdateObserver( 5306): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5306): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5079): android.intent.action.PACKAGE_ADDED : com.test.thalitest
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  841): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5323 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  841): Killing 5001:com.lge.clock/u0a10 (adj 15): empty #11
D/AndroidRuntime( 5304): 
D/AndroidRuntime( 5304): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5304): CheckJNI is OFF
W/libprocessgroup(  841): failed to open /acct/uid_10010/pid_5001/cgroup.procs: No such file or directory
D/AndroidRuntime( 5304): Calling main entry com.android.commands.am.Am
I/ActivityManager(  841): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  841): setTaskToReturnTo : TaskRecord{34ce4605 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  841): setTaskToReturnTo : TaskRecord{34ce4605 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  841): AppWindowTokenEx init.. 
D/ContextHelper(  841): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  841): Focus left window: Window{1ad7c45e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5304): Shutting down VM
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  841): check instance of lgWin Window{3d8ea67 u0 Starting com.test.thalitest}
I/ActivityManager(  841): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5368 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  841): Starting window displayed
I/HotwordDetector( 1959): Closing mic
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f5163f7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = 8000000
D/BarTransitions( 1374): draw background and invalidate : color = 6060606
I/MicrophoneInputStream( 1959): mic_close com.google.android.apps.gsa.speech.audio.u@3db331e5
V/AudioRecord( 1959): stop()
D/AudioRecord( 1959): AudioRecord->stop()
,V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb42a4000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  279): setParameters(): io 17, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1959): stop()
V/AudioRecord( 1959): stop()
V/AudioRecord( 1959): stop()
V/AudioFlinger(  279): releasing 16 from 1959 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1959): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  841): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2699): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread 0xb42a4000 exiting
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioSystem( 3203): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1959, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioSystem( 1987): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1959): Stopping hotword detection.
I/HotwordRecognitionRnr( 1959): Hotword detection finished
D/ContextHelper( 5368): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5368): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5368): Time to load native libraries: 2 ms (timestamps 9128-9130)
I/LibraryLoader( 5368): Expected native library version number "",actual native library version number ""
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AlertService( 3757): Beginning updateAlertNotification
D/AlertService( 3757): No fired or scheduled alerts
I/NotificationManager( 3757): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(8) by com.android.calendar
V/WebViewChromiumFactoryProvider( 5368): Binding Chromium to main looper Looper (main, tid 1) {3184e6ad}
I/NotificationManager( 3757): com.android.calendar: cancel(9) by com.android.calendar
I/GAv4    ( 5323): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5323):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5323):   adb logcat -s GAv4
I/NotificationManager( 3757): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(12) by com.android.calendar
I/LibraryLoader( 5368): Expected native library version number "",actual native library version number ""
I/NotificationManager( 3757): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(17) by com.android.calendar
I/chromium( 5368): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/NotificationManager( 3757): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3757): com.android.calendar: cancel(20) by com.android.calendar
W/GAv4    ( 5323): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/BrowserStartupController( 5368): Initializing chromium process, singleProcess=true
W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5368): ApplicationContext is null in ApplicationStatus
D/AlertService( 3757): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3757): No events found starting within 1 week.
W/chromium( 5368): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/GAv4    ( 5323): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5323): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/libEGL  ( 5368): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5368): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5368): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5368): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5368): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5368): Remote Branch: 
I/Adreno-EGL( 5368): Local Patches: 
I/Adreno-EGL( 5368): Reconstruct Branch: 
W/AnalyticsTrackerProxyImpl( 5323): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
V/AudioPolicyService(  279): registerClient() client 0xb436f7e0, uid 10316
D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36b6f644:true
D/BluetoothAdapterService(213270697)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@339d1fc7
I/ActivityManager(  841): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5423 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{2a139ba type 2 when 79486 android} when 79486
,I/GservicesProvider( 5423): Gservices pushing to system: true; secure/global: true
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 5323): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5323): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AwContents( 5368): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5448 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 5100:com.google.android.music:main/u0a81 (adj 15): empty #11
I/GoogleHttpClient( 5423): GMS http client unavailable, use old client
D/SystemWebViewEngine( 5368): CordovaWebView is running on device made by: LGE
,W/libprocessgroup(  841): failed to open /acct/uid_10081/pid_5100/cgroup.procs: No such file or directory
,W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5368): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5423): GMS http client unavailable, use old client
,W/ResourcesManager( 5448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 5323): CheckpointMarkThreadRoots callback created = 0xaaf2d410
,I/Activity( 5368): Activity.onPostResume() called 
,D/OpenGLRenderer( 5368): Render dirty regions requested: true
I/OpenGLRenderer( 5368): Initialized EGL, version 1.4
I/art     ( 5323): CheckpointMarkThreadRoots callback created = 0xaaf2d3f0
,D/OpenGLRenderer( 5368): Enabling debug mode 0
V/JNIHelp ( 5323): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Atlas   ( 5368): Validating map...
,D/SplitWindow(  841): check instance of lgWin Window{3ebf593f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5368): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  841): Killing 5152:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/System  ( 5323): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5323): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  841): failed to open /acct/uid_10014/pid_5152/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InputDispatcher(  841): Focus entered window: Window{3ebf593f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  841): Displayed com.test.thalitest/.MainActivity: +1s341ms
I/Timeline(  841): Timeline: Activity_windows_visible id: ActivityRecord{207865a u0 com.test.thalitest/.MainActivity t222} time:80007
,W/InputMethodManagerService(  841): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/Timeline( 5368): Timeline: Activity_idle id: android.os.BinderProxy@34322160 time:80028
,W/BindingManager( 5368): Cannot call determinedVisibility() - never saw a connection for the pid: 5368
,I/ActivityManager(  841): Killing 5178:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10021/pid_5178/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5502 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1959): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/JsMessageQueue( 5368): Set native->JS mode to OnlineEventsBridgeMode
,I/UpdateIcingCorporaServi( 1959): UpdateCorporaTask done [took 181 ms] updated apps [took 180 ms] 
,D/jxcore_app_log( 5368): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622892544
,I/chromium( 5368): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 5502): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 5368): CheckpointMarkThreadRoots callback created = 0x9f5555a0
I/art     ( 5368): CheckpointMarkThreadRoots callback created = 0x9f555570
,D/Finsky  ( 5502): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5502): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5502): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5502): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@2959d345 on behalf of 5502
,I/NotificationManager( 5502): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5502): Skipping gmscore version check
,D/Finsky  ( 5502): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5502): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5502): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  841): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5544 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5502): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5502): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  841): Killing 5207:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10009/pid_5207/cgroup.procs: No such file or directory
W/ResourcesManager( 5544): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5544): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5544): VM with version 2.1.0 has multidex support
I/MultiDex( 5544): install
I/MultiDex( 5544): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5544): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5544): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5544): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c565825: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5544): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5544): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5544): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5544): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5544): Reading stored module config
D/ChimeraCfgMgr( 5544): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5544): Loading module APK com.google.android.play.games
,D/NativeLibraryUtils( 5544): Install completed successfully. count=14 extracted=0
,I/art     (  841): Explicit concurrent mark sweep GC freed 20254(994KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.953ms total 177.489ms
,I/art     ( 5544): CheckpointMarkThreadRoots callback created = 0xb042d350
,I/art     ( 5544): CheckpointMarkThreadRoots callback created = 0xb042d330
,W/jxcore-log( 5368): Initializing JXcore engine
,W/jxcore-log( 5368): JXcore engine is ready
D/ChimeraCfgMgr( 5544): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5544): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5544): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/Thread-646( 5520): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6348]" dev="sockfs" ino=6348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-646( 5520): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-646( 5520): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8724]" dev="sockfs" ino=8724 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-646( 5520): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-646( 5520): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-646( 5520): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25195]" dev="sockfs" ino=25195 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
D/AsyncTaskServiceImpl( 5544): Submit a task: k
,W/jxcore-log( 5368): Starting JXcore engine
,D/ChimeraCfgMgr( 5544): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleDatabaseHelper( 5544): cleanUpNonGplusAccounts done.
,D/ChimeraCfgMgr( 5544): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5544): Processing package: com.test.thalitest
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GassUtils( 5544): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5544): Found info for package com.test.thalitest in db.
,D/LocationInitializer( 5544): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5544): Using Auth Proxy for data requests.
,I/art     ( 5544): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5544): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 5544): Storage manager: low false usage 1.74MB avail 2.38GB capacity 4.06GB
W/jxcore-log( 5368): Platform android
W/jxcore-log( 5368): 
W/jxcore-log( 5368): Process ARCH arm
W/jxcore-log( 5368): 
,I/ActivityManager(  841): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5593 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,E/BaseAppContext( 5544): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5544): Using Auth Proxy for data requests.
,W/BaseAppContext( 5544): Using Auth Proxy for data requests.
,W/BaseAppContext( 5544): Using Auth Proxy for data requests.
,W/BaseAppContext( 5544): Using Auth Proxy for data requests.
W/BaseAppContext( 5544): Using Auth Proxy for data requests.
W/IcingInternalCorpora( 5544): getNumBytesRead when not calculated.
,W/BaseAppContext( 5544): Using Auth Proxy for data requests.
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/art     ( 5544): Suspending all threads took: 8.210ms
,I/art     ( 5544): Background sticky concurrent mark sweep GC freed 15702(1416KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 11.205ms total 75.749ms
,I/Gmail   ( 5593): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5593): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/jxcore-log( 5368): JXcore Cordova bridge is ready!
I/jxcore-log( 5368): 
W/jxcore-log( 5368): JXcore engine is started
,I/ActivityManager(  841): Process com.android.gallery3d (pid 5244) has died
,W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  841): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5593): Error finding the version of the Email provider.....
E/Gmail   ( 5593): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5593): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5593): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5593): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5593): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5593): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5593): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5593): We do not support migrating this version of the Email provider.
,W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5593): getAccountsCursor
,I/Gmail   ( 5593): Observing account changes for notifications
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5544): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5649 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager(  841): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{a72e193 type 0 when 1454886891203 com.android.providers.contacts} when 1454886891203
V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{3e5705d0 type 2 when 59328 com.google.android.talk} when 59328
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{cac98ce type 0 when 1454973338542 com.google.android.googlequicksearchbox} when 1454973338542
,D/ChimeraCfgMgr( 5544): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5544): Module APK com.google.android.play.games already loaded
I/jxcore-log( 5368): Toggling radios to true
I/jxcore-log( 5368): 
D/BluetoothAdapter( 5368): enable(): BT is already enabled..!
,I/ActivityManager(  841): Process com.android.contacts (pid 5263) has died
,D/WifiServiceImplEx(  841): setWifiEnabled: true pid=5368, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
D/WifiService(  841): setWifiEnabled: true pid=5368, uid=10316
,D/WifiServiceImplEx(  841): disconnect pid=5368, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  841): reconnect pid=5368, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5368): Radios toggled
I/jxcore-log( 5368): 
I/jxcore-log( 5368): My device name is: LGE-LG-D722
I/jxcore-log( 5368): 
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/art     ( 5544): Background sticky concurrent mark sweep GC freed 9979(777KB) AllocSpace objects, 6(96KB) LOS objects, 7% free, 13MB/14MB, paused 7.074ms total 51.266ms
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2762): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  841): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,I/Gmail   ( 5593): notifyAccountChanged
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Gmail   ( 5593): getAccountsCursor
I/Gmail   ( 5593): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGWifiP2pService(  841): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  841): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  841): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CommandListener(  275): Clearing all IP addresses on wlan0
,I/Gmail   ( 5593): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
D/InitAlarmsService( 3757): Clearing and rescheduling alarms.
,V/NativeCrypto( 1732): Read error: ssl=0xb0456c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb0456c00: I/O error during system call, Broken pipe
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  841): ignoring duplicate network state non-change
D/WifiHS20(  841): hidePasspointNotification off =false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/Gmail   ( 5593): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:38.877 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  841): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): ValidatedState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=-13ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Forcing reevaluation
I/ActivityManager(  841): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5677 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 5593): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/WifiStateMachine(  841): Start Disconnecting Watchdog 1
,D/WifiHS20(  841): hidePasspointNotification off =false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/art     (  301): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 24.832ms
,I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-SCAN-STARTED 
I/art     (  301): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.960ms
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:38.97 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 22.482ms
,D/PhoneMonitor( 5649): Register our PhoneStateListener
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/ConnectivityService(  841): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  841): disableDataServiceNotify
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/WifiNetworkAgent(  841): NetworkAgent: NetworkAgent channel lost
,D/DSQN    (  841): stop dsqn bin
D/ConnectivityService(  841): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  841): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Disconnected - quitting
D/CSLegacyTypeTracker(  841): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  841): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  841): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  841): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ProcessCpuTracker(  841): Skipping unknown process pid 5689
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiHS20(  841): hidePasspointNotification off =false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:39.048 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DhcpStateMachine(  841): StoppedState
D/DhcpStateMachine(  841): StoppedState{ when=-112ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  841): hidePasspointNotification off =false
D/NetworkManagementService(  841): Removing idletimer
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateSCANNING
D/Tethering(  841): MasterInitialState.processMessage what=3
D/Tethering(  841): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:39.058 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:39.059 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1840): |CORE| No family connected
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
W/Settings(  841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NetworkPolicy(  841): [LG_RESTRICTED] !!!isConnected  type  :1
,V/NetworkPolicy(  841): [LG_RESTRICTED] !!!isConnected  type  :1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 5649): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 5677): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/TelephonyAutoProfiling( 5649): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5649): [parse] Load xml
V/TelephonyAutoProfiling( 5649): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5649): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PhoneMonitor( 5649): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/InstanceID/Rpc( 5544): Found 10006
,D/CalendarProvider2( 5677): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@13785218
,I/art     ( 5423): Explicit concurrent mark sweep GC freed 8112(406KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.092ms total 172.672ms
,D/CalendarProvider2( 5677): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5677): Created com.android.providers.calendar.CalendarAlarmManager@3184e6ad(com.android.providers.calendar.CalendarProvider2@13785218)
D/CalendarProvider2( 5677): Scheduling check of next Alarm
,I/Icing   ( 5544): Internal init done: storage state 0
D/CalendarProvider2( 5677): SCHEDULE_ALARM_REMOVE
I/Icing   ( 5544): Post-init done
,I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5713 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/NotificationManager( 5544): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  841): Killing 3757:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10013/pid_3757/cgroup.procs: No such file or directory
,I/Gmail   ( 5593): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5713): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  841): Explicit concurrent mark sweep GC freed 31193(1442KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.222ms total 150.986ms
,I/Babel_SMS( 5713): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5713): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5713): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5713): MmsConfig.loadFromDatabase
E/Babel_SMS( 5713): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5713): MmsConfig.loadFromResources
,E/Babel_SMS( 5713): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5713): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5713): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5713): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5713): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5713): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5713): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 5713): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5713): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5713): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5713): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5713): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5713): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5713): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5713): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5713): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5713): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5713): found sensor: Motion Accel, handle=46
I/art     ( 5713): CheckpointMarkThreadRoots callback created = 0xaaf58430
,W/Settings( 5713): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5713): startup - clean
I/art     ( 5713): CheckpointMarkThreadRoots callback created = 0xaaf58410
,I/Babel   ( 5713): deleted: false for 0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2762): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/AudioCapabilities( 5713): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5713): Unsupported mime audio/adpcm
W/AudioCapabilities( 5713): Unsupported mime audio/g726
W/AudioCapabilities( 5713): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5713): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5713): Unsupported mime video/mjpg
W/VideoCapabilities( 5713): Unsupported mime video/theora
,D/LocSvc_java(  841): onReceive
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.115 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.119 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateASSOCIATING
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2762): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.154 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.16 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/wpa_supplicant( 2762): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateGROUP_HANDSHAKE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/WifiServiceExtension(  841): setVHTCapabilityType  : false
W/AudioCapabilities( 5713): Unsupported mime audio/evrc
W/AudioCapabilities( 5713): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5713): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5713): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5713): Unsupported mime audio/evrc
I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5744 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/WifiServerServiceExt(  841): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  841): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  841): setSecurityType  : 2
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.25 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.251 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/AudioManager( 4983): getMode name:com.lge.qremote
D/ConnectivityService(  841): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  841): Got NetworkAgent Messenger
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  841): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AudioManager( 4983): getMode name:com.lge.qremote
D/CommandListener(  275): Setting iface cfg
E/WifiStateMachine(  841): Start Dhcp Watchdog 2
D/DhcpStateMachine(  841): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  841): WaitBeforeStartState
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/AudioManager( 4983): getMode name:com.lge.qremote
W/VideoCapabilities( 5713): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5713): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
I/AudioManager( 4983): getMode name:com.lge.qremote
,W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
I/AudioManager( 4983): getMode name:com.lge.qremote
D/UEI.SmartControl( 5744): Quickset Services start...
,I/UEI.SmartControl( 5744): Manufacture = LGE
I/ActivityManager(  841): Killing 5227:com.lge.appbox.client/u0a11 (adj 15): empty #11
E/MDM     ( 1732): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/UEI.SmartControl( 5744): File observer start...
E/UEI.SmartControl( 5744): IR Port is disabled: false
D/UEI.SmartControl( 5744): Starting file observer...
D/UEI.SmartControl( 5744): Extracting JNI libs...
I/CalendarProvider2( 5677): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
E/WifiStateMachine(  841): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  841): Current State is mWaitBeforeStartState.
D/UEI.SmartControl( 5744): --- this system supports 32-bit or 64-bit only
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2749f9f target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2749f9f target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  841): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  841): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/DhcpStateMachine(  841): DHCP Start wake lock is acquired.
W/ContentResolver( 5677): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_5227/cgroup.procs: No such file or directory
,D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LocationInitializer( 5544): Restart initialization of location
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/vclib   ( 5713): onServiceConnected
W/Babel   ( 5713): Attempted to change video mute state without an active call.
I/ActivityManager(  841): Killing 5287:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  841): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  841): ignoring duplicate network state non-change
I/NotificationManager( 5713): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/DhcpStateMachine(  841): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  841): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  841): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Icing   ( 5544): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/dhcpcd  ( 5766): version 5.5.6 starting
,E/dhcpcd  ( 5766): get_duid: Read-only file system
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.617 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
W/libprocessgroup(  841): failed to open /acct/uid_10069/pid_5287/cgroup.procs: No such file or directory
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  841): Adding iface wlan0 to network 101
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.632 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  841): [PASSPOINT] passpointNotification: hs20AP list is checked
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiStateMachine(  841): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  841): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.655 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:40.661 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,E/ConnectivityService(  841): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  841): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
D/ConnectivityService(  841): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  841): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  841): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  841): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  841): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  841): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  841):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  841): currentScore = 0, newScore = 20
D/ConnectivityService(  841):    accepting network in place of null
D/ConnectivityService(  841): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  841): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  841): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  841): [e] list.add(nai) empty : false size: 1
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  841): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  841): validation of new default Network = false
D/ConnectivityService(  841): Default network via Wi-Fi connected. start DSQN
D/WIFI    (  841): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/DSQN    (  841): enableDataServiceNotify 
D/DSQN    (  841): start dsqn bin
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  841): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] wait 500ms before dns check
,V/NetworkPolicy(  841): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  841): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DSQN    ( 5776): DSQN samuel.seo ver 141203
E/DSQN    ( 5776): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5776): created command queue thread
I/DSQN    ( 5776): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5776): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/dhcpcd  ( 5766): wlan0: rebinding lease of 192.168.1.134
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/AudioManager( 4983): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/AudioManager( 4983): getMode name:com.lge.qremote
I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 10090
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
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
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
I/CheckinService( 5544): Disabling old GoogleServicesFramework version
,D/Icing   ( 5544): Loaded CLD2 Version V2.0 - 20141016
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  841): Handling package changes for user 0
D/UEI.SmartControl( 5744): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5744): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5744): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/ResourcesManager( 5713): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5713): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UEI.SmartControl( 5744): --- Selecting new region: 2
I/UEI.SmartControl( 5744): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5744): Platform has CIR...
,I/NotificationManager( 5713): com.google.android.talk: cancel(8) by com.google.android.talk
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5788 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/UEI.SmartControl( 5744): NO CIR support, need to check package...
,I/UEI.SmartControl( 5744): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5744): QS Service created
I/Icing   ( 5544): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,E/UEI.SmartControl( 5744): QS start get config
,V/JNIHelp ( 5713): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] DNSResolver start dns
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  841): Process com.google.android.apps.docs (pid 5323) has died
D/UEI.SmartControl( 5744): Loading JNI Libs...
D/UEI.SmartControl( 5744):  configuring local db...
,I/NotificationService(  841): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  841): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  841): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Checking http://clients3.google.com/generate_204 on "NG700"
,V/BackupManagerService(  841): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  841): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@383f77bd
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  841): identical MTU - not setting
D/Nat464Xlat(  841): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  841): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/DSQN    ( 5776): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5776): restart monitoring
I/DSQN    ( 5776): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  841): DSQM DsqnNotification wlan0  1
D/DSQN    (  841): start to monitor internet connection
D/ConnectivityService(  841): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/System  ( 5713): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5713): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  841): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  841): enableDataServiceNotify 
D/DSQN    (  841): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/CheckinService( 5544): Checking schedule, now: 1454973341321 next: 1454973360709
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:41.322 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/CheckinService( 5544): active receiver: disabled
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 23:15:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454973341328], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454973341310]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Validated
D/WifiDataContinuityService(  841): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  841): set CMD_CAPTIVE_CHECK_COMPLETED
,D/DSQN    (  841): dsqn is running restart
,D/ConnectivityService(  841): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  841): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  841): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/WIFI    (  841): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/DSQN    ( 5809): DSQN samuel.seo ver 141203
E/DSQN    ( 5809): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5809): created command queue thread
I/DSQN    ( 5809): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5809): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/AppUp4:AppBoxCP( 5788): onCreate
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
W/AppUp4:DB( 5788):  [AppBoxDatabaseHelper] construct
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/AppUp4:DB( 5788):  setFingerPrint start
I/AppUp4:DB( 5788):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5788):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5788):  SDK version = 0
I/AppUp4:DB( 5788):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5788): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5788): onReceive
I/AppUp4:CustModeStarterReceiver( 5788): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/AppUp4:CustFacade( 5788): Context : android.app.ReceiverRestrictedContext@1d17d2d7
D/AppUp4:CustFacade( 5788): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5788): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5788): begin check event
I/AppUp4:CustModeStarterReceiver( 5788): Event For Nothing, skip.
,I/ActivityManager(  841): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5814 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5744):  ---- Has DB8: true
D/UEI.SmartControl( 5744): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5744): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5744): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5744): IRRCDataComm has AudioManager!!!!.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/irrc_jni( 5744): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5744): IrrcClient ++ 
D/irrcClient( 5744): getIrrcService ++ 
,D/irrcClient( 5744): getIrrcService -- 
D/irrcClient( 5744): IrrcClient -- 
W/irrc_jni( 5744): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5744): Services init done
,D/UEI.SmartControl( 5744): QS Service init finished
I/UEI.SmartControl( 5744): Device manager: loading config....
D/UEI.SmartControl( 5744): QS Service version name: 0.1.73
D/UEI.SmartControl( 5744): QS Service version code: 1073
D/UEI.SmartControl( 5744): Service requested: Control
D/UEI.SmartControl( 5744): Config is loaded...
,D/ConnectivityService(  841): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
W/ResourcesManager( 5814): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5814): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5744):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5744): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5744): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5744): Internal service binding...
W/ResourcesManager( 5814): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5744): -----IControl: 11
D/UEI.SmartControl( 5744): Caller: com.lge.qremote
D/UEI.SmartControl( 5744): ------------ IControl registerCallback...
I/UEI.SmartControl( 5744): Registering callback...
D/UEI.SmartControl( 5744): -----IControl: 19
D/UEI.SmartControl( 5744): Caller: com.lge.qremote
I/UEI.SmartControl( 5744): Registering Services Ready callback...
I/UEI.SmartControl( 5744): Notify client services are ready...
D/UEI.SmartControl( 5744): -----IControl: 8
,D/UEI.SmartControl( 5744): Caller: com.lge.qremote
W/ResourceType(  841): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  841): Killing 5306:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_5306/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5766): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/dhcpcd  ( 5766): wlan0: leased 192.168.1.134 for 86400 seconds
,I/ActivityManager(  841): Process com.lge.bnr (pid 5079) has died
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppConfig( 5814): Total System Memory = 906309632
I/GalleryUtils( 5814): Application Heap = 96 MB
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/AppConfig( 5814): App Tier : NOT_DEF
,D/SystemHelper( 5814): region [EU], country [EU], operator [OPEN], sub-operator []
D/LocationProviderProxy(  841): applying state to connected service
,D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  841): onReceive
D/LocSvc_java(  841): got connectivity action
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  841): broadcast - no network connections
D/LocSvc_java(  841): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  841): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  841): onReceive
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
D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  841): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5854 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 5854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5854): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5854): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5854): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5854): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  841): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  841): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  841): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  841): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  841): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  841): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  841): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  841): RunningState
I/SystemConfig( 5854): BUILD Country: EU
I/SystemConfig( 5854): BUILD Operator: OPEN
,I/ActivityManager(  841): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5879 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 5448:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10086/pid_5448/cgroup.procs: No such file or directory
,I/SystemConfig( 5854): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5854): existFile = false
I/SystemConfig( 5854): canReadFile = false
I/SystemConfig( 5854): systemFeature RCS result false
D/SystemConfig( 5854): refreshRcsSupport() :false
I/LockScreenSettings( 5879): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5879): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5879): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5879): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5879): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5879): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5896 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 5502:com.android.vending/u0a36 (adj 15): empty #11
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  841): failed to open /acct/uid_10036/pid_5502/cgroup.procs: No such file or directory
,W/ResourcesManager( 5896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1959): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  841): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5921 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 5593:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1959): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
,W/libprocessgroup(  841): failed to open /acct/uid_10053/pid_5593/cgroup.procs: No such file or directory
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 00:15:43.362 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WifiInternetCheck(  841): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  841): Process com.lge.qremote (pid 4983) has died
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  841): onReceive
D/LocSvc_java(  841): got connectivity action
D/LocSvc_java(  841): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  841): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  841): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  841): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  841): ignore wifi update if we are not in OPENING or CLOSING
,D/Finsky  ( 5921): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NotificationManager( 1959): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  841): Process com.uei.lg.quicksetsdk.lite (pid 5744) has died
,W/ProcessCpuTracker(  841): Skipping unknown process pid 5944
W/ProcessCpuTracker(  841): Skipping unknown process pid 5947
,D/Finsky  ( 5921): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5921): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5921): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5921): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 5921): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5921): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5921): Skipping gmscore version check
,D/PackageBroadcastService( 5544): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5544): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  841): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5979 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{69f81a type 2 when 89628 com.android.providers.calendar} when 89628
I/art     ( 3222): Explicit concurrent mark sweep GC freed 9323(524KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 478us total 106.589ms
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@25fc2a9a on behalf of 5921
,I/Icing   ( 5544): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 5921): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5921): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 5979): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b81c940:true
,D/BluetoothAdapterService(213270697)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@339d1fc7
D/BluetoothAdapterService(213270697)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@339d1fc7
,I/art     ( 5544): Background partial concurrent mark sweep GC freed 19970(1181KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 13MB/21MB, paused 1.572ms total 105.357ms
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 27923(1834KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 5.256ms total 106.715ms
,I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6005 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5979): Create singleton instance
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  841): Process com.android.providers.calendar (pid 5677) has died
,I/AudioManager( 5979): getMode name:com.lge.qremote
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
D/UEI.SmartControl( 6005): Quickset Services start...
I/UEI.SmartControl( 6005): Manufacture = LGE
D/UEI.SmartControl( 6005): File observer start...
,E/UEI.SmartControl( 6005): IR Port is disabled: false
D/UEI.SmartControl( 6005): Starting file observer...
D/UEI.SmartControl( 6005): Extracting JNI libs...
D/UEI.SmartControl( 6005): --- this system supports 32-bit or 64-bit only
I/DSQN    ( 5809): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5809): restart monitoring
I/DSQN    ( 5809): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
,D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  841): DSQM DsqnNotification wlan0  1
D/DSQN    (  841): start to monitor internet connection
V/SetupWizard( 5649): Connected to Gservices successfully
V/WifiInternetCheck(  841): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 6005): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6005): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6005): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6005): --- Selecting new region: 2
,I/UEI.SmartControl( 6005): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6005): Platform has CIR...
D/UEI.SmartControl( 6005): NO CIR support, need to check package...
I/UEI.SmartControl( 6005): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6005): QS Service created
E/UEI.SmartControl( 6005): QS start get config
,D/UEI.SmartControl( 6005): Loading JNI Libs...
,D/UEI.SmartControl( 6005):  configuring local db...
I/art     (  841): Explicit concurrent mark sweep GC freed 77084(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.036ms total 185.587ms
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,E/MDM     ( 1732): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5544): Restart initialization of location
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  841): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6038 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 23.772ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.349ms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.873ms
,D/UEI.SmartControl( 6005):  ---- Has DB8: true
,D/UEI.SmartControl( 6005): QS start statue = true Error code = 0
D/UEI.SmartControl( 6005): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6005): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6005): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6005): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6005): IrrcClient ++ 
D/irrcClient( 6005): getIrrcService ++ 
D/irrcClient( 6005): getIrrcService -- 
D/irrcClient( 6005): IrrcClient -- 
W/irrc_jni( 6005): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6005): Services init done
,I/UEI.SmartControl( 6005): Device manager: loading config....
D/UEI.SmartControl( 6005): QS Service init finished
D/UEI.SmartControl( 6005): QS Service version name: 0.1.73
D/UEI.SmartControl( 6005): QS Service version code: 1073
D/UEI.SmartControl( 6005): Service requested: Control
D/UEI.SmartControl( 6005): Config is loaded...
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 6005):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6005): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6005): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6005): Internal service binding...
,D/UEI.SmartControl( 6005): -----IControl: 11
D/UEI.SmartControl( 6005): Caller: com.lge.qremote
D/UEI.SmartControl( 6005): ------------ IControl registerCallback...
I/UEI.SmartControl( 6005): Registering callback...
D/UEI.SmartControl( 6005): -----IControl: 19
D/UEI.SmartControl( 6005): Caller: com.lge.qremote
I/UEI.SmartControl( 6005): Registering Services Ready callback...
I/UEI.SmartControl( 6005): Notify client services are ready...
D/UEI.SmartControl( 6005): -----IControl: 8
D/UEI.SmartControl( 6005): Caller: com.lge.qremote
,W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6038): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6038): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6038): Error finding the version of the Email provider.....
E/Gmail   ( 6038): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6038): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6038): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6038): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6038): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6038): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6038): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6038): We do not support migrating this version of the Email provider.
I/Gmail   ( 6038): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  841): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6080 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ActivityManager(  841): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  841): Killing 5788:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 6038): Observing account changes for notifications
,I/Icing   ( 5544): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5544): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_5788/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6038): notifyAccountChanged
,I/Gmail   ( 6038): getAccountsCursor
I/Gmail   ( 6038): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6080): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6080): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6080): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6080): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/Gmail   ( 6038): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6038): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6038): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6038): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/IndexDatabaseHelper( 6080): Using schema version: 115
,I/IndexDatabaseHelper( 6080): Index is fine
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/ActivityManager(  841): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6107 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  841): Killing 5814:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10023/pid_5814/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PCSuite ( 6107): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6107): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6107): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/PCSuite ( 6107): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6107): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6107): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  841): Killing 5854:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10018/pid_5854/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/PCSuite ( 6107): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6107): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6107): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/PCSuite ( 6107): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6107): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6107): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6080): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/ActivityManager(  841): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6129 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6129): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6129): CalendarApplication.onCreate()
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{1ae00001 type 0 when 1454973347261 com.android.vending} when 1454973347261
D/Finsky  ( 5921): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PreferenceKeysParser( 6129): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6129): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@14c83256, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1d17d2d7, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@eac77c4, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3184e6ad, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2aad1de2, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@299cc573, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@25db4c30, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@cb640a9, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1d03362e, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2a7445cf, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@de0fb5c, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3a893e65, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2490873a, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2b996feb, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@b307148, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2bd45be1, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@e6fdd06, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@339d1fc7, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@347f59f4, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2e59d51d, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@c9cc392, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3741f163, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@34322160, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc3a619, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@33f86de, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2ad840bf, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3487f38c, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@345f8ad5, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb932ea, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@d5a29db, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2286bc78, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3d9aff51, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3e6f93b6, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@94788b7, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@33a72824, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3f3f8d, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@593542, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@741f953, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1a40a290, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2a6d4789, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3949638e, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@e68d7af, l
D/GeneralP,referenceUtils( 6129): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6129): [init]
,I/Config  ( 6129): LGCalendar ver.4.40.17
I/Config  ( 6129): start check model
I/Config  ( 6129): start check native_ca
I/Config  ( 6129): Config Operator=OPEN, Country=EU
D/Config  ( 6129): [setDefaultValuesToPref]
D/Config  ( 6129): [parseProfiles]
D/ProfilesParser( 6129): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6129): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6129): [updateProfiletoCountryInfo]
D/GeneralPreference( 6129): [checkAndMigrateOldPreference]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlertReceiver( 6129): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6129): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6129): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/NotificationManager(  841): android: cancelAsUser(2) by android
I/AlertUtils( 6129): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6129): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6129): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6129): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6129): End InitializeAlertRingtoneService.onHandleIntent
,D/libc-netbsd( 5921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
W/HolidayIntentService( 6129): onHandleIntent
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5921): propertyValue:false
D/libc-netbsd( 5921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/HolidayDataLoader( 6129): readJsonAsset : holiday.json
D/AlertService( 6129): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6129): [updateWidgets] 
,D/MonthWidgetProvider( 6129): [onReceive]
D/CalendarWidgetProvider( 6129): [onReceive]
D/CalendarWidgetProvider( 6129): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6129): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6129): [onReceive]
D/CalendarWidgetProvider( 6129): [onReceive]
D/CalendarWidgetProvider( 6129): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CalendarTypeController( 6129): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5368): 
E/HolidayIntentService( 6129): onHandleIntent:holiday data empty
D/libc-netbsd( 5921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/PCSuite ( 6107): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6107): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6080): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6080): MCCMNC not supported: null
I/PCSuite ( 6107): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6107): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6164 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5713): com.google.android.talk: cancel(8) by com.google.android.talk
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  841): android: cancelAsUser(2) by android
I/AppUp4:AppBoxCP( 6164): onCreate
,W/AppUp4:DB( 6164):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6164):  setFingerPrint start
I/AppUp4:DB( 6164):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6164):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6164):  SDK version = 0
I/AppUp4:DB( 6164):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6164): AppBoxApplication onCreate()
,I/qtaguid ( 5921): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5921): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5921): untagSocket(41) failed with errno -22
I/AppUp4:CustModeStarterReceiver( 6164): onReceive
I/AppUp4:CustModeStarterReceiver( 6164): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/Finsky  ( 5921): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/AppUp4:CustFacade( 6164): Context : android.app.ReceiverRestrictedContext@1d17d2d7
D/AppUp4:CustFacade( 6164): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6164): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6164): begin check event
I/AppUp4:CustModeStarterReceiver( 6164): Event For Nothing, skip.
I/ActivityManager(  841): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6185 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  841): Process com.google.android.apps.plus (pid 5896) has died
,I/art     (  841): Explicit concurrent mark sweep GC freed 18803(949KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.645ms total 144.810ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  841): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6205 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,W/ResourcesManager( 6185): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6185): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 6205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6205): VM with version 2.1.0 has multidex support
I/MultiDex( 6205): install
I/MultiDex( 6205): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 5921): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5921): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5921): untagSocket(41) failed with errno -22
I/AppConfig( 6185): Total System Memory = 906309632
,I/GalleryUtils( 6185): Application Heap = 96 MB
V/JNIHelp ( 6205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6185): App Tier : NOT_DEF
D/SystemHelper( 6185): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  841): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6232 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ActivityThread( 6205): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6205): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f960da7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6205): Installed default security provider GmsCore_OpenSSL
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{235b7c1d type 0 when 1454973348767 com.google.android.googlequicksearchbox} when 1454973348767
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5368): 
,I/ActivityManager(  841): Process com.lge.lockscreensettings (pid 5879) has died
,I/NotificationManager( 6205): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6205): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6205): Reading stored module config
,W/ResourcesManager( 6232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     ( 5921): CheckpointMarkThreadRoots callback created = 0xb0561720
,D/ChimeraCfgMgr( 6205): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5368): 
I/art     ( 5921): CheckpointMarkThreadRoots callback created = 0xb0561700
I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5368): 
,I/ActivityManager(  841): Process com.google.android.setupwizard (pid 5649) has died
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 94435463250; DSPS: 3185876; Offset : -2799831317
I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5368): 
I/SystemConfig( 6232): BUILD Country: EU
I/SystemConfig( 6232): BUILD Operator: OPEN
,D/NativeLibraryUtils( 6205): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6205): Connecting to CarCallService...
,I/ActivityManager(  841): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6260 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6232): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6232): existFile = false
I/SystemConfig( 6232): canReadFile = false
I/SystemConfig( 6232): systemFeature RCS result false
D/SystemConfig( 6232): refreshRcsSupport() :false
,I/art     ( 6205): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6205): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5368): 
D/CAR.SERVICE( 6205): com.google.android.projection.gearhead isn't installed.
,I/LockScreenSettings( 6260): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/CAR.TEL.Service( 6205): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6205): Creating a new PhoneAdapter instance
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6205): setListener: com.google.android.gms.car.dn@31247ca2
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6205): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6205): Starting CarCallService with initial phone null
D/LockScreenSettings( 6260): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6260): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6260): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6260): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6260): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/NotificationManager( 6205): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6282 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/CAR.SERVICE( 6205): Package validated; name: com.android.vending
,I/ActivityManager(  841): Process com.google.android.gm (pid 6038) has died
,I/NotificationManager( 5921): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5921): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ResourcesManager( 6282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/qtaguid ( 5921): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5921): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5921): untagSocket(41) failed with errno -22
,I/UpdateIcingCorporaServi( 1959): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5544): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5544): Null package name or gms related package.  Ignoreing.
I/UpdateIcingCorporaServi( 1959): UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6313 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/Icing   ( 5544): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 6005): Internal timer expired: 1
,D/PhoneMonitor( 6313): Register our PhoneStateListener
,I/ActivityManager(  841): Process com.android.settings (pid 6080) has died
,W/ResourcesManager( 5921): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5921): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 5979): getMode name:com.lge.qremote
,D/PhoneMonitor( 6313): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6313): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6313): [parse] Load xml
,V/TelephonyAutoProfiling( 6313): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6313): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
W/ResourcesManager( 5921): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PhoneMonitor( 6313): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6336 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  301): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 288us total 20.802ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.583ms
,I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 19970
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.407ms
,I/CheckinService( 5544): Checking schedule, now: 1454973350747 next: 1454973360709
I/CheckinService( 5544): active receiver: disabled
,D/Finsky  ( 5921): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{580d7a2 type 0 when 1454973350784 com.android.vending} when 1454973350784
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/Finsky  ( 5921): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5921): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  841): Killing 6164:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/ActivityManager(  841): Killing 6107:com.lge.sync/1000 (adj 15): empty #12
,I/MusicStore( 6336): Database version: 120
,W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_6164/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Process com.android.contacts (pid 6232) has died
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6107/cgroup.procs: No such file or directory
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6336): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6336): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6336): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6336): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6336): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ec6419e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6336): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6336): GMSCore installation verified
,I/ConfigStore( 6336): Config Database version: 1
,I/Icing   ( 5544): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MediaRouter( 6336): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/Icing   ( 5544): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/MusicLeanback( 6336): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6336): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6336): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6380 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6336): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6336): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  841): Killing 6185:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ResourcesManager( 6380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6380): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6380): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  841): failed to open /acct/uid_10023/pid_6185/cgroup.procs: No such file or directory
,I/NotificationManager( 6336): com.google.android.music: cancel(1061) by com.google.android.music
,I/art     (  841): Explicit concurrent mark sweep GC freed 16043(722KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.548ms total 152.434ms
,I/LGEmail ( 6380): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6380): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6380): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/AlertService( 6129): Beginning updateAlertNotification
,I/ActivityManager(  841): Process com.google.android.apps.plus (pid 6282) has died
,I/ActivityManager(  841): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6403 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6420 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ResourcesManager( 6403): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/HubEmail( 6380): JNI_OnLoad()
I/HubEmail( 6380): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6380): registerNatives()
I/HubEmail( 6380): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6380): registerNativeMethods()
I/HubEmail( 6380): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6380): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  841): Killing 5713:com.google.android.talk/u0a61 (adj 15): empty #11
,D/CalendarProvider2( 6403): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@13785218
,W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_5713/cgroup.procs: No such file or directory
,D/CalendarProvider2( 6403): [getOrCreateCalendarAlarmManager]
W/Settings( 6380): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/CalendarProvider2( 6403): Created com.android.providers.calendar.CalendarAlarmManager@3184e6ad(com.android.providers.calendar.CalendarProvider2@13785218)
D/LGDMClient( 6420): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6420): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6420): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6420): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6420): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6420): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6420): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6420): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6445 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6420): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6420): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6420): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6420): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/AlertService( 6129): No fired or scheduled alerts
I/NotificationManager( 6129): com.android.calendar: cancel(0) by com.android.calendar
D/LGDMClient( 6420): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/NotificationManager( 6129): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 6129): com.android.calendar: cancel(3) by com.android.calendar
D/LGDMClient( 6420): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/NotificationManager( 6129): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(6) by com.android.calendar
I/ActivityManager(  841): Killing 6260:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/NotificationManager( 6129): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 6129): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6129): com.android.calendar: cancel(20) by com.android.calendar
W/libprocessgroup(  841): failed to open /acct/uid_10069/pid_6260/cgroup.procs: No such file or directory
,D/AlertService( 6129): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  841): Killing 6313:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6445): onCreate
,W/AppUp4:DB( 6445):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6445):  setFingerPrint start
I/AppUp4:DB( 6445):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6445):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6445):  SDK version = 0
I/AppUp4:DB( 6445):  beforefinger == newfinger no write in DB
W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_6313/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6445): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6445): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6445): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6445): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6445): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6445): onReceive
I/AppUp4:CustModeStarterReceiver( 6445): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AlarmScheduler( 6129): No events found starting within 1 week.
,I/ActivityManager(  841): Killing 6129:com.android.calendar/u0a13 (adj 15): empty #11
D/AppUp4:CustFacade( 6445): Context : android.app.ReceiverRestrictedContext@2aad1de2
D/AppUp4:CustFacade( 6445): isCustomizationCompleted : false
W/libprocessgroup(  841): failed to open /acct/uid_10013/pid_6129/cgroup.procs: No such file or directory
,D/AppUp4:CustFacade( 6445): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6445): begin check event
,I/AppUp4:CustModeStarterReceiver( 6445): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6445): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6445): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6445): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6445): handleAsyncCustNotification do not startCustService
I/ActivityManager(  841): Killing 6005:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5979): android.os.DeadObjectException
,W/System.err( 5979): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5979): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5979): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5979): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5979): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5979): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5979): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5979): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5979): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5979): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5979): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5979): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5979): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5979): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5979): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5979): android.os.DeadObjectException
W/System.err( 5979): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5979): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5979): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5979): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5979): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5979): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5979): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5979): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5979): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5979): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5979): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5979): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5979): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5979): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5979): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_6005/cgroup.procs: No such file or directory
W/ActivityManager(  841): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6468 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LgeMiscReceiver( 3203): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3203): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3203): networkInfo.isConnected() = false
I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6488 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6468): Quickset Services start...
I/UEI.SmartControl( 6468): Manufacture = LGE
D/UEI.SmartControl( 6468): File observer start...
,E/UEI.SmartControl( 6468): IR Port is disabled: false
D/UEI.SmartControl( 6468): Starting file observer...
D/UEI.SmartControl( 6468): Extracting JNI libs...
D/UEI.SmartControl( 6468): --- this system supports 32-bit or 64-bit only
D/PhoneMonitor( 6488): Register our PhoneStateListener
D/UEI.SmartControl( 6468): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6468): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6468): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/MobileConnectivityChangeReceiver( 6488): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6488): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  841): Killing 5979:com.lge.qremote/u0a106 (adj 15): empty #11
D/PhoneMonitor( 6488): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6488): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6488): [parse] Load xml
V/TelephonyAutoProfiling( 6488): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6488): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6488): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/UEI.SmartControl( 6468): --- Selecting new region: 2
,I/UEI.SmartControl( 6468): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6468): Platform has CIR...
D/UEI.SmartControl( 6468): NO CIR support, need to check package...
I/UEI.SmartControl( 6468): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6468): QS Service created
W/libprocessgroup(  841): failed to open /acct/uid_10106/pid_5979/cgroup.procs: No such file or directory
,I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 23612
,V/DownloadManager( 3222): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3222): DownloadService onCreate
E/UEI.SmartControl( 6468): QS start get config
I/NotificationManager( 3222): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3222): in removeSpuriousFiles
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@e753fcb on behalf of 3222
,I/DownloadManager( 3222): in trimDatabase
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6515 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 5544): Checking schedule, now: 1454973354400 next: 1454973360709
I/CheckinService( 5544): active receiver: disabled
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@3ec95ec1 on behalf of 3222
,V/DownloadManager( 3222): DownloadService onStartCommand
V/DownloadManager( 3222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/UEI.SmartControl( 6468): Loading JNI Libs...
D/UEI.SmartControl( 6468):  configuring local db...
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@2f960da7 on behalf of 3222
,V/DownloadManager( 3222): DownloadService onDestroy
,I/ActivityManager(  841): Killing 6205:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/UEI.SmartControl( 6468):  ---- Has DB8: true
W/libprocessgroup(  841): failed to open /acct/uid_10006/pid_6205/cgroup.procs: No such file or directory
,W/ActivityManager(  841): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
D/WeatherAncestor( 2693): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:15:54
D/UEI.SmartControl( 6468): QS start statue = true Error code = 0
D/UEI.SmartControl( 6468): QS version = v2.7.11.1_RC1
D/UpdateThreadPoolManager( 2693): 2 : This is isUpdating : false
D/UEI.SmartControl( 6468): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/WeatherAncestor( 2693): connectivity changed - connection : true
D/Weather_cast( 2693): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2693): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:15:54
D/WeatherService( 2693): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/UEI.SmartControl( 6468): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6468): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6468): IrrcClient ++ 
D/irrcClient( 6468): getIrrcService ++ 
D/irrcClient( 6468): getIrrcService -- 
,D/irrcClient( 6468): IrrcClient -- 
W/irrc_jni( 6468): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6468): Services init done
I/UEI.SmartControl( 6468): Device manager: loading config....
D/UEI.SmartControl( 6468): Config is loaded...
,I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6540 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2693): 2 : Utils getTopActivity com.lge.launcher2 / true
D/UEI.SmartControl( 6468): QS Service init finished
D/UEI.SmartControl( 6468):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6468): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6468): QS Service version name: 0.1.73
D/WeatherService( 2693): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2693): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6468): QS Service version code: 1073
D/UEI.SmartControl( 6468): Service requested: Control
D/UEI.SmartControl( 6468): Service.onUnbind: IControl
D/UEI.SmartControl( 6468): Service.onDestroy
D/UEI.SmartControl( 6468): Shutdown IRRCPlayer... 
W/irrc_jni( 6468): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6468): ~IrrcClient ++ 
D/irrcClient( 6468): ~IrrcClient -- 
W/irrc_jni( 6468): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6468): Blaster closed
D/UEI.SmartControl( 6468): Blaster closed
D/UEI.SmartControl( 6468): Shut down QS...
,D/UEI.SmartControl( 6468): Stopped file observer...
I/UEI.SmartControl( 6468): QS lib stop result = true
D/UEI.SmartControl( 6468): QS shutdown complete
D/UEI.SmartControl( 6468): QS Service created
E/UEI.SmartControl( 6468): QS start get config
,W/ResourcesManager( 6540): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6468):  configuring local db...
,D/UEI.SmartControl( 6468):  ---- Has DB8: true
,D/UEI.SmartControl( 6468): QS start statue = true Error code = 0
D/UEI.SmartControl( 6468): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6468): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6468): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6468): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6468): IrrcClient ++ 
D/irrcClient( 6468): getIrrcService ++ 
D/irrcClient( 6468): getIrrcService -- 
D/irrcClient( 6468): IrrcClient -- 
W/irrc_jni( 6468): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6468): Services init done
D/UEI.SmartControl( 6468): QS Service init finished
,D/UEI.SmartControl( 6468): QS Service version name: 0.1.73
D/UEI.SmartControl( 6468): QS Service version code: 1073
D/UEI.SmartControl( 6468): Service requested: Control
I/UEI.SmartControl( 6468): Device manager: loading config....
D/UEI.SmartControl( 6468): Config is loaded...
E/ActivityThread( 6468): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@cb640a9 that was originally bound here
E/ActivityThread( 6468): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@cb640a9 that was originally bound here
E/ActivityThread( 6468): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6468): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6468): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6468): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6468): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6468): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6468): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6468): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6468): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6468): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6468): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6468): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6468): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6468): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6468): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6468): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6468): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6468): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6468): Internal service binding...
I/Babel_SMS( 6540): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6540): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6540): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6540): MmsConfig.loadFromDatabase
D/UEI.SmartControl( 6468):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6468): Notify AllClients services are ready: 0
,E/Babel_SMS( 6540): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6540): MmsConfig.loadFromResources
E/Babel_SMS( 6540): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6540): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6540): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6540): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6540): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6540): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6540): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6540): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6540): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6540): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6540): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6540): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6540): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6540): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6540): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6540): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6540): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6540): found sensor: Motion Accel, handle=46
,I/art     ( 6540): CheckpointMarkThreadRoots callback created = 0xb042d420
I/art     ( 6540): CheckpointMarkThreadRoots callback created = 0xb042d400
,W/Settings( 6540): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6540): startup - clean
I/Babel   ( 6540): deleted: false for 0
,I/ActivityManager(  841): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6578 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 5921:com.android.vending/u0a36 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  841): failed to open /acct/uid_10036/pid_5921/cgroup.procs: No such file or directory
W/AudioCapabilities( 6540): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6540): Unsupported mime audio/adpcm
W/AudioCapabilities( 6540): Unsupported mime audio/g726
W/AudioCapabilities( 6540): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6540): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6540): Unsupported mime video/mjpg
W/VideoCapabilities( 6540): Unsupported mime video/theora
,W/AudioCapabilities( 6540): Unsupported mime audio/evrc
,W/AudioCapabilities( 6540): Unsupported mime audio/qcelp
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6540): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6540): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6540): Unsupported mime audio/evrc
W/VideoCapabilities( 6540): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6540): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6540): onServiceConnected
W/Babel   ( 6540): Attempted to change video mute state without an active call.
,I/NotificationManager( 6540): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6540): propertyValue:false
I/Babel   ( 6540): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  841): Killing 6336:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10081/pid_6336/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6578): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6578): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6578): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6578): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6578): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6578):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6578):   adb logcat -s GAv4
,W/GAv4    ( 6578): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6578): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6578): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6578): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6578): Time to load native libraries: 2 ms (timestamps 1813-1815)
I/LibraryLoader( 6578): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6578): Binding Chromium to main looper Looper (main, tid 1) {15c7ae97}
,I/LibraryLoader( 6578): Expected native library version number "",actual native library version number ""
I/chromium( 6578): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6578): Initializing chromium process, singleProcess=true
,W/art     ( 6578): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6578): ApplicationContext is null in ApplicationStatus
W/chromium( 6578): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6578): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6578): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6578): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6578): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6578): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6578): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6578): Remote Branch: 
I/Adreno-EGL( 6578): Local Patches: 
I/Adreno-EGL( 6578): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb40271e0, uid 10079
,W/AudioManagerAndroid( 6578): Requires BLUETOOTH permission
I/NSApplication( 6578): Starting up...
,I/ActivityManager(  841): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6642 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6380:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10021/pid_6380/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6661 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  841): Killing 6403:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/art     (  301): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 289us total 21.300ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.793ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.834ms
,W/libprocessgroup(  841): failed to open /acct/uid_10014/pid_6403/cgroup.procs: No such file or directory
,W/ResourcesManager( 6661): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5544): SYNC; picasa accounts
,D/NetworkLogImpl( 5544): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5544): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  841): Killing 6420:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/iu.UploadsManager( 5544): num queued entries: 0
,I/iu.UploadsManager( 5544): num updated entries: 0
I/iu.SyncManager( 5544): NEXT; no task
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6420/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6691 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/MusicStore( 6691): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6691): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6691): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6691): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6691): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6691): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6691): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6691): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6691): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ec6419e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6691): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6691): GMSCore installation verified
,I/ConfigStore( 6691): Config Database version: 1
,I/MediaRouter( 6691): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6691): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6691): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6691): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6724 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6691): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6691): Using platform SSLCertificateSocketFactory
I/art     (  841): Explicit concurrent mark sweep GC freed 19925(962KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.052ms total 145.651ms
,W/ResourcesManager( 6724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6724): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6724): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  841): Killing 6445:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_6445/cgroup.procs: No such file or directory
,I/NotificationManager( 6691): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6724): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6724): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6724): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/jxcore-log( 5368): Test app app.js loaded
I/jxcore-log( 5368): 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5368): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bc6314e added. We now have 1 listener(s)
,D/BluetoothAdapterService(213270697)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@339d1fc7
I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6748 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6724): JNI_OnLoad()
I/HubEmail( 6724): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNatives()
I/HubEmail( 6724): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNativeMethods()
,I/HubEmail( 6724): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6724): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  841): Killing 6488:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/jxcore-log( 5368): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5368): 
I/chromium( 5368): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 5368): TAP version 13
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): ok 1 should be equal
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 5368): 
,W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_6488/cgroup.procs: No such file or directory
D/LGDMClient( 6748): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6748): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6748): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6748): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/UEI.SmartControl( 6468): file observer is disposed!
D/LGDMClient( 6748): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6748): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6777 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6748): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6748): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6748): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6748): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6748): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  841): Killing 6515:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6777): onCreate
,W/AppUp4:DB( 6777):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6777):  setFingerPrint start
I/AppUp4:DB( 6777):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6777):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6777):  SDK version = 0
,I/AppUp4:DB( 6777):  beforefinger == newfinger no write in DB
I/jxcore-log( 5368): ok 2 should be equal
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ok 3 should be equal
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): ok 4 should be equal
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ok 5 should be equal
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ok 6 should throw
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 5368): 
W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_6515/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6777): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6777): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6777): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6777): [onReceive] connect :true
I/jxcore-log( 5368): ok 7 should throw
I/jxcore-log( 5368): 
I/NetworkStateForAutoUpdateMonitor( 6777): [onReceive] request level :IDLE....
I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons no beacons returns null
I/jxcore-log( 5368): 
I/AppUp4:CustModeStarterReceiver( 6777): onReceive
I/AppUp4:CustModeStarterReceiver( 6777): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6777): Context : android.app.ReceiverRestrictedContext@2aad1de2
,D/AppUp4:CustFacade( 6777): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6777): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6777): begin check event
I/AppUp4:CustModeStarterReceiver( 6777): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6777): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6777): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6777): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6777): handleAsyncCustNotification do not startCustService
I/ActivityManager(  841): Killing 6468:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/jxcore-log( 5368): ok 8 should be equal
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ok 9 should throw
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 5368): 
W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_6468/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3203): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3203): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3203): networkInfo.isConnected() = false
,I/jxcore-log( 5368): ok 10 should be equal
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 5368): 
,I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6804 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6804): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6804): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6804): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  841): Killing 6540:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6804): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6804): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6804): [parse] Load xml
V/TelephonyAutoProfiling( 6804): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6804): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6804): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/jxcore-log( 5368): ok 11 should be equal
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): ok 12 should be equal
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 5368): 
W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_6540/cgroup.procs: No such file or directory
,V/DownloadManager( 3222): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3222): DownloadService onCreate
I/DownloadManager( 3222): in removeSpuriousFiles
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@e4c25fd on behalf of 3222
I/NotificationManager( 3222): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3222): in trimDatabase
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@28ad72f2 on behalf of 3222
,I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6837 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3222): DownloadService onStartCommand
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,V/DownloadManager( 3222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@2a3a24f9 on behalf of 3222
I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 29299
I/CheckinService( 5544): Checking schedule, now: 1454973360054 next: 1454973360709
I/CheckinService( 5544): active receiver: disabled
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,V/DownloadManager( 3222): DownloadService onDestroy
,I/ActivityManager(  841): Killing 6578:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 5368): ok 13 should be equal
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ok 14 (unnamed assert)
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # setup
I/jxcore-log( 5368): 
I/jxcore-log( 5368): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ok 15 (unnamed assert)
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): # teardown
I/jxcore-log( 5368): 
W/libprocessgroup(  841): failed to open /acct/uid_10079/pid_6578/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2693): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:0
D/UpdateThreadPoolManager( 2693): 2 : This is isUpdating : false
D/WeatherAncestor( 2693): connectivity changed - connection : true
D/Weather_cast( 2693): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2693): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:0
D/WeatherService( 2693): 2 : TimeTick Intent has been received, Time(hour:min:sec) 0:16:0
D/WeatherService( 2693): 2 : TimeTick Intent And Screen On
D/WeatherService( 2693): 2 : SDK version : 21
I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6858 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2693): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2693): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2693): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2693): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2693): 2 : This is isUpdating : false
D/WeatherService( 2693): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2693): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2693): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2693): 2 : Fixed theme : optimus
D/WeatherReflect( 2693): 2 : Map key string is -2
,D/lim     ( 2693): 2 : time = 00:16
I/WeatherReflect( 2693): Model Name : LG-D722
,D/WeatherTheme( 2693): 2 : Different view - status_min_formatted : 15 != 16
D/WeatherTheme( 2693): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2693): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2693): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2693): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2693): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2693): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2693): forecast size is 0
D/Theme   ( 2693): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2693): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2693): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2693): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2693): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2693): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2693): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2693): url is : null
D/Theme   ( 2693): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2693): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2693): 2 : update view, appWidgetId: 2
D/WeatherService( 2693): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 0:16:0
D/WeatherService( 2693): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2693): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2693): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2693): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ResourcesManager( 6858): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/Babel_SMS( 6858): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6858): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6858): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6858): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6858): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6858): MmsConfig.loadFromResources
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
E/Babel_SMS( 6858): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6858): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6858): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6858): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6858): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6858): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6858): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6858): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6858): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6858): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6858): found sensor: LGE Step Counter Sensor, handle=44
,D/SensorManager( 6858): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6858): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6858): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6858): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6858): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6858): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6858): found sensor: Motion Accel, handle=46
W/Settings( 6858): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6858): startup - clean
I/art     ( 6858): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/art     ( 6858): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/Babel   ( 6858): deleted: false for 0
I/ActivityManager(  841): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6898 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5544): Done disabling old GoogleServicesFramework version
,W/AudioCapabilities( 6858): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6858): Unsupported mime audio/adpcm
W/AudioCapabilities( 6858): Unsupported mime audio/g726
,W/AudioCapabilities( 6858): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6858): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6858): Unsupported mime video/mjpg
W/VideoCapabilities( 6858): Unsupported mime video/theora
W/AudioCapabilities( 6858): Unsupported mime audio/evrc
,W/AudioCapabilities( 6858): Unsupported mime audio/qcelp
W/VideoCapabilities( 6858): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6858): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6858): Unsupported mime audio/qcelp
W/AudioCapabilities( 6858): Unsupported mime audio/evrc
W/VideoCapabilities( 6858): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6858): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6858): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6858): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6858): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6858): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6858): onServiceConnected
W/Babel   ( 6858): Attempted to change video mute state without an active call.
,I/NotificationManager( 6858): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6858): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6858): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6858): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6858): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6858): propertyValue:false
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6898): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6898): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6898):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6898):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6898): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 6858): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  841): Killing 6642:com.android.chrome/u0a48 (adj 15): empty #11
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6898): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6898): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup(  841): failed to open /acct/uid_10048/pid_6642/cgroup.procs: No such file or directory
,W/GAv4    ( 6898): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6898): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6898): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6898): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6898): Time to load native libraries: 3 ms (timestamps 6841-6844)
I/LibraryLoader( 6898): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6898): Binding Chromium to main looper Looper (main, tid 1) {15c7ae97}
I/LibraryLoader( 6898): Expected native library version number "",actual native library version number ""
I/chromium( 6898): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6898): Initializing chromium process, singleProcess=true
,W/art     ( 6898): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6898): ApplicationContext is null in ApplicationStatus
W/chromium( 6898): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6898): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6898): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6898): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6898): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6898): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6898): Remote Branch: 
I/Adreno-EGL( 6898): Local Patches: 
I/Adreno-EGL( 6898): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb4027800, uid 10079
,W/AudioManagerAndroid( 6898): Requires BLUETOOTH permission
I/NSApplication( 6898): Starting up...
,I/ActivityManager(  841): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6964 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6661:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10086/pid_6661/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6983 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6691:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10081/pid_6691/cgroup.procs: No such file or directory
,W/ResourcesManager( 6983): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  841): Killing 6724:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10021/pid_6724/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7007 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 420us total 33.124ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 31.582ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.180ms
,I/MusicStore( 7007): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7007): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7007): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7007): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/JNIHelp ( 7007): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 7007): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7007): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ec6419e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7007): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7007): GMSCore installation verified
I/ConfigStore( 7007): Config Database version: 1
,I/MediaRouter( 7007): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7007): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7007): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7007): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7035 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7007): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7007): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7035): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7035): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  841): Killing 6748:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6748/cgroup.procs: No such file or directory
,I/NotificationManager( 7007): com.google.android.music: cancel(1061) by com.google.android.music
I/art     (  841): Explicit concurrent mark sweep GC freed 19774(975KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.191ms total 150.749ms
,I/LGEmail ( 7035): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7035): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7035): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7066 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7035): JNI_OnLoad()
I/HubEmail( 7035): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7035): registerNatives()
I/HubEmail( 7035): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7035): registerNativeMethods()
I/HubEmail( 7035): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7035): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  841): Killing 6777:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_6777/cgroup.procs: No such file or directory
,D/LGDMClient( 7066): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7066): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7066): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7066): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7066): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7066): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7066): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7066): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7090 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7066): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7066): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7066): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7066): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7066): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7066): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  841): Killing 6804:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_6804/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7090): onCreate
,W/AppUp4:DB( 7090):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7090):  setFingerPrint start
I/AppUp4:DB( 7090):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7090):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7090):  SDK version = 0
I/AppUp4:DB( 7090):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7090): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7090): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7090): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7090): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7090): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7090): onReceive
I/AppUp4:CustModeStarterReceiver( 7090): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7090): Context : android.app.ReceiverRestrictedContext@2aad1de2
D/AppUp4:CustFacade( 7090): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7090): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7090): begin check event
I/AppUp4:CustModeStarterReceiver( 7090): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7090): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7090): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7090): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7090): handleAsyncCustNotification do not startCustService
I/ActivityManager(  841): Killing 6837:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_6837/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3203): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3203): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3203): networkInfo.isConnected() = true
D/PhoneState( 3203): setPdpRejectCasuse : false
,I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7109 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7109): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7109): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7109): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  841): Killing 6858:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7109): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7109): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7109): [parse] Load xml
V/TelephonyAutoProfiling( 7109): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7109): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7109): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_6858/cgroup.procs: No such file or directory
,V/DownloadManager( 3222): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3222): DownloadService onCreate
I/DownloadManager( 3222): in removeSpuriousFiles
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 33315
I/NotificationManager( 3222): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@37850a9f on behalf of 3222
I/DownloadManager( 3222): in trimDatabase
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@186f17b5 on behalf of 3222
,I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7132 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 5544): Checking schedule, now: 1454973364107 next: 1454973360709
V/DownloadManager( 3222): DownloadService onStartCommand
I/CheckinService( 5544): active receiver: enabled
V/DownloadManager( 3222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@1839b1bb on behalf of 3222
,V/DownloadManager( 3222): DownloadService onDestroy
I/CheckinService( 5544): Preparing to send checkin request
I/EventLogService( 5544): Accumulating logs since 1454973323567
,D/WeatherAncestor( 2693): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:4
D/UpdateThreadPoolManager( 2693): 2 : This is isUpdating : false
D/WeatherAncestor( 2693): connectivity changed - connection : true
D/Weather_cast( 2693): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2693): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:4
D/WeatherService( 2693): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7154 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2693): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2693): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2693): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7154): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5544): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5544): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5423): Explicit concurrent mark sweep GC freed 2474(97KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 358us total 32.862ms
,I/Babel_SMS( 7154): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7154): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7154): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7154): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7154): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7154): MmsConfig.loadFromResources
E/Babel_SMS( 7154): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7154): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7154): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7154): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7154): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7154): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7154): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7154): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7154): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7154): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7154): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7154): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7154): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7154): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7154): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7154): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7154): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7154): found sensor: Motion Accel, handle=46
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7154): startup - clean
I/Babel   ( 7154): deleted: false for 0
,I/art     ( 7154): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/art     ( 7154): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/AudioCapabilities( 7154): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7154): Unsupported mime audio/adpcm
W/AudioCapabilities( 7154): Unsupported mime audio/g726
W/AudioCapabilities( 7154): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7154): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7154): Unsupported mime video/mjpg
W/VideoCapabilities( 7154): Unsupported mime video/theora
W/AudioCapabilities( 7154): Unsupported mime audio/evrc
,W/AudioCapabilities( 7154): Unsupported mime audio/qcelp
W/VideoCapabilities( 7154): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7154): Unsupported mime audio/amr-wb-plus
I/art     ( 6983): CheckpointMarkThreadRoots callback created = 0xb042d450
,W/AudioCapabilities( 7154): Unsupported mime audio/qcelp
W/AudioCapabilities( 7154): Unsupported mime audio/evrc
W/VideoCapabilities( 7154): Unsupported mime video/mp4v-esdp
I/art     ( 6983): CheckpointMarkThreadRoots callback created = 0xb042d420
,I/ActivityManager(  841): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7193 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/VideoCapabilities( 7154): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  841): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7208 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{ce7d004 type 0 when 1454973360709 com.google.android.gms} when 1454973360709
W/VideoCapabilities( 7154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7154): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  841): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7226 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{72cf9ed type 0 when 1454973364831 com.android.vending} when 1454973364831
W/VideoCapabilities( 7154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7154): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 7193): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 7208): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7208): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/vclib   ( 7154): onServiceConnected
W/Babel   ( 7154): Attempted to change video mute state without an active call.
I/NotificationManager( 7154): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7154): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7154): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7154): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7154): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7154): propertyValue:false
D/CalendarProvider2( 7193): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@13785218
I/Babel   ( 7154): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  841): Killing 7007:com.google.android.music:main/u0a81 (adj 15): empty #11
I/MultiDex( 7208): VM with version 2.1.0 has multidex support
I/MultiDex( 7208): install
I/MultiDex( 7208): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  841): failed to open /acct/uid_10081/pid_7007/cgroup.procs: No such file or directory
,D/CalendarProvider2( 7193): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7193): Created com.android.providers.calendar.CalendarAlarmManager@3184e6ad(com.android.providers.calendar.CalendarProvider2@13785218)
D/CalendarProviderBroadcastReceiver( 7193): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7193): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 7193): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7193): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7193): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  841): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7252 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/CalendarProvider2( 7193): [IntentService] Release Lock
,D/CalendarProvider2( 7193): CalendarProviderIntentService.onDestroy()
V/JNIHelp ( 7208): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7252): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ActivityThread( 7208): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7208): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f960da7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7208): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7208): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7208): com.google.android.gms: cancel(39789) by com.google.android.gms
D/Finsky  ( 7226): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/BluetoothManagerService(  841): Message: 20
,D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cd385d:true
D/BluetoothAdapterService(213270697)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@339d1fc7
D/BluetoothAdapterService(213270697)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@339d1fc7
I/art     ( 7208): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7208): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7282 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 24.201ms
V/LGMDMManager( 7252): Create singleton instance
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.088ms
D/Finsky  ( 7226): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.124ms
,W/Settings( 7226): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7226): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7226): com.android.vending: cancel(-1050172287) by com.android.vending
D/NativeLibraryUtils( 7208): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  841): Killing 7035:com.lge.email/u0a21 (adj 15): empty #11
,D/WVCdm   (  279): Instantiating CDM.
,D/UEI.SmartControl( 7282): Quickset Services start...
I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
I/UEI.SmartControl( 7282): Manufacture = LGE
D/UEI.SmartControl( 7282): File observer start...
D/Ads     ( 7226): Skipping gmscore version check
E/UEI.SmartControl( 7282): IR Port is disabled: false
D/UEI.SmartControl( 7282): Starting file observer...
D/UEI.SmartControl( 7282): Extracting JNI libs...
D/UEI.SmartControl( 7282): --- this system supports 32-bit or 64-bit only
,I/AudioManager( 7252): getMode name:com.lge.qremote
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
,W/libprocessgroup(  841): failed to open /acct/uid_10021/pid_7035/cgroup.procs: No such file or directory
,I/AudioManager( 7252): getMode name:com.lge.qremote
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@26c67a31 on behalf of 7226
D/Finsky  ( 7226): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7226): [1] Libraries$2.run: Finished loading 1 libraries.
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=3560097219
,D/Finsky  ( 7226): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7226): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  841): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7315 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7208): CheckpointMarkThreadRoots callback created = 0xb04cbf80
,I/art     ( 7208): CheckpointMarkThreadRoots callback created = 0xb04cbf70
,D/UEI.SmartControl( 7282): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7282): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7282): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7282): --- Selecting new region: 2
I/UEI.SmartControl( 7282): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7282): Platform has CIR...
D/UEI.SmartControl( 7282): NO CIR support, need to check package...
I/UEI.SmartControl( 7282): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7282): QS Service created
,I/ActivityManager(  841): Process com.lge.appbox.client (pid 7090) has died
,I/dex2oat ( 7333): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/UEI.SmartControl( 7282): QS start get config
D/UEI.SmartControl( 7282): Loading JNI Libs...
,D/UEI.SmartControl( 7282):  configuring local db...
D/Finsky  ( 7226): [945] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7226): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/dex2oat ( 7333): dex2oat took 119.633ms (threads: 4)
,I/Adreno-EGL( 7208): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7208): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7208): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7208): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7208): Remote Branch: 
I/Adreno-EGL( 7208): Local Patches: 
I/Adreno-EGL( 7208): Reconstruct Branch: 
,I/Gmail   ( 7315): getAccountsCursor
I/Adreno-EGL( 7208): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7208): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7208): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7208): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7208): Remote Branch: 
I/Adreno-EGL( 7208): Local Patches: 
I/Adreno-EGL( 7208): Reconstruct Branch: 
,I/art     (  841): Explicit concurrent mark sweep GC freed 23617(1075KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.526ms total 195.172ms
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/GAV2    ( 7315): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/UEI.SmartControl( 7282):  ---- Has DB8: true
D/UEI.SmartControl( 7282): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7282): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7282): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7282): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7282): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7282): IrrcClient ++ 
D/irrcClient( 7282): getIrrcService ++ 
,D/irrcClient( 7282): getIrrcService -- 
D/irrcClient( 7282): IrrcClient -- 
W/irrc_jni( 7282): IRRCPlayer_nativeInit -- 
W/ActivityManager(  841): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/UEI.SmartControl( 7282): Services init done
,W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 7282): QS Service init finished
D/UEI.SmartControl( 7282): QS Service version name: 0.1.73
D/UEI.SmartControl( 7282): QS Service version code: 1073
,D/UEI.SmartControl( 7282): Service requested: Control
I/UEI.SmartControl( 7282): Device manager: loading config....
D/UEI.SmartControl( 7282): Config is loaded...
I/Gmail   ( 7315): Observing account changes for notifications
W/ActivityManager(  841): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7315): Error finding the version of the Email provider.....
E/Gmail   ( 7315): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7315): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7315): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7315): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7315): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7315): We do not support migrating this version of the Email provider.
I/Gmail   ( 7315): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7282):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7282): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7282): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7282): -----IControl: 11
D/UEI.SmartControl( 7282): Caller: com.lge.qremote
D/UEI.SmartControl( 7282): ------------ IControl registerCallback...
D/UEI.SmartControl( 7282): Internal service binding...
I/UEI.SmartControl( 7282): Registering callback...
D/UEI.SmartControl( 7282): -----IControl: 19
,D/UEI.SmartControl( 7282): Caller: com.lge.qremote
I/UEI.SmartControl( 7282): Registering Services Ready callback...
I/ActivityManager(  841): Killing 7066:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/UEI.SmartControl( 7282): Notify client services are ready...
D/UEI.SmartControl( 7282): -----IControl: 8
D/UEI.SmartControl( 7282): Caller: com.lge.qremote
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_7066/cgroup.procs: No such file or directory
D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/LocationInitializer( 5544): Restart initialization of location
,I/ActivityManager(  841): Killing 7109:com.google.android.setupwizard/u0a38 (adj 15): empty #11
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_7109/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Killing 7132:com.lge.drmservice/u0a51 (adj 15): empty #11
I/Adreno-EGL( 7208): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7208): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7208): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7208): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7208): Remote Branch: 
I/Adreno-EGL( 7208): Local Patches: 
I/Adreno-EGL( 7208): Reconstruct Branch: 
,I/WVCdm   (  279): CdmEngine::OpenSession
,W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_7132/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/AudioManager( 7252): getMode name:com.lge.qremote
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7374 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 7315): notifyAccountChanged
,I/Gmail   ( 7315): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7315): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7315): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7315): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 7374): Register our PhoneStateListener
I/Gmail   ( 7315): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  841): Killing 6898:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 7374): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7374): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7374): [parse] Load xml
V/TelephonyAutoProfiling( 7374): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7374): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7374): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  841): failed to open /acct/uid_10079/pid_6898/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7252): getMode name:com.lge.qremote
I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 36999
,D/Finsky  ( 7226): [950] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5544): Checkin interval check for package: unspecified last checkin: 1454973330745 min interval config: 0 actual interval: 37054
I/NotificationManager(  841): android: cancelAsUser(2) by android
,E/MDM     ( 1732): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5544): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/Gmail   ( 7315): getAccountsCursor
I/AudioManager( 7252): getMode name:com.lge.qremote
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 7226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,W/ContextImpl( 3572): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/AudioManager( 7252): getMode name:com.lge.qremote
I/AudioManager( 7252): getMode name:com.lge.qremote
,I/AudioManager( 7252): getMode name:com.lge.qremote
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7226): propertyValue:false
I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2353964981
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 114436450534; DSPS: 3841267; Offset : -2799791199
,I/MusicWidget( 2622): mDelayedStopHandler : unbind
,I/MusicBrowser( 2699): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2699): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2699): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2699): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2699): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2699): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2699): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2699): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  841):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@34322160com.lge.music.MediaPlaybackService$6@2fc3a619
,D/MusicBrowser( 2699): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1d03362e
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2699): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2699): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2699): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2699): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2699): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2699): reset
V/MediaPlayer[Native]( 2699): setListener
V/MediaPlayer[Native]( 2699): disconnect
V/MediaPlayer[Native]( 2699): destructor
V/AudioFlinger(  279): releasing 19 from 2699 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2699): disconnect
D/MusicBrowser( 2699): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2699): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2699): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2699): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2699): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2699): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2699): [SmartShareManagerClient] unregisterListener: 54494942
W/SmartShareClient( 2699): [SmartShareManagerClient] unregisterListener invalid listener: 54494942
I/SmartShareClient( 2699): [SmartShareManagerClient] terminate service: 2699/MediaPlaybackService/246183876
E/HomeCloudIF( 2699): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2699): [SmartShareManagerClient] unbindService context:android.app.Application@2ad840bf
,V/CloudHub( 2699): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2699): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2699): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2699): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2699): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  841): Killing 6964:com.android.chrome/u0a48 (adj 15): empty #11
I/CloudHub( 2699): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  841): failed to open /acct/uid_10048/pid_6964/cgroup.procs: No such file or directory
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/CheckinRequestBuilder( 5544): Classify the device as Phone.
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5544): propertyValue:false
D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5544): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5544): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5544): Sending checkin request (9786 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5544): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5544): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5544): Classify the device as Phone.
,I/CheckinTask( 5544): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5544): Checking schedule, now: 1454973371337 next: 1455500620332
I/CheckinService( 5544): active receiver: disabled
,I/CheckinService( 5544): Checking schedule, now: 1454973371374 next: 1455500620332
,I/CheckinService( 5544): active receiver: disabled
D/CheckinService( 5544): Recording last checkin time for package unspecified as 1454973371383
V/SetupWizard( 7374): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 7315): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5544): Google Analytics 8.4.89 is starting up.
,D/UEI.SmartControl( 7282): Internal timer expired: 1
,I/ThermalEngine(  290): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/ActivityManager(  841): Killing 7193:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  841): Killing 6983:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  841): failed to open /acct/uid_10014/pid_7193/cgroup.procs: No such file or directory
,W/libprocessgroup(  841): failed to open /acct/uid_10086/pid_6983/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
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
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  841): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7481 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7154): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7481): onCreate
,W/AppUp4:DB( 7481):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7481):  setFingerPrint start
I/AppUp4:DB( 7481):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7481):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7481):  SDK version = 0
I/AppUp4:DB( 7481):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7481): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7481): onReceive
,I/AppUp4:CustModeStarterReceiver( 7481): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7481): Context : android.app.ReceiverRestrictedContext@1d17d2d7
,D/AppUp4:CustFacade( 7481): isCustomizationCompleted : false
V/JNIHelp ( 7154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:CustFacade( 7481): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7481): begin check event
I/AppUp4:CustModeStarterReceiver( 7481): Event For Nothing, skip.
,I/NotificationService(  841): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  841): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  841): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7503 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/System  ( 7154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7154): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/BackupManagerService(  841): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
,W/ResourcesManager( 7503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7503): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7503): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  841): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/art     (  841): Explicit concurrent mark sweep GC freed 24417(1239KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.650ms total 187.687ms
,V/BackupManagerService(  841): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  841): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2636c6b
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7503): Total System Memory = 906309632
,I/GalleryUtils( 7503): Application Heap = 96 MB
I/AppConfig( 7503): App Tier : NOT_DEF
,D/LocationProviderProxy(  841): applying state to connected service
D/SystemHelper( 7503): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  841): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7524 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  841): Killing 7226:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10036/pid_7226/cgroup.procs: No such file or directory
,W/ResourcesManager( 7524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7524): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7524): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7524): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7524): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7524): BUILD Country: EU
I/SystemConfig( 7524): BUILD Operator: OPEN
,I/ActivityManager(  841): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7549 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 7315:com.google.android.gm/u0a53 (adj 15): empty #11
,I/SystemConfig( 7524): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7524): existFile = false
I/SystemConfig( 7524): canReadFile = false
I/SystemConfig( 7524): systemFeature RCS result false
D/SystemConfig( 7524): refreshRcsSupport() :false
W/libprocessgroup(  841): failed to open /acct/uid_10053/pid_7315/cgroup.procs: No such file or directory
I/LockScreenSettings( 7549): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7549): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7549): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7549): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7549): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7549): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7566 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 2699:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2699 died, releasing its sessions
V/AudioFlinger(  279):  pid 1750 @ 0
V/AudioFlinger(  279):  pid 3203 @ 1
V/AudioFlinger(  279):  pid 3203 @ 2
,W/libprocessgroup(  841): failed to open /acct/uid_10028/pid_2699/cgroup.procs: No such file or directory
,W/ResourcesManager( 7566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1959): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  841): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7591 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1959): UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
,I/ActivityManager(  841): Killing 7282:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7252): android.os.DeadObjectException
,W/System.err( 7252): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7252): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7252): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7252): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7252): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7252): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7252): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7252): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7252): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
,W/System.err( 7252): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7252): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7252): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7252): android.os.DeadObjectException
W/System.err( 7252): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7252): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7252): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7252): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7252): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7252): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7252): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7252): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7252): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7252): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7252): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7252): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_7282/cgroup.procs: No such file or directory
W/ActivityManager(  841): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7615 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7615): Quickset Services start...
,I/UEI.SmartControl( 7615): Manufacture = LGE
D/UEI.SmartControl( 7615): File observer start...
E/UEI.SmartControl( 7615): IR Port is disabled: false
D/UEI.SmartControl( 7615): Starting file observer...
D/UEI.SmartControl( 7615): Extracting JNI libs...
D/UEI.SmartControl( 7615): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7615): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7615): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7615): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7615): --- Selecting new region: 2
,I/UEI.SmartControl( 7615): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7615): Platform has CIR...
D/UEI.SmartControl( 7615): NO CIR support, need to check package...
I/UEI.SmartControl( 7615): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7615): QS Service created
D/Finsky  ( 7591): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
E/UEI.SmartControl( 7615): QS start get config
,D/UEI.SmartControl( 7615): Loading JNI Libs...
,D/UEI.SmartControl( 7615):  configuring local db...
,D/Finsky  ( 7591): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7591): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7591): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7591): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@2ea32516 on behalf of 7591
,D/Finsky  ( 7591): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7591): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7591): Skipping gmscore version check
D/Finsky  ( 7591): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/UEI.SmartControl( 7615):  ---- Has DB8: true
D/UEI.SmartControl( 7615): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7615): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7615): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7615): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7615): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7615): IrrcClient ++ 
,D/irrcClient( 7615): getIrrcService ++ 
D/irrcClient( 7615): getIrrcService -- 
D/irrcClient( 7615): IrrcClient -- 
W/irrc_jni( 7615): IRRCPlayer_nativeInit -- 
D/PackageBroadcastService( 5544): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7591): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 5544): Null package name or gms related package.  Ignoreing.
D/UEI.SmartControl( 7615): Services init done
I/UEI.SmartControl( 7615): Device manager: loading config....
D/UEI.SmartControl( 7615): QS Service init finished
D/UEI.SmartControl( 7615): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7615): QS Service version code: 1073
D/UEI.SmartControl( 7615): Service requested: Control
D/UEI.SmartControl( 7615): Config is loaded...
I/Icing   ( 5544): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 7615):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7615): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 7615): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7615): -----IControl: 11
I/ActivityManager(  841): Killing 7252:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7615): Caller: com.lge.qremote
D/UEI.SmartControl( 7615): ------------ IControl registerCallback...
I/UEI.SmartControl( 7615): Registering callback...
D/UEI.SmartControl( 7615): Internal service binding...
,W/libprocessgroup(  841): failed to open /acct/uid_10106/pid_7252/cgroup.procs: No such file or directory
,I/ActivityManager(  841): Killing 7374:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_7374/cgroup.procs: No such file or directory
,I/ThermalEngine(  290): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 5544): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5544): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  841): Killing 7208:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10006/pid_7208/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7615): Internal timer expired: 1
,D/UEI.SmartControl( 7615): Service.onUnbind: IControl
D/UEI.SmartControl( 7615): Service.onDestroy
W/System.err( 7615): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@cb640a9
W/System.err( 7615): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7615): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7615): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7615): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7615): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7615): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7615): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7615): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7615): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7615): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7615): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7615): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7615): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7615): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7615): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7615): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@cb640a9
D/UEI.SmartControl( 7615): Shutdown IRRCPlayer... 
,W/irrc_jni( 7615): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7615): ~IrrcClient ++ 
D/irrcClient( 7615): ~IrrcClient -- 
W/irrc_jni( 7615): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7615): Blaster closed
D/UEI.SmartControl( 7615): Blaster closed
D/UEI.SmartControl( 7615): Shut down QS...
,D/UEI.SmartControl( 7615): Stopped file observer...
I/UEI.SmartControl( 7615): QS lib stop result = true
D/UEI.SmartControl( 7615): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1801): Battery Level Remaining: 100%
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
D/WifiController(  841): battery changed pluggedType: 2
,D/charger_monitor(  459): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 134437267401; DSPS: 4496655; Offset : -2799828538
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30135 ms ago)
,D/qdlights(  841): set_light_backlight: 254
,D/qdlights(  841): set_light_backlight: 250
D/qdlights(  841): set_light_backlight: 247
,D/qdlights(  841): set_light_backlight: 244
,D/qdlights(  841): set_light_backlight: 240
,D/qdlights(  841): set_light_backlight: 237
,D/qdlights(  841): set_light_backlight: 234
,D/qdlights(  841): set_light_backlight: 230
,D/qdlights(  841): set_light_backlight: 227
,D/qdlights(  841): set_light_backlight: 224
,D/qdlights(  841): set_light_backlight: 220
,D/qdlights(  841): set_light_backlight: 217
,D/qdlights(  841): set_light_backlight: 214
,D/qdlights(  841): set_light_backlight: 210
,D/qdlights(  841): set_light_backlight: 207
,D/qdlights(  841): set_light_backlight: 204
,D/qdlights(  841): set_light_backlight: 200
,D/qdlights(  841): set_light_backlight: 197
,D/qdlights(  841): set_light_backlight: 194
,D/qdlights(  841): set_light_backlight: 190
,D/qdlights(  841): set_light_backlight: 187
,D/qdlights(  841): set_light_backlight: 184
,D/qdlights(  841): set_light_backlight: 180
,D/qdlights(  841): set_light_backlight: 177
,D/qdlights(  841): set_light_backlight: 174
,D/qdlights(  841): set_light_backlight: 170
,D/qdlights(  841): set_light_backlight: 167
,D/qdlights(  841): set_light_backlight: 164
,D/qdlights(  841): set_light_backlight: 160
,D/qdlights(  841): set_light_backlight: 157
,D/qdlights(  841): set_light_backlight: 154
,D/qdlights(  841): set_light_backlight: 150
,D/qdlights(  841): set_light_backlight: 147
,D/qdlights(  841): set_light_backlight: 144
,D/qdlights(  841): set_light_backlight: 140
,D/qdlights(  841): set_light_backlight: 137
,D/qdlights(  841): set_light_backlight: 134
,D/qdlights(  841): set_light_backlight: 130
,D/qdlights(  841): set_light_backlight: 127
,D/qdlights(  841): set_light_backlight: 124
,D/qdlights(  841): set_light_backlight: 120
,D/qdlights(  841): set_light_backlight: 117
,D/qdlights(  841): set_light_backlight: 114
,D/qdlights(  841): set_light_backlight: 110
,D/qdlights(  841): set_light_backlight: 107
,D/qdlights(  841): set_light_backlight: 104
,D/qdlights(  841): set_light_backlight: 100
,D/qdlights(  841): set_light_backlight: 97
,D/qdlights(  841): set_light_backlight: 94
,D/qdlights(  841): set_light_backlight: 90
,D/qdlights(  841): set_light_backlight: 87
,D/qdlights(  841): set_light_backlight: 84
,D/qdlights(  841): set_light_backlight: 80
,D/qdlights(  841): set_light_backlight: 77
,D/qdlights(  841): set_light_backlight: 74
,D/qdlights(  841): set_light_backlight: 70
,D/qdlights(  841): set_light_backlight: 67
,D/qdlights(  841): set_light_backlight: 64
,D/qdlights(  841): set_light_backlight: 60
,D/qdlights(  841): set_light_backlight: 57
,D/qdlights(  841): set_light_backlight: 54
,D/qdlights(  841): set_light_backlight: 50
,D/qdlights(  841): set_light_backlight: 47
,D/qdlights(  841): set_light_backlight: 44
,D/qdlights(  841): set_light_backlight: 40
,D/qdlights(  841): set_light_backlight: 37
,D/qdlights(  841): set_light_backlight: 34
,D/qdlights(  841): set_light_backlight: 30
,D/qdlights(  841): set_light_backlight: 27
,D/qdlights(  841): set_light_backlight: 24
,D/qdlights(  841): set_light_backlight: 20
,D/qdlights(  841): set_light_backlight: 17
,D/qdlights(  841): set_light_backlight: 14
,D/qdlights(  841): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 154437956508; DSPS: 5152037; Offset : -2799810531
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36990 ms ago)
I/PowerManagerService(  841): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37003 ms ago)
,W/ContextImpl(  841): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  841): Sleeping (uid 1000)...
D/LPWGController(  841): [updateScreenState] screen on = false
D/LPWGController(  841): disable proximity sensor
,D/LPWGController(  841): enable proximity sensor
I/SensorManager(  841): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@30f77c4b] by com.android.server.power.ProximitySensorListener.enable():120
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
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37045 ms ago)
I/Adreno-EGL(  841): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  841): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  841): Build Date: 03/02/15 Mon
I/Adreno-EGL(  841): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  841): Remote Branch: 
I/Adreno-EGL(  841): Local Patches: 
I/Adreno-EGL(  841): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1300 us)
,I/Sensors (  417): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
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
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  841): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  841): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  841): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  841): Excessive delay in setPowerMode(): 214ms
I/QCOM PowerHAL(  841): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  841): sendKtScanInterval  mRtspPlay : false
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 841
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/WifiServerServiceExt(  841): set CMD_KT_SCAN_INTERVAL
,I/Sensors (  417): sns_pwr.c(301):releasing wakelock
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/GpsLocationProvider(  841): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1801): lockStatus = 0
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/SplitWindow(  841): check instance of lgWin Window{35e51ce6 u0 SearchPanel}
,D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
D/InputDispatcher(  841): Window went away: Window{28f2e960 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  841): JNI:system_update. Event-0
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2693): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:16:53
D/WeatherService( 2693): 2 : ACTION screen on
,D/WeatherService( 2693): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2693): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2693): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:16:53
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): ACTION_SCREEN_ON
,D/AppCleanupService( 3997): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 841
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  841): CMD_SCREEN_OFF 
D/WifiController(  841): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  841): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
,D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2693): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:16:54
D/WeatherService( 2693): 2 : ACTION screen off
D/WeatherService( 2693): 2 : TimeTick Receiver Unregister
D/WeatherService( 2693): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:16:54
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): ACTION_SCREEN_OFF
D/AppCleanupService( 3997): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3997): AppUsageStatsSaveTask
E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
,D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{13f9227 type 2 when 162932 com.android.systemui} when 162932
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1750): getCallState : 0
D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{17c34cd4 type 2 when 144554 com.google.android.gms} when 144554
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{1f887e7d type 0 when 1454973418019 com.google.android.gms} when 1454973418019
I/EventLogService( 5544): Aggregate from 1454973364365 (log), 1454971617914 (data)
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1454973418344 tag=VacuumService
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 52130(3MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/22MB, paused 1.657ms total 109.609ms
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 11706 seconds from now (1454973418846)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 174438552646; DSPS: 5807417; Offset : -2799826462
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=951804449, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{6350646 type 2 when 181251 android} when 181251
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=951804449 [*alarm*], flags=0x0
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  459): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{2ca13007 type 2 when 189425 com.google.android.gms} when 189425
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 194439359878; DSPS: 6462803; Offset : -2799811281
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 214440272632; DSPS: 7118193; Offset : -2799813456
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 234440947259; DSPS: 7773575; Offset : -2799810424
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  459): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 254441640013; DSPS: 8428958; Offset : -2799819730
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 274442476359; DSPS: 9084345; Offset : -2799807437
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 5368): --= Surplus to requirements =--
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ****TEST TOOK:  ms ****
I/jxcore-log( 5368): 
I/jxcore-log( 5368): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5368): 
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 294446023017; DSPS: 9739821; Offset : -2799802329
,D/AndroidRuntime( 7812): 
D/AndroidRuntime( 7812): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7812): CheckJNI is OFF
,D/AndroidRuntime( 7812): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  841): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  841): Killing 5368:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  841): Skipping PackageSetting{2fad1f37 com.example.hello/10317} due to missing metadata
,I/WindowState(  841): WIN DEATH: Window{3ebf593f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  841): Focus left window: Window{3ebf593f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  841): Window went away: Window{3ebf593f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  841):   Force finishing activity ActivityRecord{207865a u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  841): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
,W/ActivityManager(  841): Spurious death for ProcessRecord{9adc534 5368:com.test.thalitest/u0a316}, curProc for 5368: null
,I/ActivityManager(  841): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  841):   Force finishing activity ActivityRecord{207865a u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  841): Duplicate finish request for ActivityRecord{207865a u0 com.test.thalitest/.MainActivity t222 f}
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 21904(1371KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 12MB/20MB, paused 1.869ms total 78.930ms
,I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/System.err( 3572): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/art     ( 5544): Explicit concurrent mark sweep GC freed 8358(463KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 13MB/18MB, paused 2.535ms total 101.629ms
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3572): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3572): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3572): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3572): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3572): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3572): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3572): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3572): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3572): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3572): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3572): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7844 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     (  841): Explicit concurrent mark sweep GC freed 58902(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.866ms total 207.294ms
,I/art     (  841): WaitForGcToComplete blocked for 32.407ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/administrator(  841): Handling package changes for user 0
,I/art     (  841): Explicit concurrent mark sweep GC freed 4530(264KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.049ms total 190.747ms
I/art     (  841): WaitForGcToComplete blocked for 372.881ms for cause Explicit
,I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
,I/Activity( 1877): Activity.onPostResume() called 
W/ActivityManager(  841): Activity pause timeout for ActivityRecord{489385f u0 com.lge.launcher2/.Launcher t221}
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1374): handleShortcutListChanged...
,W/ResourcesManager( 7844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7844): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/Choreographer( 1877): Skipped 30 frames!  The application may be doing too much work on its main thread.
W/ResourcesManager( 7844): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
,D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
,I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f5163f7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f5163f7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  841): Focus entered window: Window{1ad7c45e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/NotificationService(  841): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
D/JobSchedulerService(  841): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  841): removeObsoleteFile: deleting file=222_task.xml
,W/InputMethodManagerService(  841): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  841): Got RemoteException sending setActive(false) notification to pid 5368 uid 10316
,I/LGEmail ( 7844): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7844): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  841): Explicit concurrent mark sweep GC freed 6409(383KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.383ms total 238.819ms
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  841): Timeline: Activity_windows_visible id: ActivityRecord{489385f u0 com.lge.launcher2/.Launcher t221} time:296195
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 7812): Shutting down VM
,W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1628): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/PackageChangeReceiver( 7844): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/AppUp4:PreloadHelper( 7481): added Exclude : com.test.thalitest
,W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  841): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7872 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  841): Killing 7154:com.google.android.talk/u0a61 (adj 15): empty #11
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.451ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.994ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 326us total 21.514ms
,W/libprocessgroup(  841): failed to open /acct/uid_10061/pid_7154/cgroup.procs: No such file or directory
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,W/ResourceType(  841): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
