#### Test 58135655812b57f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/SystemConfig( 5417): BUILD Country: EU
I/SystemConfig( 5417): BUILD Operator: OPEN
,--------- beginning of system
I/ActivityManager(  960): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5441 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  960): Killing 5117:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10010/pid_5117/cgroup.procs: No such file or directory
I/SystemConfig( 5417): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5417): existFile = false
I/SystemConfig( 5417): canReadFile = false
I/SystemConfig( 5417): systemFeature RCS result false
D/SystemConfig( 5417): refreshRcsSupport() :false
I/LockScreenSettings( 5441): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5441): New app installed broadcast received ..
I/LockScreenSettings( 5441): Number of installed packages  1
I/ActivityManager(  960): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5464 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  960): Killing 4311:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10006/pid_4311/cgroup.procs: No such file or directory
D/EulaProviderUpdateObserver( 5464): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5464): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5223): android.intent.action.PACKAGE_ADDED : com.test.thalitest
D/AndroidRuntime( 5447): 
D/AndroidRuntime( 5447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5447): CheckJNI is OFF
I/ActivityManager(  960): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5483 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  960): Killing 5243:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10081/pid_5243/cgroup.procs: No such file or directory
V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{227cd98a type 2 when 80223 android} when 80223
D/AndroidRuntime( 5447): Calling main entry com.android.commands.am.Am
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  960): setTaskToReturnTo : TaskRecord{42cdbfb #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  960): setTaskToReturnTo : TaskRecord{42cdbfb #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  960): AppWindowTokenEx init.. 
D/ContextHelper(  960): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  960): Focus left window: Window{25a3c3a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5447): Shutting down VM
D/SplitWindow(  960): check instance of lgWin Window{3d3760ad u0 Starting com.test.thalitest}
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5517 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1942): Closing mic
I/MicrophoneInputStream( 1942): mic_close com.google.android.apps.gsa.speech.audio.u@e9aae2
V/AudioRecord( 1942): stop()
D/AudioRecord( 1942): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb435b000
I/WindowStateAnimator(  960): Starting window displayed
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e88488e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = 15000000
D/BarTransitions( 1374): draw background and invalidate : color = 13121212
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
,V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb435b000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): releasing 16 from 1942 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  960): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1942): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1992): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3219): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 2745): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb435b000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioFlinger(  282): removeClient_l() pid 1942, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1942): Stopping hotword detection.
I/HotwordRecognitionRnr( 1942): Hotword detection finished
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ContextHelper( 5517): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5517): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/AlertService( 3843): Beginning updateAlertNotification
I/LibraryLoader( 5517): Time to load native libraries: 6 ms (timestamps 962-968)
I/LibraryLoader( 5517): Expected native library version number "",actual native library version number ""
D/AlertService( 3843): No fired or scheduled alerts
I/NotificationManager( 3843): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3843): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3843): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
V/WebViewChromiumFactoryProvider( 5517): Binding Chromium to main looper Looper (main, tid 1) {182cc70a}
I/LibraryLoader( 5517): Expected native library version number "",actual native library version number ""
I/chromium( 5517): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/AlarmScheduler( 3843): No events found starting within 1 week.
I/BrowserStartupController( 5517): Initializing chromium process, singleProcess=true
W/art     ( 5517): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5517): ApplicationContext is null in ApplicationStatus
I/GAv4    ( 5483): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5483):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5483):   adb logcat -s GAv4
W/chromium( 5517): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/GAv4    ( 5483): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/libEGL  ( 5517): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5517): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
W/GAv4    ( 5483): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5483): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5483): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
V/AudioPolicyService(  282): registerClient() client 0xb551c640, uid 10316
D/BluetoothManagerService(  960): Message: 20
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4273592:true
D/BluetoothAdapterService(509102550)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@269e8edc
W/art     ( 5517): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5517): onDetachedFromWindow called when already detached. Ignoring
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,D/SystemWebViewEngine( 5517): CordovaWebView is running on device made by: LGE
W/ContextImpl( 5483): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5483): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5483): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  960): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5581 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/art     ( 5517): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5517): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 5483): CheckpointMarkThreadRoots callback created = 0xaaf2a240
,V/JNIHelp ( 5483): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Activity( 5517): Activity.onPostResume() called 
,I/art     ( 5483): CheckpointMarkThreadRoots callback created = 0xb002ded0
D/OpenGLRenderer( 5517): Render dirty regions requested: true
I/OpenGLRenderer( 5517): Initialized EGL, version 1.4
W/ResourcesManager( 5581): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 5517): Enabling debug mode 0
D/Atlas   ( 5517): Validating map...
,D/SplitWindow(  960): check instance of lgWin Window{35e26189 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5517): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  960): Killing 5308:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/System  ( 5483): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5483): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  960): failed to open /acct/uid_10014/pid_5308/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InputDispatcher(  960): Focus entered window: Window{35e26189 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  960): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +1s256ms
I/Timeline(  960): Timeline: Activity_windows_visible id: ActivityRecord{11425418 u0 com.test.thalitest/.MainActivity t222} time:81781
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Timeline( 5517): Timeline: Activity_idle id: android.os.BinderProxy@25fc8161 time:81804
W/BindingManager( 5517): Cannot call determinedVisibility() - never saw a connection for the pid: 5517
,D/JsMessageQueue( 5517): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  960): Killing 5331:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10021/pid_5331/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5623 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,D/jxcore_app_log( 5517): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622895104
,I/chromium( 5517): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 5623): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 5517): CheckpointMarkThreadRoots callback created = 0x9aa20510
I/art     ( 5517): CheckpointMarkThreadRoots callback created = 0x9aa204e0
,D/Finsky  ( 5623): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,W/Settings( 5623): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5623): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5623): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@a7e52d3 on behalf of 5623
I/art     ( 4012): Explicit concurrent mark sweep GC freed 9460(464KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 474us total 39.310ms
,I/NotificationManager( 5623): com.android.vending: cancel(1003285959) by com.android.vending
,D/Ads     ( 5623): Skipping gmscore version check
D/Finsky  ( 5623): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5623): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5623): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  960): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5665 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5623): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5623): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  960): Killing 5357:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10009/pid_5357/cgroup.procs: No such file or directory
,W/ResourcesManager( 5665): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5665): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5665): VM with version 2.1.0 has multidex support
I/MultiDex( 5665): install
I/MultiDex( 5665): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5665): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5665): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5665): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cba0c22: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5665): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5665): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5665): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5665): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5665): Reading stored module config
,D/ChimeraCfgMgr( 5665): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5665): Loading module APK com.google.android.play.games
D/NativeLibraryUtils( 5665): Install completed successfully. count=14 extracted=0
,I/art     ( 5665): CheckpointMarkThreadRoots callback created = 0xb002d4f0
,I/art     ( 5665): CheckpointMarkThreadRoots callback created = 0xb002d4d0
,I/PeopleDatabaseHelper( 5665): cleanUpNonGplusAccounts done.
,W/jxcore-log( 5517): Initializing JXcore engine
,W/jxcore-log( 5517): JXcore engine is ready
I/art     (  960): Explicit concurrent mark sweep GC freed 21120(1029KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.216ms total 178.274ms
,D/ChimeraCfgMgr( 5665): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5665): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5665): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5665): Submit a task: k
,W/Thread-657( 5641): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5873]" dev="sockfs" ino=5873 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-657( 5641): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-657( 5641): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6022]" dev="sockfs" ino=6022 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-657( 5641): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-657( 5641): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-657( 5641): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24204]" dev="sockfs" ino=24204 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/ChimeraCfgMgr( 5665): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/jxcore-log( 5517): Starting JXcore engine
,D/ChimeraCfgMgr( 5665): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5665): Processing package: com.test.thalitest
,D/GassUtils( 5665): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5665): Found info for package com.test.thalitest in db.
,I/Icing   ( 5665): Storage manager: low false usage 1.73MB avail 2.38GB capacity 4.06GB
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,W/BaseAppContext( 5665): Using Auth Proxy for data requests.
E/MDM     ( 1735): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 5665): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5665): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/BaseAppContext( 5665): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5665): Using Auth Proxy for data requests.
D/InitAlarmsService( 3843): Clearing and rescheduling alarms.
,W/jxcore-log( 5517): Platform android
W/jxcore-log( 5517): 
W/jxcore-log( 5517): Process ARCH arm
W/jxcore-log( 5517): 
,I/ActivityManager(  960): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5726 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocationInitializer( 5665): Restart initialization of location
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BaseAppContext( 5665): Using Auth Proxy for data requests.
W/ResourcesManager( 5726): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5665): Using Auth Proxy for data requests.
,W/BaseAppContext( 5665): Using Auth Proxy for data requests.
W/BaseAppContext( 5665): Using Auth Proxy for data requests.
D/CalendarProvider2( 5726): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3adcacb9
,I/ActivityManager(  960): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5752 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 395us total 23.718ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.342ms
,D/CalendarProvider2( 5726): [getOrCreateCalendarAlarmManager]
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 26.196ms
,W/BaseAppContext( 5665): Using Auth Proxy for data requests.
W/GCoreFlp( 1735): No location to return for getLastLocation()
I/CalendarProvider2( 5726): Created com.android.providers.calendar.CalendarAlarmManager@182cc70a(com.android.providers.calendar.CalendarProvider2@3adcacb9)
W/FusedLocationProvider( 1735): location=null
D/CalendarProvider2( 5726): Scheduling check of next Alarm
,D/CalendarProvider2( 5726): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  960): Killing 3843:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10013/pid_3843/cgroup.procs: No such file or directory
W/IcingInternalCorpora( 5665): getNumBytesRead when not calculated.
,I/jxcore-log( 5517): JXcore Cordova bridge is ready!
I/jxcore-log( 5517): 
,W/jxcore-log( 5517): JXcore engine is started
W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{f193f49 type 0 when 1454948624774 com.google.android.gms} when 1454948624774
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{137af56f type 0 when 1454948638606 com.google.android.googlequicksearchbox} when 1454948638606
I/Icing   ( 5665): updateResources: need to parse f{com.google.android.gms}
,I/Gmail   ( 5752): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5517): Toggling radios to true
I/jxcore-log( 5517): 
,D/BluetoothAdapter( 5517): enable(): BT is already enabled..!
W/GAV2    ( 5752): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/WifiServiceImplEx(  960): setWifiEnabled: true pid=5517, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  960): setWifiEnabled: true pid=5517, uid=10316
D/WifiServiceImplEx(  960): disconnect pid=5517, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  960): reconnect pid=5517, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5517): Radios toggled
I/jxcore-log( 5517): 
I/jxcore-log( 5517): My device name is: LGE-LG-D722
I/jxcore-log( 5517): 
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/wpa_supplicant( 2805): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2805): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  960): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  960): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/Gmail   ( 5752): Error finding the version of the Email provider.....
E/Gmail   ( 5752): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5752): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5752): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5752): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5752): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5752): We do not support migrating this version of the Email provider.
,D/LGWifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
I/Gmail   ( 5752): getAccountsCursor
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1735): Read error: ssl=0xaaee0e00: I/O error during system call, Connection timed out
I/art     ( 4012): Explicit concurrent mark sweep GC freed 2989(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 6.189ms total 36.296ms
V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xaaee0e00: I/O error during system call, Broken pipe
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  960): hidePasspointNotification off =false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:23:58.989 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  960): Start Disconnecting Watchdog 1
,D/WifiHS20(  960): hidePasspointNotification off =false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:23:58.998 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  960): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  960): ignoring duplicate network state non-change
I/wpa_supplicant( 2805): wlan0: CTRL-EVENT-SCAN-STARTED 
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGWifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/WifiHS20(  960): hidePasspointNotification off =false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  960): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:23:59.018 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ChimeraCfgMgr( 5665): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5665): Module APK com.google.android.play.games already loaded
D/ConnectivityService(  960): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiNetworkAgent(  960): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): DefaultState{ when=-13ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): Forcing reevaluation
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:23:59.043 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  960): hidePasspointNotification off =false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:23:59.049 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateDISCONNECTED
,D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateSCANNING
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
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/ActivityManager(  960): Killing 5380:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/ConnectivityService(  960): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  960): disableDataServiceNotify
D/DSQN    (  960): stop dsqn bin
,I/CalendarProvider2( 5726): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ConnectivityService(  960): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/DhcpStateMachine(  960): StoppedState
,D/DhcpStateMachine(  960): StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/ContentResolver( 5726): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ConnectivityService(  960): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  960): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): Disconnected - quitting
D/CSLegacyTypeTracker(  960): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  960): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/art     ( 1735): Explicit concurrent mark sweep GC freed 23871(1350KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/22MB, paused 1.534ms total 99.719ms
,W/ActivityManager(  960): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  960): failed to open /acct/uid_10011/pid_5380/cgroup.procs: No such file or directory
D/ConnectivityService(  960): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  960): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  960): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  960): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  960):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  960): MasterInitialState.processMessage what=3
D/Tethering(  960): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1841): |CORE| No family connected
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,V/NetworkPolicy(  960): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  960): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  960): Removing idletimer
W/Settings(  960): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/Gmail   ( 5752): Observing account changes for notifications
I/ActivityManager(  960): Killing 5398:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  960): failed to open /acct/uid_10023/pid_5398/cgroup.procs: No such file or directory
,W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Gmail   ( 5752): notifyAccountChanged
,I/Icing   ( 5665): Internal init done: storage state 0
I/Gmail   ( 5752): getAccountsCursor
I/Gmail   ( 5752): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/InstanceID/Rpc( 5665): Found 10006
,I/NotificationManager( 5665): com.google.android.gms: cancel(10436) by com.google.android.gms
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5752): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5752): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5752): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5820 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Icing   ( 5665): Post-init done
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5752): getAccountsCursor
,D/PhoneMonitor( 5820): Register our PhoneStateListener
,I/ActivityManager(  960): Killing 5417:com.android.contacts/u0a18 (adj 15): empty #11
,D/PhoneMonitor( 5820): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5820): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5820): [parse] Load xml
,V/TelephonyAutoProfiling( 5820): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5820): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5820): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     (  960): Explicit concurrent mark sweep GC freed 29355(1332KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.831ms total 166.466ms
,W/libprocessgroup(  960): failed to open /acct/uid_10018/pid_5417/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WeatherService( 2726): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:24:0
,D/WeatherService( 2726): 2 : TimeTick Intent And Screen On
D/WeatherService( 2726): 2 : SDK version : 21
W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2726): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2726): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2726): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2726): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2726): 2 : This is isUpdating : false
D/WeatherService( 2726): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2726): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2726): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2726): 2 : Fixed theme : optimus
D/WeatherReflect( 2726): 2 : Map key string is -2
D/lim     ( 2726): 2 : time = 17:24
I/WeatherReflect( 2726): Model Name : LG-D722
D/WeatherTheme( 2726): 2 : Different view - status_min_formatted : 23 != 24
D/WeatherTheme( 2726): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2726): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2726): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2726): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2726): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2726): forecast size is 0
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2726): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2726): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2726): setTouchIntent, appWidgetId: 2
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5847 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Theme_WeatherAncestor_optimus( 2726): url is : null
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2805): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2726): 2 : update view, appWidgetId: 2
D/WeatherService( 2726): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:24:0
,D/LocSvc_java(  960): onReceive
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.187 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2805): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.195 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateASSOCIATED
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateFOUR_WAY_HANDSHAKE
W/ResourcesManager( 5847): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.233 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2805): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2805): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.234 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/WifiServiceExtension(  960): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
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
I/WifiServerServiceExt(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  960): setSecurityType  : 2
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.287 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.288 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  960): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: ,false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  960): Got NetworkAgent Messenger
D/ConnectivityService(  960): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  960): NetworkAgent connected
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
E/WifiConfigStore(  960): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  960): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  960): Start Dhcp Watchdog 2
D/DhcpStateMachine(  960): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  960): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  960): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27b5c207 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  960): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27b5c207 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateCOMPLETED
D/ConnectivityService(  960): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  960): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  960): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  960): ignoring duplicate network state non-change
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  960): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  960): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,D/WifiHS20(  960): [PASSPOINT] passpointNotification: hs20AP list is checked
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.482 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  960): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine(  960): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.489 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.501 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
E/ConnectivityService(  960): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  960): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:00.503 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  960): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  960): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  960): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  960): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  960): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  960): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  960): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
D/ConnectivityService(  960):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  960):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  960):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  960): currentScore = 0, newScore = 20
D/ConnectivityService(  960):    accepting network in place of null
D/ConnectivityService(  960): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  960): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  960):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  960): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  960): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): [LWD] Start DNSResolver start to wait
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/Tethering(  960): MasterInitialState.processMessage what=3
D/ConnectivityService(  960): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  960): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  960): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  960): validation of new default Network = false
D/ConnectivityService(  960): Default network via Wi-Fi connected. start DSQN
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/DSQN    (  960): enableDataServiceNotify 
D/DSQN    (  960): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): [LWD] wait 500ms before dns check
D/ConnectivityService(  960): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  960): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/DSQN    ( 5876): DSQN samuel.seo ver 141203
E/DSQN    ( 5876): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5876): created command queue thread
I/DSQN    ( 5876): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5876): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/NetworkPolicy(  960): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/CheckinService( 5665): Checkin interval check for package: unspecified last checkin: 1454948631071 min interval config: 0 actual interval: 9523
,I/CheckinService( 5665): Disabling old GoogleServicesFramework version
,I/Icing   ( 5665): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/DhcpStateMachine(  960): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  960): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/dhcpcd  ( 5883): version 5.5.6 starting
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
E/dhcpcd  ( 5883): get_duid: Read-only file system
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/CheckinService( 5665): Checking schedule, now: 1454948640703 next: 1454948661029
,I/CheckinService( 5665): active receiver: disabled
I/Babel_SMS( 5847): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5847): MmsConfig.loadMmsSettings
,I/dhcpcd  ( 5883): wlan0: rebinding lease of 192.168.1.134
,I/Babel_SMS( 5847): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 5847): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5847): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5847): MmsConfig.loadFromResources
E/Babel_SMS( 5847): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5847): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 5847): CheckpointMarkThreadRoots callback created = 0xaaf22f40
,D/Icing   ( 5665): Loaded CLD2 Version V2.0 - 20141016
D/SensorManager( 5847): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5847): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5847): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5847): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5847): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5847): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5847): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5847): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5847): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5847): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5847): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5847): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5847): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5847): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5847): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5847): found sensor: Motion Accel, handle=46
,I/art     ( 5847): CheckpointMarkThreadRoots callback created = 0xaaf22f30
I/Icing   ( 5665): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/art     ( 5847): Suspending all threads took: 15.496ms
,W/Settings( 5847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5847): startup - clean
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/Babel   ( 5847): deleted: false for 0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): [LWD] DNSResolver start dns
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  960): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5876): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5876): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5876): dsqn report finish
D/DSQN    (  960): DSQM DsqnNotification wlan0  1
D/DSQN    (  960): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:24:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454948641135], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454948641114]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  960): Validated
D/ConnectivityService(  960): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  960):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  960):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  960): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  960): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  960): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  960): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/WIFI    (  960): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  960):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/ActivityManager(  960): Process com.lge.bnr (pid 5223) has died
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
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
W/AudioCapabilities( 5847): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5847): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5847): Unsupported mime audio/g726
W/AudioCapabilities( 5847): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5847): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5847): Unsupported mime video/mjpg
D/administrator(  960): Handling package changes for user 0
,W/VideoCapabilities( 5847): Unsupported mime video/theora
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/AudioCapabilities( 5847): Unsupported mime audio/evrc
W/AudioCapabilities( 5847): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5847): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5847): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5847): Unsupported mime audio/qcelp
W/AudioCapabilities( 5847): Unsupported mime audio/evrc
W/VideoCapabilities( 5847): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5847): Unsupported profile 4 for video/mp4v-es
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/VideoCapabilities( 5847): Unrecognized profile 2130706433 for video/avc
I/NotificationService(  960): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  960): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/VideoCapabilities( 5847): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5847): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5847): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  960): Process com.google.android.apps.docs (pid 5483) has died
,I/BackupManagerService(  960): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/WifiDataContinuityService(  960): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  960): set CMD_CAPTIVE_CHECK_COMPLETED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  960): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  960): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@7b26839
D/ConnectivityService(  960): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager(  960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  960): Process com.lge.lockscreensettings (pid 5441) has died
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
I/vclib   ( 5847): onServiceConnected
,W/Babel   ( 5847): Attempted to change video mute state without an active call.
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  960): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:01.829 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  960): identical MTU - not setting
D/Nat464Xlat(  960): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  960): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  960):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  960): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
D/ConnectivityService(  960): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  960): enableDataServiceNotify 
D/DSQN    (  960): start dsqn bin
W/ResourcesManager( 5847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DSQN    (  960): dsqn is running restart
W/ResourceType(  960): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/DSQN    ( 5904): DSQN samuel.seo ver 141203
E/DSQN    ( 5904): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5904): created command queue thread
I/DSQN    ( 5904): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5904): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/ActivityManager(  960): Process com.google.android.apps.plus (pid 5581) has died
,I/dhcpcd  ( 5883): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,V/JNIHelp ( 5847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dhcpcd  ( 5883): wlan0: leased 192.168.1.134 for 86400 seconds
I/ActivityManager(  960): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5909 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 5847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5847): Installed default security provider GmsCore_OpenSSL
,I/AudioManager( 5200): getMode name:com.lge.qremote
,I/ActivityManager(  960): Process com.lge.eula (pid 5464) has died
I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AudioManager( 5200): getMode name:com.lge.qremote
I/NotificationManager( 5847): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AudioManager( 5200): getMode name:com.lge.qremote
I/BackgroundMemoryTrimmer( 1942): Trimming objects from memory, since app is in the background.
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AudioManager( 5200): getMode name:com.lge.qremote
,I/AudioManager( 5200): getMode name:com.lge.qremote
D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocationProviderProxy(  960): applying state to connected service
D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  960): onReceive
D/LocSvc_java(  960): got connectivity action
D/LocSvc_java(  960): broadcast - no network connections
D/LocSvc_java(  960): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  960): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  960): onReceive
D/LocSvc_java(  960): got connectivity action
D/LocSvc_java(  960): broadcast - no network connections
D/LocSvc_java(  960): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  960): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  960): DHCPV4 succeeded on wlan0
,D/GpsLocationProvider(  960): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  960): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  960): RunningState
D/GpsLocationProvider(  960): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  960): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/MDM     ( 1735): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5665): Restart initialization of location
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5200): getMode name:com.lge.qremote
D/UEI.SmartControl( 5909): Quickset Services start...
,I/UEI.SmartControl( 5909): Manufacture = LGE
D/UEI.SmartControl( 5909): File observer start...
E/UEI.SmartControl( 5909): IR Port is disabled: false
D/UEI.SmartControl( 5909): Starting file observer...
D/UEI.SmartControl( 5909): Extracting JNI libs...
D/UEI.SmartControl( 5909): --- this system supports 32-bit or 64-bit only
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/NotificationManager( 5847): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5959 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/BackgroundMemoryTrimmer( 1942): Trimming objects from memory, since app is in the background.
,I/ActivityManager(  960): Process com.google.android.gm (pid 5752) has died
,I/AppUp4:AppBoxCP( 5959): onCreate
,W/AppUp4:DB( 5959):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5959):  setFingerPrint start
,I/AppUp4:DB( 5959):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5959):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5959):  SDK version = 0
I/AppUp4:DB( 5959):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5959): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5959): onReceive
I/AppUp4:CustModeStarterReceiver( 5959): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5959): Context : android.app.ReceiverRestrictedContext@2a3722ac
D/AppUp4:CustFacade( 5959): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5959): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5959): begin check event
I/AppUp4:CustModeStarterReceiver( 5959): Event For Nothing, skip.
,D/UEI.SmartControl( 5909): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5909): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5909): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5909): --- Selecting new region: 2
,I/UEI.SmartControl( 5909): -- Running on KitKat(19) and above! JNI will be used.
I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5985 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{3888d0af type 2 when 89929 com.google.android.gms} when 89929
D/UEI.SmartControl( 5909): Platform has CIR...
D/UEI.SmartControl( 5909): NO CIR support, need to check package...
,I/UEI.SmartControl( 5909): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5909): QS Service created
E/UEI.SmartControl( 5909): QS start get config
,W/ResourcesManager( 5985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5985): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5985): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5909): Loading JNI Libs...
D/UEI.SmartControl( 5909):  configuring local db...
,I/AppConfig( 5985): Total System Memory = 906309632
,I/GalleryUtils( 5985): Application Heap = 96 MB
I/AppConfig( 5985): App Tier : NOT_DEF
D/SystemHelper( 5985): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6004 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{18305cbc type 2 when 90206 com.android.providers.calendar} when 90206
D/UEI.SmartControl( 5909):  ---- Has DB8: true
,D/UEI.SmartControl( 5909): QS start statue = true Error code = 0
D/UEI.SmartControl( 5909): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5909): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5909): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5909): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5909): IrrcClient ++ 
D/irrcClient( 5909): getIrrcService ++ 
,D/irrcClient( 5909): getIrrcService -- 
D/irrcClient( 5909): IrrcClient -- 
W/irrc_jni( 5909): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5909): Services init done
,I/UEI.SmartControl( 5909): Device manager: loading config....
D/UEI.SmartControl( 5909): QS Service init finished
D/UEI.SmartControl( 5909): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5909): QS Service version code: 1073
D/UEI.SmartControl( 5909): Service requested: Control
D/UEI.SmartControl( 5909): Config is loaded...
W/ResourcesManager( 6004): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6004): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6004): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6004): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6004): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5909):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 5909): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 5909): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5909): Internal service binding...
D/UEI.SmartControl( 5909): -----IControl: 11
D/UEI.SmartControl( 5909): Caller: com.lge.qremote
D/UEI.SmartControl( 5909): ------------ IControl registerCallback...
I/UEI.SmartControl( 5909): Registering callback...
D/UEI.SmartControl( 5909): -----IControl: 19
,D/UEI.SmartControl( 5909): Caller: com.lge.qremote
I/UEI.SmartControl( 5909): Registering Services Ready callback...
I/UEI.SmartControl( 5909): Notify client services are ready...
D/UEI.SmartControl( 5909): -----IControl: 8
D/UEI.SmartControl( 5909): Caller: com.lge.qremote
I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 17:24:03.37 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/SystemConfig( 6004): BUILD Country: EU
I/SystemConfig( 6004): BUILD Operator: OPEN
,I/SystemConfig( 6004): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6004): existFile = false
,I/SystemConfig( 6004): canReadFile = false
I/SystemConfig( 6004): systemFeature RCS result false
D/SystemConfig( 6004): refreshRcsSupport() :false
,V/WifiInternetCheck(  960): Single check msg out of sync, ignoring.
,I/ActivityManager(  960): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6026 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  960): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  960): onReceive
D/LocSvc_java(  960): got connectivity action
D/LocSvc_java(  960): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  960): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  960): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  960): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/LockScreenSettings( 6026): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6026): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6026): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6026): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6026): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6026): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  960): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6047 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 1942): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,W/ResourcesManager( 6047): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,I/ActivityManager(  960): Killing 5726:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  960): failed to open /acct/uid_10014/pid_5726/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5665): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/AudioManager( 5200): getMode name:com.lge.qremote
I/PackageBroadcastService( 5665): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 5200): getMode name:com.lge.qremote
I/Icing   ( 5665): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  960): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6079 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 5665): Background partial concurrent mark sweep GC freed 23627(1384KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 13MB/21MB, paused 1.443ms total 100.382ms
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  960): propertyValue:false
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  960): propertyValue:false
I/DSQN    ( 5904): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5904): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
,D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5904): dsqn report finish
D/DSQN    (  960): DSQM DsqnNotification wlan0  1
D/DSQN    (  960): start to monitor internet connection
V/WifiInternetCheck(  960): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  960): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6110 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/art     (  960): Explicit concurrent mark sweep GC freed 71973(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.743ms total 178.011ms
,I/ActivityManager(  960): Killing 5820:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10038/pid_5820/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 6110): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  960): Process com.lge.appbox.client (pid 5959) has died
,E/UpdateRequestReceiver( 6110): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6110): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6110): Received malformed URL while handling Gservices.CHANGED_ACTION
I/CheckinService( 5665): Checkin interval check for package: unspecified last checkin: 1454948631071 min interval config: 0 actual interval: 14538
,I/GservicesUpdateTask( 1942): Updating Gservices keys
I/CheckinService( 5665): Checking schedule, now: 1454948645619 next: 1454948661029
I/CheckinService( 5665): active receiver: disabled
I/SystemUpdateService( 5665): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5665): onCreate
,D/SystemUpdateService( 5665): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5665): cancelUpdate (empty URL)
I/SystemUpdateService( 5665): active receiver: disabled
,I/NotificationManager( 5665): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 5665): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 4012): Explicit concurrent mark sweep GC freed 3954(172KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.023ms total 37.485ms
,I/Icing   ( 5665): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5665): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/art     ( 4012): Explicit concurrent mark sweep GC freed 2802(107KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 845us total 24.850ms
,I/art     ( 5665): Explicit concurrent mark sweep GC freed 17334(1034KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/22MB, paused 1.235ms total 74.847ms
,D/SystemUpdateService( 5665): onDestroy
,I/EventLogService( 5665): Aggregate from 1454948623281 (log), 1454946824660 (data)
,E/DynamiteModule( 5665): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5665): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5665): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5665): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5665): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5665): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5665): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5665): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5665): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5665): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5665): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5665): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5665): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5665): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5665): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5665): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5665): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5665): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5665): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5665): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5665): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5665): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5665): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5665): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5665): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5665): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5665): 		... 17 more
E/DynamiteModule( 5665): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 5665): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5665): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 5665): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5665): Updating ocr activity enabled=false
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  960): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5665): Updating downloaded model state (gservices changed)
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{3aef1d77 type 0 when 1454948646678 com.android.vending} when 1454948646678
,D/Finsky  ( 5623): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     ( 4012): Explicit concurrent mark sweep GC freed 2538(100KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.326ms total 32.156ms
,I/NotificationManager(  960): android: cancelAsUser(-591465577) by android
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 19760(1326KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 1.635ms total 80.501ms
,D/GCM     ( 1735): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,I/GCoreUlr( 1735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1735): DispatchingService.onCreate()
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6192 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.674ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.121ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.902ms
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 94637571479; DSPS: 3199120; Offset : -3001511513
,I/ActivityManager(  960): Killing 5847:com.google.android.talk/u0a61 (adj 15): empty #11
,I/GCoreUlr( 1735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/libc-netbsd( 5623): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5623): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5623): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5623): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 6192): Register our PhoneStateListener
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 5623): propertyValue:false
D/libc-netbsd( 5623): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5623): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  960): failed to open /acct/uid_10061/pid_5847/cgroup.procs: No such file or directory
V/SetupWizard( 6192): Connected to Gservices successfully
,W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
D/PhoneMonitor( 6192): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6192): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6192): [parse] Load xml
V/TelephonyAutoProfiling( 6192): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6192): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/ActivityManager(  960): Killing 5985:com.android.gallery3d/u0a23 (adj 15): empty #11
D/PhoneMonitor( 6192): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
E/ctxmgr  ( 1735): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/libc-netbsd( 5623): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5623): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  960): failed to open /acct/uid_10023/pid_5985/cgroup.procs: No such file or directory
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
,D/LocationInitializer( 5665): Restart initialization of location
E/MDM     ( 1735): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/GCoreUlr( 1735): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  960): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6228 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
I/GCoreUlr( 1735): Unbound from all location providers
I/GCoreUlr( 1735): Place inference reporting - stopped
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ctxmgr  ( 1735): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1735): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/NotificationManager(  960): android: cancelAsUser(2) by android
I/GCoreUlr( 1735): DispatchingService.onDestroy()
I/GCoreUlr( 1735): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1735): Unbound from all location providers
I/GCoreUlr( 1735): Place inference reporting - stopped
,I/qtaguid ( 5623): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5623): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5623): untagSocket(41) failed with errno -22
D/Finsky  ( 5623): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  960): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6246 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/UEI.SmartControl( 5909): Internal timer expired: 1
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6228): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5623): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5623): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5623): untagSocket(41) failed with errno -22
,I/art     ( 4012): Explicit concurrent mark sweep GC freed 2806(110KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 449us total 29.976ms
I/art     (  960): Explicit concurrent mark sweep GC freed 26072(1318KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.842ms total 169.316ms
W/ResourcesManager( 6246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAV2    ( 6228): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/AlarmManager(  960): RTC_WAKEUP set : Alarm{369591d3 type 0 when 1454948648542 com.google.android.googlequicksearchbox} when 1454948648542
,I/MultiDex( 6246): VM with version 2.1.0 has multidex support
I/MultiDex( 6246): install
I/MultiDex( 6246): VM has multidex support, MultiDex support library is disabled.
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5517): 
,W/ActivityManager(  960): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 6228): Error finding the version of the Email provider.....
E/Gmail   ( 6228): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6228): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6228): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6228): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6228): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6228): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6228): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6228): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6228): We do not support migrating this version of the Email provider.
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6228): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6228): Observing account changes for notifications
V/JNIHelp ( 6246): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  960): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6289 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityThread( 6246): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6246): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cc2ab3c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6246): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6246): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6246): com.google.android.gms: cancel(39789) by com.google.android.gms
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 6246): Reading stored module config
,D/ChimeraCfgMgr( 6246): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 5623): CheckpointMarkThreadRoots callback created = 0xb002d930
,I/Gmail   ( 6228): notifyAccountChanged
,I/art     ( 5623): CheckpointMarkThreadRoots callback created = 0xb002d8f0
,I/Gmail   ( 6228): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6228): getAccountsCursor
D/NativeLibraryUtils( 6246): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  960): Process com.google.android.apps.plus (pid 6047) has died
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6228): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/CAR.SERVICE( 6246): Connecting to CarCallService...
,I/Gmail   ( 6228): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6228): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6289): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6289): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6289): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6289): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6289): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 6246): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6246): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6246): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6246): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6246): Creating a new PhoneAdapter instance
W/ActivityManager(  960): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6246): setListener: com.google.android.gms.car.dn@36cd1b3b
W/ActivityManager(  960): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6246): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6246): Starting CarCallService with initial phone null
,I/IndexDatabaseHelper( 6289): Using schema version: 115
I/IndexDatabaseHelper( 6289): Index is fine
,I/NotificationManager( 6246): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Gmail   ( 6228): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.SERVICE( 6246): Package validated; name: com.android.vending
I/NotificationManager( 5623): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5623): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
I/ActivityManager(  960): Process com.lge.qremote (pid 5200) has died
,D/UEI.SmartControl( 5909): Service.onUnbind: IControl
D/UEI.SmartControl( 5909): Service.onDestroy
D/UEI.SmartControl( 5909): Shutdown IRRCPlayer... 
W/irrc_jni( 5909): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5909): ~IrrcClient ++ 
D/irrcClient( 5909): ~IrrcClient -- 
W/irrc_jni( 5909): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5909): Blaster closed
D/UEI.SmartControl( 5909): Blaster closed
D/UEI.SmartControl( 5909): Shut down QS...
,D/UEI.SmartControl( 5909): Stopped file observer...
I/UEI.SmartControl( 5909): QS lib stop result = true
,D/UEI.SmartControl( 5909): QS shutdown complete
I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6320 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6320): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6341 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6341): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5517): 
D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22ea31a3:true
,D/BluetoothAdapterService(509102550)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@269e8edc
D/BluetoothAdapterService(509102550)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@269e8edc
I/art     ( 1735): Explicit concurrent mark sweep GC freed 25364(1511KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 1.831ms total 94.166ms
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6320): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6320): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5517): 
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5517): 
I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6361 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5517): 
,I/qtaguid ( 5623): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5623): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5623): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5517): 
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5517): 
,I/jxcore-log( 5517): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5517): 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 5623): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5623): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5623): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  960): Process com.android.contacts (pid 6004) has died
,I/Babel_SMS( 6361): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6361): MmsConfig.loadMmsSettings
I/Babel_SMS( 6361): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6361): MmsConfig.loadFromDatabase
,D/Finsky  ( 5623): [1] DailyHygiene.access$600: Logging device features
,E/Babel_SMS( 6361): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6361): MmsConfig.loadFromResources
E/Babel_SMS( 6361): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6361): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/AlarmManager(  960): RTC_WAKEUP set : Alarm{28831f64 type 0 when 1454948650841 com.android.vending} when 1454948650841
,D/DeviceConnectionService( 1735): client connected with version: 8296000
,D/SensorManager( 6361): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6361): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6361): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6361): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6361): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6361): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6361): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6361): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6361): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6361): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6361): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6361): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6361): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6361): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6361): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6361): found sensor: Motion Accel, handle=46
D/Finsky  ( 5623): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5623): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/art     ( 6361): CheckpointMarkThreadRoots callback created = 0xb002d890
,W/Settings( 6361): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6361): startup - clean
I/art     ( 6361): CheckpointMarkThreadRoots callback created = 0xb002d870
,I/Babel   ( 6361): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
,I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6320): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  960): Killing 6026:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/AudioCapabilities( 6361): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6361): Unsupported mime audio/adpcm
W/AudioCapabilities( 6361): Unsupported mime audio/g726
W/AudioCapabilities( 6361): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6361): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6361): Unsupported mime video/mjpg
W/VideoCapabilities( 6361): Unsupported mime video/theora
,W/AudioCapabilities( 6361): Unsupported mime audio/evrc
,W/AudioCapabilities( 6361): Unsupported mime audio/qcelp
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6361): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6361): Unsupported mime audio/qcelp
W/AudioCapabilities( 6361): Unsupported mime audio/evrc
W/VideoCapabilities( 6361): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6361): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  960): failed to open /acct/uid_10069/pid_6026/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Killing 5909:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/vclib   ( 6361): onServiceConnected
W/Babel   ( 6361): Attempted to change video mute state without an active call.
,I/NotificationManager( 6361): com.google.android.talk: cancel(10436) by com.google.android.talk
W/libprocessgroup(  960): failed to open /acct/uid_10089/pid_5909/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  960): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6390 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6390): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6390): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6390): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3758385f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2a3722ac, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3125b75, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@182cc70a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2b71fb7b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3649bd98, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@10ba39f1, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1e5849d6, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@39ad457, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@7e91b44, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3f27842d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@15e72d62, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3f0e5ef3, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1cfea7b0, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@11a53629, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@268ebdae, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@b25f74f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@269e8edc, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1b320be5, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2c0d06ba, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2774b96b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@30f3bcc8, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@25fc8161, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@df4d486, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2fa38147, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1debdd74, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@169ed29d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@839b312, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@270ceae3, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea35ce0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@71afb99, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@307bee5e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2219523f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1791670c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1596b855, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@414926a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@295ad35b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1b73e7f8, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@22d784d1, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@ae16b36, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@32694a37, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@28fb8ba
,D/GeneralPreferenceUtils( 6390): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6390): [init]
,I/Config  ( 6390): LGCalendar ver.4.40.17
I/Config  ( 6390): start check model
I/Config  ( 6390): start check native_ca
I/Config  ( 6390): Config Operator=OPEN, Country=EU
D/Config  ( 6390): [setDefaultValuesToPref]
D/Config  ( 6390): [parseProfiles]
D/ProfilesParser( 6390): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6390): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6390): [updateProfiletoCountryInfo]
D/GeneralPreference( 6390): [checkAndMigrateOldPreference]
D/AlertReceiver( 6390): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6390): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6390): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6390): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6390): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6390): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6390): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6390): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6390): onHandleIntent
,D/HolidayDataLoader( 6390): readJsonAsset : holiday.json
D/AlertService( 6390): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6390): [updateWidgets] 
D/MonthWidgetProvider( 6390): [onReceive]
D/CalendarWidgetProvider( 6390): [onReceive]
D/CalendarWidgetProvider( 6390): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6390): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6390): [onReceive]
,D/CalendarWidgetProvider( 6390): [onReceive]
D/CalendarWidgetProvider( 6390): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6390): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6390): onHandleIntent:holiday data empty
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6289): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6289): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6289): MCCMNC not supported: null
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6420 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 6361): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6361): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6361): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6361): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6420): onCreate
,W/AppUp4:DB( 6420):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6420):  setFingerPrint start
I/AppUp4:DB( 6420):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6420):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6420):  SDK version = 0
I/AppUp4:DB( 6420):  beforefinger == newfinger no write in DB
W/System  ( 6361): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6361): Installed default security provider GmsCore_OpenSSL
D/AppUp4:AppBoxApplication( 6420): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6420): onReceive
I/AppUp4:CustModeStarterReceiver( 6420): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6420): Context : android.app.ReceiverRestrictedContext@2a3722ac
D/AppUp4:CustFacade( 6420): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6420): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6420): begin check event
,I/AppUp4:CustModeStarterReceiver( 6420): Event For Nothing, skip.
I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6446 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 6079:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/art     (  960): Explicit concurrent mark sweep GC freed 18210(860KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.078ms total 164.420ms
W/libprocessgroup(  960): failed to open /acct/uid_10009/pid_6079/cgroup.procs: No such file or directory
,W/ResourcesManager( 6446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6446): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6446): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6446): Total System Memory = 906309632
I/GalleryUtils( 6446): Application Heap = 96 MB
,I/AppConfig( 6446): App Tier : NOT_DEF
D/SystemHelper( 6446): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6472 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  960): Killing 6110:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10003/pid_6110/cgroup.procs: No such file or directory
,I/GAv4-SVC( 5665): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 6228): Thread[GAThread,5,main]: No campaign data found.
W/ResourcesManager( 6472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6472): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6472): BUILD Country: EU
I/SystemConfig( 6472): BUILD Operator: OPEN
,I/ActivityManager(  960): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6506 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 6228:com.google.android.gm/u0a53 (adj 15): empty #11
I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.852ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 22.354ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.398ms
,W/libprocessgroup(  960): failed to open /acct/uid_10053/pid_6228/cgroup.procs: No such file or directory
,I/SystemConfig( 6472): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6472): existFile = false
I/SystemConfig( 6472): canReadFile = false
I/SystemConfig( 6472): systemFeature RCS result false
,D/SystemConfig( 6472): refreshRcsSupport() :false
I/LockScreenSettings( 6506): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6506): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 6506): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  960): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6527 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  960): Killing 6246:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10006/pid_6246/cgroup.procs: No such file or directory
,W/ActivityManager(  960): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
W/ResourcesManager( 6527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5665): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,I/ActivityManager(  960): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6553 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 5665): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5665): updateResources: need to parse f{com.google.android.gms}
,W/PackageSettings(  960): Skipping PackageSetting{15de6b8c com.example.hello/10317} due to missing metadata
,I/MusicStore( 6553): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6553): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6553): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6553): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6553): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6553): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6553): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6553): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6553): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12df4d07: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6553): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6553): GMSCore installation verified
I/ConfigStore( 6553): Config Database version: 1
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/MediaRouter( 6553): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6553): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6553): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6553): type=WIFI subType= reason=null isConnected=true
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6594 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6553): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6553): Using platform SSLCertificateSocketFactory
I/ActivityManager(  960): Killing 6289:com.android.settings/1000 (adj 15): empty #11
,W/ResourcesManager( 6594): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6594): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6594): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/Icing   ( 5665): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_6289/cgroup.procs: No such file or directory
,I/NotificationManager( 6553): com.google.android.music: cancel(1061) by com.google.android.music
D/Icing   ( 5665): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5665): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  960): Killing 6320:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_6320/cgroup.procs: No such file or directory
,I/LGEmail ( 6594): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6594): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6594): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  960): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6628 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6594): JNI_OnLoad()
I/HubEmail( 6594): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6594): registerNatives()
I/HubEmail( 6594): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6594): registerNativeMethods()
I/HubEmail( 6594): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6594): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  960): Killing 6192:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/Settings( 6594): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  960): failed to open /acct/uid_10038/pid_6192/cgroup.procs: No such file or directory
D/LGDMClient( 6628): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6628): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6420): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6420): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6420): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6420): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6420): onReceive
I/AppUp4:CustModeStarterReceiver( 6420): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6420): Context : android.app.ReceiverRestrictedContext@2a3722ac
D/AppUp4:CustFacade( 6420): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6420): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6420): begin check event
I/AppUp4:CustModeStarterReceiver( 6420): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6420): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/LGDMClient( 6628): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustModeStarterReceiver( 6420): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6420): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6420): handleAsyncCustNotification do not startCustService
D/LGDMClient( 6628): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6628): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6628): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/LgeMiscReceiver( 3219): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3219): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3219): networkInfo.isConnected() = false
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6664 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ContextImpl( 6628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6628): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6628): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6628): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6628): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6628): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  960): Killing 6446:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/AlertService( 6390): Beginning updateAlertNotification
,W/libprocessgroup(  960): failed to open /acct/uid_10023/pid_6446/cgroup.procs: No such file or directory
I/ActivityManager(  960): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6684 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PhoneMonitor( 6664): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6664): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6664): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  960): Killing 6472:com.android.contacts/u0a18 (adj 15): empty #11
,D/PhoneMonitor( 6664): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6664): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6664): [parse] Load xml
W/ResourcesManager( 6684): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/TelephonyAutoProfiling( 6664): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6664): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6664): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/CalendarProvider2( 6684): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3adcacb9
,W/libprocessgroup(  960): failed to open /acct/uid_10018/pid_6472/cgroup.procs: No such file or directory
,D/CalendarProvider2( 6684): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6684): Created com.android.providers.calendar.CalendarAlarmManager@182cc70a(com.android.providers.calendar.CalendarProvider2@3adcacb9)
I/CheckinService( 5665): Checkin interval check for package: unspecified last checkin: 1454948631071 min interval config: 0 actual interval: 26464
,I/CheckinService( 5665): Checking schedule, now: 1454948657544 next: 1454948661029
I/CheckinService( 5665): active receiver: disabled
V/DownloadManager( 3276): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3276): DownloadService onCreate
I/DownloadManager( 3276): in removeSpuriousFiles
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@1737be10 on behalf of 3276
,I/DownloadManager( 3276): in trimDatabase
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/NotificationManager( 3276): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@2f04fd09 on behalf of 3276
,I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6715 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3276): DownloadService onStartCommand
V/DownloadManager( 3276): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@1cc2ab3c on behalf of 3276
D/AlertService( 6390): No fired or scheduled alerts
I/NotificationManager( 6390): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 6390): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 6390): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6390): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6390): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  960): Killing 6506:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10069/pid_6506/cgroup.procs: No such file or directory
,V/DownloadManager( 3276): DownloadService onDestroy
D/AlarmScheduler( 6390): No events found starting within 1 week.
,I/ActivityManager(  960): Killing 6390:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10013/pid_6390/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Killing 6527:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10086/pid_6527/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2726): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:18
,D/UpdateThreadPoolManager( 2726): 2 : This is isUpdating : false
D/WeatherAncestor( 2726): connectivity changed - connection : true
D/Weather_cast( 2726): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2726): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:18
D/WeatherService( 2726): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2726): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2726): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2726): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6736 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 6361): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6361): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6361): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6361): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6361): propertyValue:false
I/Babel   ( 6361): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  960): Killing 5623:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10036/pid_5623/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  960): Explicit concurrent mark sweep GC freed 19265(1190KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 9.896ms total 162.433ms
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6736): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6736): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6736): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6736):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6736):   adb logcat -s GAv4
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6736): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6736): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6736): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6736): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6736): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6736): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6736): Time to load native libraries: 2 ms (timestamps 6245-6247)
I/LibraryLoader( 6736): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6736): Binding Chromium to main looper Looper (main, tid 1) {28a55b6c}
I/LibraryLoader( 6736): Expected native library version number "",actual native library version number ""
,I/chromium( 6736): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6736): Initializing chromium process, singleProcess=true
W/art     ( 6736): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6736): ApplicationContext is null in ApplicationStatus
,W/chromium( 6736): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6736): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6736): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6736): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6736): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6736): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6736): Remote Branch: 
I/Adreno-EGL( 6736): Local Patches: 
I/Adreno-EGL( 6736): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb551c6e0, uid 10079
,W/AudioManagerAndroid( 6736): Requires BLUETOOTH permission
I/NSApplication( 6736): Starting up...
I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6803 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  960): Killing 6553:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10081/pid_6553/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  960): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6823 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 6594:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10021/pid_6594/cgroup.procs: No such file or directory
,W/ResourcesManager( 6823): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5665): SYNC; picasa accounts
,D/NetworkLogImpl( 5665): Loaded NetworkSpeedPredictor
I/iu.Environment( 5665): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  960): Killing 6420:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/iu.UploadsManager( 5665): num queued entries: 0
,I/iu.UploadsManager( 5665): num updated entries: 0
,I/iu.SyncManager( 5665): NEXT; no task
I/jxcore-log( 5517): Test app app.js loaded
I/jxcore-log( 5517): 
,W/libprocessgroup(  960): failed to open /acct/uid_10011/pid_6420/cgroup.procs: No such file or directory
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5517): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9ff02f added. We now have 1 listener(s)
,D/BluetoothAdapterService(509102550)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@269e8edc
I/jxcore-log( 5517): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5517): 
,I/ActivityManager(  960): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6860 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.361ms
,I/chromium( 5517): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     (  313): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 24.452ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.243ms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/MusicStore( 6860): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6860): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/CheckinService( 5665): Done disabling old GoogleServicesFramework version
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6860): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6860): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6860): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12df4d07: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6860): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6860): GMSCore installation verified
I/ConfigStore( 6860): Config Database version: 1
,I/MediaRouter( 6860): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6860): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
I/NetworkMonitor( 6860): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6860): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6891 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6860): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6860): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6891): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  960): Killing 6628:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/ResourcesManager( 6891): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_6628/cgroup.procs: No such file or directory
,I/NotificationManager( 6860): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6891): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6891): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6891): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  960): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6918 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6891): JNI_OnLoad()
I/HubEmail( 6891): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6891): registerNatives()
I/HubEmail( 6891): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6891): registerNativeMethods()
I/HubEmail( 6891): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6891): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  960): Killing 6664:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10038/pid_6664/cgroup.procs: No such file or directory
,W/Settings( 6891): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6918): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6918): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6918): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6918): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6918): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6918): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6943 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6918): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6918): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6918): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6918): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6918): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  960): Killing 6684:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10014/pid_6684/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6943): onCreate
,W/AppUp4:DB( 6943):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6943):  setFingerPrint start
I/AppUp4:DB( 6943):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6943):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6943):  SDK version = 0
I/AppUp4:DB( 6943):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6943): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6943): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6943): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6943): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6943): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6943): onReceive
I/AppUp4:CustModeStarterReceiver( 6943): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6943): Context : android.app.ReceiverRestrictedContext@2b71fb7b
D/AppUp4:CustFacade( 6943): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6943): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6943): begin check event
I/AppUp4:CustModeStarterReceiver( 6943): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6943): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6943): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6943): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6943): handleAsyncCustNotification do not startCustService
I/ActivityManager(  960): Killing 6715:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10051/pid_6715/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3219): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3219): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3219): networkInfo.isConnected() = false
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6965 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6965): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6965): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6965): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  960): Killing 6361:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6965): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6965): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6965): [parse] Load xml
V/TelephonyAutoProfiling( 6965): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6965): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6965): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  960): failed to open /acct/uid_10061/pid_6361/cgroup.procs: No such file or directory
,V/DownloadManager( 3276): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3276): DownloadService onCreate
I/DownloadManager( 3276): in removeSpuriousFiles
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3276): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@eae6a1a on behalf of 3276
I/DownloadManager( 3276): in trimDatabase
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@eb3494b on behalf of 3276
I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6987 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3276): DownloadService onStartCommand
V/DownloadManager( 3276): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@3f390de6 on behalf of 3276
I/CheckinService( 5665): Checkin interval check for package: unspecified last checkin: 1454948631071 min interval config: 0 actual interval: 30995
,I/CheckinService( 5665): Checking schedule, now: 1454948662079 next: 1454948661029
I/CheckinService( 5665): active receiver: enabled
,I/CheckinService( 5665): Preparing to send checkin request
I/EventLogService( 5665): Accumulating logs since 1454948646333
,V/DownloadManager( 3276): DownloadService onDestroy
,D/WeatherAncestor( 2726): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:22
,D/UpdateThreadPoolManager( 2726): 2 : This is isUpdating : false
D/WeatherAncestor( 2726): connectivity changed - connection : true
D/Weather_cast( 2726): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2726): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:22
D/WeatherService( 2726): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7015 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2726): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2726): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2726): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinRequestBuilder( 5665): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5665): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7015): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  960): Explicit concurrent mark sweep GC freed 17212(879KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.752ms total 157.921ms
,I/Babel_SMS( 7015): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7015): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7015): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7015): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7015): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7015): MmsConfig.loadFromResources
E/Babel_SMS( 7015): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7015): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 7015): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7015): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7015): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7015): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7015): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7015): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7015): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7015): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7015): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7015): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7015): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7015): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7015): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7015): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7015): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7015): found sensor: Motion Accel, handle=46
,I/art     ( 7015): CheckpointMarkThreadRoots callback created = 0xb002d880
,I/art     ( 7015): CheckpointMarkThreadRoots callback created = 0xb002d850
,I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7046 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 7015): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7015): startup - clean
,I/Babel   ( 7015): deleted: false for 0
,W/ResourcesManager( 7046): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7046): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 7015): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7015): Unsupported mime audio/adpcm
W/AudioCapabilities( 7015): Unsupported mime audio/g726
W/AudioCapabilities( 7015): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7015): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7015): Unsupported mime video/mjpg
I/MultiDex( 7046): VM with version 2.1.0 has multidex support
I/MultiDex( 7046): install
I/MultiDex( 7046): VM has multidex support, MultiDex support library is disabled.
W/VideoCapabilities( 7015): Unsupported mime video/theora
,I/ActivityManager(  960): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7066 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7015): Unsupported mime audio/evrc
,W/AudioCapabilities( 7015): Unsupported mime audio/qcelp
W/VideoCapabilities( 7015): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7015): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7015): Unsupported mime audio/qcelp
V/JNIHelp ( 7046): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/AudioCapabilities( 7015): Unsupported mime audio/evrc
W/VideoCapabilities( 7015): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 7066): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 7066): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3adcacb9
,I/VideoCapabilities( 7015): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7015): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7015): Unrecognized profile 2130706433 for video/avc
,W/ActivityThread( 7046): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/VideoCapabilities( 7015): Unrecognized profile 2130706433 for video/avc
W/System  ( 7046): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cc2ab3c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7046): Installed default security provider GmsCore_OpenSSL
D/CalendarProvider2( 7066): [getOrCreateCalendarAlarmManager]
I/NotificationManager( 7046): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7046): com.google.android.gms: cancel(39789) by com.google.android.gms
I/CalendarProvider2( 7066): Created com.android.providers.calendar.CalendarAlarmManager@182cc70a(com.android.providers.calendar.CalendarProvider2@3adcacb9)
D/CalendarProviderBroadcastReceiver( 7066): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 7066): [IntentService] WakeLock acquire, start IntentSerivce
W/VideoCapabilities( 7015): Unrecognized profile 2130706433 for video/avc
D/CalendarProvider2( 7066): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7066): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 7066): [getOrCreateCalendarAlarmManager]
I/vclib   ( 7015): onServiceConnected
W/Babel   ( 7015): Attempted to change video mute state without an active call.
I/NotificationManager( 7015): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7015): propertyValue:false
D/CalendarProvider2( 7066): [IntentService] Release Lock
,D/CalendarProvider2( 7066): CalendarProviderIntentService.onDestroy()
I/art     ( 7046): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7046): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  960): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7092 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6341): Create singleton instance
,I/Babel   ( 7015): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  960): Killing 6860:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10081/pid_6860/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 7046): Install completed successfully. count=14 extracted=0
,I/AudioManager( 6341): getMode name:com.lge.qremote
I/ActivityManager(  960): Process com.lge.email (pid 6891) has died
,D/UEI.SmartControl( 7092): Quickset Services start...
,I/UEI.SmartControl( 7092): Manufacture = LGE
D/UEI.SmartControl( 7092): File observer start...
E/UEI.SmartControl( 7092): IR Port is disabled: false
D/UEI.SmartControl( 7092): Starting file observer...
D/UEI.SmartControl( 7092): Extracting JNI libs...
D/UEI.SmartControl( 7092): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  960): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7110 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  282): Instantiating CDM.
I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,I/MusicStore( 7110): Database version: 120
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,D/UEI.SmartControl( 7092): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7092): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7092): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=2386021384
,I/UEI.SmartControl( 7092): --- Selecting new region: 2
,I/UEI.SmartControl( 7092): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7092): Platform has CIR...
D/UEI.SmartControl( 7092): NO CIR support, need to check package...
I/UEI.SmartControl( 7092): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7092): QS Service created
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7110): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/UEI.SmartControl( 7092): QS start get config
,D/UEI.SmartControl( 7092): Loading JNI Libs...
D/UEI.SmartControl( 7092):  configuring local db...
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7110): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7110): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 7110): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7110): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 7046): CheckpointMarkThreadRoots callback created = 0xb00cceb0
,V/JNIHelp ( 7110): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 7046): CheckpointMarkThreadRoots callback created = 0xb00ccea0
W/ActivityThread( 7110): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7110): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12df4d07: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7110): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7110): GMSCore installation verified
I/ConfigStore( 7110): Config Database version: 1
D/UEI.SmartControl( 7092):  ---- Has DB8: true
D/UEI.SmartControl( 7092): QS start statue = true Error code = 0
D/UEI.SmartControl( 7092): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7092): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7092): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7092): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7092): IrrcClient ++ 
D/irrcClient( 7092): getIrrcService ++ 
,D/irrcClient( 7092): getIrrcService -- 
D/irrcClient( 7092): IrrcClient -- 
W/irrc_jni( 7092): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7092): Services init done
D/UEI.SmartControl( 7092): QS Service init finished
D/UEI.SmartControl( 7092): QS Service version name: 0.1.73
D/UEI.SmartControl( 7092): QS Service version code: 1073
,I/UEI.SmartControl( 7092): Device manager: loading config....
D/UEI.SmartControl( 7092): Service requested: Control
D/UEI.SmartControl( 7092): Config is loaded...
,D/UEI.SmartControl( 7092):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 7092): Request IControl service: devices are loaded...
I/UEI.SmartControl( 7092): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7092): Internal service binding...
,D/UEI.SmartControl( 7092): -----IControl: 11
D/UEI.SmartControl( 7092): Caller: com.lge.qremote
D/UEI.SmartControl( 7092): ------------ IControl registerCallback...
I/UEI.SmartControl( 7092): Registering callback...
I/MediaRouter( 7110): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/UEI.SmartControl( 7092): -----IControl: 19
D/UEI.SmartControl( 7092): Caller: com.lge.qremote
I/UEI.SmartControl( 7092): Registering Services Ready callback...
I/UEI.SmartControl( 7092): Notify client services are ready...
D/UEI.SmartControl( 7092): -----IControl: 8
V/MusicLeanback( 7110): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/UEI.SmartControl( 7092): Caller: com.lge.qremote
I/ActivityManager(  960): Killing 6918:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/NetworkMonitor( 7110): type=WIFI subType= reason=null isConnected=true
,I/dex2oat ( 7140): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_6918/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Killing 6943:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10011/pid_6943/cgroup.procs: No such file or directory
,I/dex2oat ( 7140): dex2oat took 135.269ms (threads: 4)
I/NetworkMonitor( 7110): type=WIFI subType= reason=null isConnected=true
I/Adreno-EGL( 7046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7046): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7046): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7046): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7046): Remote Branch: 
I/Adreno-EGL( 7046): Local Patches: 
I/Adreno-EGL( 7046): Reconstruct Branch: 
,I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7148 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 24.331ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.361ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.348ms
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{2e456eaf type 0 when 1454948661029 com.google.android.gms} when 1454948661029
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  960): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7166 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{25a3a2bc type 0 when 1454948664649 com.android.vending} when 1454948664649
I/GHttpClientFactory( 7110): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7110): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7148): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7148): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  960): Killing 6965:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10038/pid_6965/cgroup.procs: No such file or directory
,I/LGEmail ( 7148): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7148): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/NotificationManager( 7110): com.google.android.music: cancel(1061) by com.google.android.music
,I/Adreno-EGL( 7046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7046): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7046): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7046): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7046): Remote Branch: 
I/Adreno-EGL( 7046): Local Patches: 
I/Adreno-EGL( 7046): Reconstruct Branch: 
D/Finsky  ( 7166): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Adreno-EGL( 7046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7046): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7046): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7046): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7046): Remote Branch: 
I/Adreno-EGL( 7046): Local Patches: 
I/Adreno-EGL( 7046): Reconstruct Branch: 
,D/eas_req ( 7148): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager(  960): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7197 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7148): JNI_OnLoad()
I/HubEmail( 7148): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7148): registerNatives()
I/HubEmail( 7148): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7148): registerNativeMethods()
I/HubEmail( 7148): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7148): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7148): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  960): Process com.google.android.apps.magazines (pid 6736) has died
,D/LGDMClient( 7197): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7197): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 7197): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7197): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7234 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 7197): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7197): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/Finsky  ( 7166): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/ContextImpl( 7197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7197): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,W/Settings( 7166): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/LGDMClient( 7197): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7197): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7197): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
W/Settings( 7166): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/LGDMClient( 7197): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/NotificationManager( 7166): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@2c2b25d4 on behalf of 7166
I/art     ( 4012): Explicit concurrent mark sweep GC freed 2568(99KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 373us total 44.410ms
,I/AppUp4:AppBoxCP( 7234): onCreate
W/AppUp4:DB( 7234):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7234):  setFingerPrint start
I/AppUp4:DB( 7234):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,D/Ads     ( 7166): Skipping gmscore version check
D/Finsky  ( 7166): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/AppUp4:DB( 7234):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7234):  SDK version = 0
I/AppUp4:DB( 7234):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7234): AppBoxApplication onCreate()
I/ActivityManager(  960): Killing 6987:com.lge.drmservice/u0a51 (adj 15): empty #11
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] request level :IDLE....
I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
W/libprocessgroup(  960): failed to open /acct/uid_10051/pid_6987/cgroup.procs: No such file or directory
I/AppUp4:CustModeStarterReceiver( 7234): onReceive
,I/AppUp4:CustModeStarterReceiver( 7234): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/WVCdm   (  282): PrepareKeyRequest: nonce=4232741496
D/AppUp4:CustFacade( 7234): Context : android.app.ReceiverRestrictedContext@2b71fb7b
D/AppUp4:CustFacade( 7234): isCustomizationCompleted : false
D/Finsky  ( 7166): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7166): [1] Libraries$2.run: Finished loading 1 libraries.
D/AppUp4:CustFacade( 7234): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7234): begin check event
I/AppUp4:CustModeStarterReceiver( 7234): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7234): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7234): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7234): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7234): handleAsyncCustNotification do not startCustService
,D/Finsky  ( 7166): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  960): Killing 7015:com.google.android.talk/u0a61 (adj 15): empty #11
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
I/LgeMiscReceiver( 3219): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3219): action = android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  960): failed to open /acct/uid_10061/pid_7015/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3219): networkInfo.isConnected() = true
D/PhoneState( 3219): setPdpRejectCasuse : false
,I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7268 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 7166): [905] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7166): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  960): Killing 6803:com.android.chrome/u0a48 (adj 15): empty #11
D/PhoneMonitor( 7268): Register our PhoneStateListener
,W/libprocessgroup(  960): failed to open /acct/uid_10048/pid_6803/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7268): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7268): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  960): Killing 6823:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/PhoneMonitor( 7268): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7268): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7268): [parse] Load xml
V/TelephonyAutoProfiling( 7268): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7268): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7268): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  960): failed to open /acct/uid_10086/pid_6823/cgroup.procs: No such file or directory
,V/DownloadManager( 3276): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3276): DownloadService onCreate
I/NotificationManager( 3276): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3276): in removeSpuriousFiles
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@3e782272 on behalf of 3276
I/DownloadManager( 3276): in trimDatabase
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@9d196c3 on behalf of 3276
,I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7293 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3276): DownloadService onStartCommand
V/DownloadManager( 3276): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5665): Checkin interval check for package: unspecified last checkin: 1454948631071 min interval config: 0 actual interval: 35463
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@1cea3a79 on behalf of 3276
,V/DownloadManager( 3276): DownloadService onDestroy
,I/ActivityManager(  960): Killing 7066:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10014/pid_7066/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2726): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:26
D/UpdateThreadPoolManager( 2726): 2 : This is isUpdating : false
D/WeatherAncestor( 2726): connectivity changed - connection : true
D/Weather_cast( 2726): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2726): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:26
D/WeatherService( 2726): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7310 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2726): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2726): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2726): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  960): Explicit concurrent mark sweep GC freed 24666(1110KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.135ms total 139.426ms
,W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7310): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7310): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7310): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7310): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7310): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7310): MmsConfig.loadFromResources
E/Babel_SMS( 7310): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7310): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7310): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7310): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7310): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7310): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7310): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7310): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7310): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7310): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7310): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7310): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7310): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7310): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7310): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7310): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7310): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7310): found sensor: Motion Accel, handle=46
,W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7310): startup - clean
,I/Babel   ( 7310): deleted: false for 0
,I/art     ( 7310): CheckpointMarkThreadRoots callback created = 0xb002d570
,I/art     ( 7310): CheckpointMarkThreadRoots callback created = 0xb002d550
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7342 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7310): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7310): Unsupported mime audio/adpcm
W/AudioCapabilities( 7310): Unsupported mime audio/g726
W/AudioCapabilities( 7310): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7310): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7310): Unsupported mime video/mjpg
W/VideoCapabilities( 7310): Unsupported mime video/theora
,W/AudioCapabilities( 7310): Unsupported mime audio/evrc
,W/AudioCapabilities( 7310): Unsupported mime audio/qcelp
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7310): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7310): Unsupported mime audio/qcelp
W/AudioCapabilities( 7310): Unsupported mime audio/evrc
,W/VideoCapabilities( 7310): Unsupported mime video/mp4v-esdp
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 114639130534; DSPS: 3854531; Offset : -3001506849
,I/VideoCapabilities( 7310): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7310): onServiceConnected
,W/Babel   ( 7310): Attempted to change video mute state without an active call.
D/libc-netbsd( 7310): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7310): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7310): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7310): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7310): propertyValue:false
,I/NotificationManager( 7310): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Babel   ( 7310): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  960): Killing 6341:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10106/pid_6341/cgroup.procs: No such file or directory
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7342): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7342): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7342): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7342): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7342): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7342):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7342):   adb logcat -s GAv4
,W/GAv4    ( 7342): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7342): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7342): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  282): CdmEngine::CloseSession
I/WVCdm   (  282): L3 Terminate.
,I/CheckinRequestBuilder( 5665): Classify the device as Phone.
,D/libc-netbsd( 5665): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5665): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5665): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5665): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5665): propertyValue:false
I/WebViewFactory( 7342): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7342): Time to load native libraries: 2 ms (timestamps 5315-5317)
I/LibraryLoader( 7342): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7342): Binding Chromium to main looper Looper (main, tid 1) {28a55b6c}
I/LibraryLoader( 7342): Expected native library version number "",actual native library version number ""
,I/chromium( 7342): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/libc-netbsd( 5665): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5665): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/BrowserStartupController( 7342): Initializing chromium process, singleProcess=true
W/art     ( 7342): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7342): ApplicationContext is null in ApplicationStatus
W/chromium( 7342): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7342): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7342): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7342): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7342): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7342): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7342): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7342): Remote Branch: 
I/Adreno-EGL( 7342): Local Patches: 
I/Adreno-EGL( 7342): Reconstruct Branch: 
,D/libc-netbsd( 5665): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5665): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5665): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5665): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5665): Sending checkin request (9887 bytes)
,V/AudioPolicyService(  282): registerClient() client 0xb551c660, uid 10079
,W/AudioManagerAndroid( 7342): Requires BLUETOOTH permission
I/NSApplication( 7342): Starting up...
I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7412 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 7092:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10089/pid_7092/cgroup.procs: No such file or directory
,I/MusicWidget( 2650): mDelayedStopHandler : unbind
,I/MusicBrowser( 2745): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2745): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2745): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2745): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2745): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2745): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2745): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2745): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/CheckinRequestBuilder( 5665): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5665): Failed to find provider info for com.google.android.wearable.settings
I/MediaFocusControl(  960):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@25fc8161com.lge.music.MediaPlaybackService$6@df4d486
,D/MusicBrowser( 2745): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@39ad457
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2745): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2745): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2745): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2745): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2745): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2745): reset
V/MediaPlayer[Native]( 2745): setListener
,V/MediaPlayer[Native]( 2745): disconnect
V/MediaPlayer[Native]( 2745): destructor
V/AudioFlinger(  282): releasing 19 from 2745 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2745): disconnect
D/MusicBrowser( 2745): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2745): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2745): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2745): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2745): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2745): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2745): [SmartShareManagerClient] unregisterListener: 799244615
W/SmartShareClient( 2745): [SmartShareManagerClient] unregisterListener invalid listener: 799244615
I/SmartShareClient( 2745): [SmartShareManagerClient] terminate service: 2745/MediaPlaybackService/51534709
E/HomeCloudIF( 2745): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2745): [SmartShareManagerClient] unbindService context:android.app.Application@1debdd74
,V/CloudHub( 2745): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2745): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2745): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2745): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2745): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2745): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
,I/ActivityManager(  960): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7445 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  960): Killing 7110:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10081/pid_7110/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Killing 7148:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10021/pid_7148/cgroup.procs: No such file or directory
,W/ResourcesManager( 7445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5665): Classify the device as Phone.
,I/CheckinTask( 5665): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5665): Checking schedule, now: 1454948669009 next: 1455475918003
I/CheckinService( 5665): active receiver: disabled
,I/CheckinService( 5665): Checking schedule, now: 1454948669052 next: 1455475918003
I/CheckinService( 5665): active receiver: disabled
,D/CheckinService( 5665): Recording last checkin time for package unspecified as 1454948669062
I/ActivityManager(  960): Killing 7166:com.android.vending/u0a36 (adj 15): empty #11
,I/ActivityManager(  960): Killing 7197:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  960): failed to open /acct/uid_10036/pid_7166/cgroup.procs: No such file or directory
,W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_7197/cgroup.procs: No such file or directory
I/ActivityManager(  960): Killing 7234:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10011/pid_7234/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7479 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7479): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ede700c:true
,D/BluetoothAdapterService(509102550)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@269e8edc
D/BluetoothAdapterService(509102550)( 1992): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@269e8edc
I/AudioManager( 7479): getMode name:com.lge.qremote
,I/AudioManager( 7479): getMode name:com.lge.qremote
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  960): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7497 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.777ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.713ms
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.630ms
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7497): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7497): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7497): Error finding the version of the Email provider.....
E/Gmail   ( 7497): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7497): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7497): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7497): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7497): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7497): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7497): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7497): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7497): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7497): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,E/MDM     ( 1735): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5665): Restart initialization of location
I/ActivityManager(  960): Killing 7293:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/libprocessgroup(  960): failed to open /acct/uid_10051/pid_7293/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  960): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/ActivityManager(  960): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7539 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7479): Create singleton instance
,I/art     (  960): Explicit concurrent mark sweep GC freed 20197(981KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.416ms total 167.670ms
,W/ActivityManager(  960): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7497): Observing account changes for notifications
,I/AudioManager( 7479): getMode name:com.lge.qremote
I/ActivityManager(  960): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7563 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7539): Quickset Services start...
,I/UEI.SmartControl( 7539): Manufacture = LGE
D/UEI.SmartControl( 7539): File observer start...
E/UEI.SmartControl( 7539): IR Port is disabled: false
D/UEI.SmartControl( 7539): Starting file observer...
D/UEI.SmartControl( 7539): Extracting JNI libs...
D/UEI.SmartControl( 7539): --- this system supports 32-bit or 64-bit only
I/Gmail   ( 7497): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7497): notifyAccountChanged
D/UEI.SmartControl( 7539): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7539): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7539): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/UEI.SmartControl( 7539): --- Selecting new region: 2
I/UEI.SmartControl( 7539): -- Running on KitKat(19) and above! JNI will be used.
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/UEI.SmartControl( 7539): Platform has CIR...
D/UEI.SmartControl( 7539): NO CIR support, need to check package...
I/UEI.SmartControl( 7539): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7539): QS Service created
,D/Finsky  ( 7563): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/UEI.SmartControl( 7539): QS start get config
D/UEI.SmartControl( 7539): Loading JNI Libs...
,D/UEI.SmartControl( 7539):  configuring local db...
I/Gmail   ( 7497): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7563): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7563): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7563): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7563): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@9acdc1f on behalf of 7563
D/Finsky  ( 7563): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7563): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7563): Skipping gmscore version check
D/Finsky  ( 7563): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/MDM     ( 1735): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UEI.SmartControl( 7539):  ---- Has DB8: true
,D/Finsky  ( 7563): [969] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5665): Restart initialization of location
D/Finsky  ( 7563): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/UEI.SmartControl( 7539): QS start statue = true Error code = 0
D/UEI.SmartControl( 7539): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7539): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7539): IRRCDataComm has AudioManager!!!!.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 7479): getMode name:com.lge.qremote
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/irrc_jni( 7539): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7539): IrrcClient ++ 
D/irrcClient( 7539): getIrrcService ++ 
,D/irrcClient( 7539): getIrrcService -- 
D/irrcClient( 7539): IrrcClient -- 
W/irrc_jni( 7539): IRRCPlayer_nativeInit -- 
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
D/UEI.SmartControl( 7539): Services init done
D/UEI.SmartControl( 7539): QS Service init finished
,D/UEI.SmartControl( 7539): QS Service version name: 0.1.73
D/UEI.SmartControl( 7539): QS Service version code: 1073
I/UEI.SmartControl( 7539): Device manager: loading config....
D/UEI.SmartControl( 7539): Service requested: Control
I/NotificationManager(  960): android: cancelAsUser(2) by android
D/UEI.SmartControl( 7539): Config is loaded...
,I/CheckinService( 5665): Checkin interval check for package: unspecified last checkin: 1454948669062 min interval config: 0 actual interval: 1976
I/CheckinService( 5665): Checking schedule, now: 1454948671058 next: 1455475918003
I/CheckinService( 5665): active receiver: disabled
,D/UEI.SmartControl( 7539):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7539): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7539): Request IControl service: devices are loaded...
W/ContextImpl( 3643): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/UEI.SmartControl( 7539): Internal service binding...
D/UEI.SmartControl( 7539): -----IControl: 11
D/UEI.SmartControl( 7539): Caller: com.lge.qremote
,D/UEI.SmartControl( 7539): ------------ IControl registerCallback...
I/UEI.SmartControl( 7539): Registering callback...
D/UEI.SmartControl( 7539): -----IControl: 19
D/UEI.SmartControl( 7539): Caller: com.lge.qremote
I/UEI.SmartControl( 7539): Registering Services Ready callback...
I/UEI.SmartControl( 7539): Notify client services are ready...
D/UEI.SmartControl( 7539): -----IControl: 8
V/SetupWizard( 7268): Connected to Gservices successfully
D/UEI.SmartControl( 7539): Caller: com.lge.qremote
I/AudioManager( 7479): getMode name:com.lge.qremote
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 7563): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7563): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7563): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7563): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 7563): propertyValue:false
I/ActivityManager(  960): Process com.google.android.apps.magazines (pid 7342) has died
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 7479): getMode name:com.lge.qremote
I/AudioManager( 7479): getMode name:com.lge.qremote
I/AudioManager( 7479): getMode name:com.lge.qremote
,I/AudioManager( 7479): getMode name:com.lge.qremote
I/AudioManager( 7479): getMode name:com.lge.qremote
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  960): Handling package changes for user 0
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7662 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     ( 1788): Background sticky concurrent mark sweep GC freed 90163(5MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 9MB/14MB, paused 4.529ms total 102.942ms
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationManager( 7310): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7310): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7662): onCreate
W/AppUp4:DB( 7662):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7662):  setFingerPrint start
I/AppUp4:DB( 7662):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7662):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7662):  SDK version = 0
I/AppUp4:DB( 7662):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7662): AppBoxApplication onCreate()
V/JNIHelp ( 7310): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:CustModeStarterReceiver( 7662): onReceive
I/AppUp4:CustModeStarterReceiver( 7662): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7662): Context : android.app.ReceiverRestrictedContext@2a3722ac
D/AppUp4:CustFacade( 7662): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7662): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7662): begin check event
I/AppUp4:CustModeStarterReceiver( 7662): Event For Nothing, skip.
W/System  ( 7310): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7310): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  960): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  960): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7692 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
I/BackupManagerService(  960): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/BackupManagerService(  960): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  960): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@f923d89
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager(  960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  960): Process com.android.vending (pid 7563) has died
,I/AppConfig( 7692): Total System Memory = 906309632
,W/ResourceType(  960): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/GalleryUtils( 7692): Application Heap = 96 MB
I/AppConfig( 7692): App Tier : NOT_DEF
D/SystemHelper( 7692): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7715 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/LocationProviderProxy(  960): applying state to connected service
,I/ActivityManager(  960): Killing 7412:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10048/pid_7412/cgroup.procs: No such file or directory
W/ResourcesManager( 7715): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7715): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7715): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7715): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7715): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7715): BUILD Country: EU
I/SystemConfig( 7715): BUILD Operator: OPEN
,I/ActivityManager(  960): Process com.google.android.gm (pid 7497) has died
,I/ActivityManager(  960): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7734 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7715): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7715): existFile = false
I/SystemConfig( 7715): canReadFile = false
I/SystemConfig( 7715): systemFeature RCS result false
D/SystemConfig( 7715): refreshRcsSupport() :false
,I/LockScreenSettings( 7734): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7734): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7734): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  960): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7755 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
I/art     ( 7445): CheckpointMarkThreadRoots callback created = 0xb002d620
I/ActivityManager(  960): Killing 2745:com.lge.music/u0a28 (adj 15): empty #11
,I/art     ( 7445): CheckpointMarkThreadRoots callback created = 0xb002d5f0
V/AudioFlinger(  282): 2745 died, releasing its sessions
V/AudioFlinger(  282):  pid 1753 @ 0
V/AudioFlinger(  282):  pid 3219 @ 1
V/AudioFlinger(  282):  pid 3219 @ 2
,W/libprocessgroup(  960): failed to open /acct/uid_10028/pid_2745/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  960): Explicit concurrent mark sweep GC freed 27228(1341KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.825ms total 152.835ms
,D/Finsky  ( 7755): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7755): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7755): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7755): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7755): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3276): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3276): created cursor android.database.sqlite.SQLiteCursor@28a55b6c on behalf of 7755
D/Finsky  ( 7755): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7755): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7755): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7755): Skipping gmscore version check
,D/PackageBroadcastService( 5665): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5665): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5665): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7755): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  960): Killing 7268:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10038/pid_7268/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 5665): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5665): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  960): Killing 7662:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10011/pid_7662/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7539): Internal timer expired: 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  960): Killing 7310:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10061/pid_7310/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/charger_monitor(  472): init target 500000
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/charger_monitor(  472): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 134639906672; DSPS: 4509917; Offset : -3001524168
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
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
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{3d12ef38 type 2 when 147093 com.google.android.gms} when 147093
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=54729489, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,D/WeatherService( 2726): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:25:0
,D/WeatherService( 2726): 2 : TimeTick Intent And Screen On
D/WeatherService( 2726): 2 : SDK version : 21
W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2726): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2726): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2726): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2726): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2726): 2 : This is isUpdating : false
D/WeatherService( 2726): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2726): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2726): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2726): 2 : Fixed theme : optimus
D/WeatherReflect( 2726): 2 : Map key string is -2
,D/lim     ( 2726): 2 : time = 17:25
,I/WeatherReflect( 2726): Model Name : LG-D722
D/WeatherTheme( 2726): 2 : Different view - status_min_formatted : 24 != 25
D/WeatherTheme( 2726): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2726): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2726): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2726): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2726): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2726): forecast size is 0
,D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2726): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2726): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2726): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2726): url is : null
D/Theme   ( 2726): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2726): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2726): 2 : update view, appWidgetId: 2
D/WeatherService( 2726): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:25:0
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=54729489 [*alarm*], flags=0x0
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1735): Vacuum at: now=1454948700252 tag=VacuumService
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 6448 seconds from now (1454948700746)
D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28618 ms ago)
,D/qdlights(  960): set_light_backlight: 252
,D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/qdlights(  960): set_light_backlight: 249
,D/qdlights(  960): set_light_backlight: 245
,D/qdlights(  960): set_light_backlight: 242
,D/qdlights(  960): set_light_backlight: 239
,D/qdlights(  960): set_light_backlight: 235
,D/qdlights(  960): set_light_backlight: 232
,D/qdlights(  960): set_light_backlight: 229
,D/qdlights(  960): set_light_backlight: 225
,D/qdlights(  960): set_light_backlight: 222
,D/qdlights(  960): set_light_backlight: 219
,D/qdlights(  960): set_light_backlight: 215
,D/qdlights(  960): set_light_backlight: 212
,D/qdlights(  960): set_light_backlight: 209
,D/qdlights(  960): set_light_backlight: 205
,D/qdlights(  960): set_light_backlight: 202
,D/qdlights(  960): set_light_backlight: 199
,D/qdlights(  960): set_light_backlight: 195
,D/qdlights(  960): set_light_backlight: 192
,D/qdlights(  960): set_light_backlight: 189
,D/qdlights(  960): set_light_backlight: 185
,D/qdlights(  960): set_light_backlight: 182
,D/qdlights(  960): set_light_backlight: 179
,D/qdlights(  960): set_light_backlight: 175
,D/qdlights(  960): set_light_backlight: 172
,D/qdlights(  960): set_light_backlight: 169
,D/qdlights(  960): set_light_backlight: 165
,D/qdlights(  960): set_light_backlight: 162
,D/qdlights(  960): set_light_backlight: 159
,D/qdlights(  960): set_light_backlight: 155
,D/qdlights(  960): set_light_backlight: 152
,D/qdlights(  960): set_light_backlight: 149
,D/qdlights(  960): set_light_backlight: 145
,D/qdlights(  960): set_light_backlight: 142
,D/qdlights(  960): set_light_backlight: 139
,D/qdlights(  960): set_light_backlight: 135
,D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/qdlights(  960): set_light_backlight: 132
,D/qdlights(  960): set_light_backlight: 129
,D/qdlights(  960): set_light_backlight: 125
,D/qdlights(  960): set_light_backlight: 122
,D/qdlights(  960): set_light_backlight: 119
,D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  960): set_light_backlight: 115
D/qdlights(  960): set_light_backlight: 112
,D/qdlights(  960): set_light_backlight: 109
,D/qdlights(  960): set_light_backlight: 105
,D/qdlights(  960): set_light_backlight: 102
,D/qdlights(  960): set_light_backlight: 99
,D/qdlights(  960): set_light_backlight: 95
,D/qdlights(  960): set_light_backlight: 92
,D/qdlights(  960): set_light_backlight: 89
,D/qdlights(  960): set_light_backlight: 85
,D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  960): set_light_backlight: 82
D/qdlights(  960): set_light_backlight: 79
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/qdlights(  960): set_light_backlight: 75
,D/qdlights(  960): set_light_backlight: 72
,D/qdlights(  960): set_light_backlight: 69
,D/qdlights(  960): set_light_backlight: 65
,D/qdlights(  960): set_light_backlight: 62
,D/qdlights(  960): set_light_backlight: 59
,D/qdlights(  960): set_light_backlight: 55
,D/qdlights(  960): set_light_backlight: 52
,D/qdlights(  960): set_light_backlight: 49
,D/qdlights(  960): set_light_backlight: 45
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 106249(5MB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 16MB/27MB, paused 2.350ms total 166.129ms
,D/qdlights(  960): set_light_backlight: 42
D/qdlights(  960): set_light_backlight: 39
,D/qdlights(  960): set_light_backlight: 35
,D/qdlights(  960): set_light_backlight: 32
,D/qdlights(  960): set_light_backlight: 29
,D/qdlights(  960): set_light_backlight: 25
D/qdlights(  960): set_light_backlight: 22
,D/qdlights(  960): set_light_backlight: 19
,D/qdlights(  960): set_light_backlight: 15
,D/qdlights(  960): set_light_backlight: 12
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
D/qdlights(  960): set_light_backlight: 10
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  960): android: cancelAsUser(2) by android
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 154640753852; DSPS: 5165305; Offset : -3001531974
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35612 ms ago)
I/PowerManagerService(  960): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35631 ms ago)
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  960): Sleeping (uid 1000)...
,D/LPWGController(  960): [updateScreenState] screen on = false
D/LPWGController(  960): disable proximity sensor
D/LPWGController(  960): enable proximity sensor
,I/SensorManager(  960): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3c4e68b9] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  960): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  960): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  960): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  960): activate: handle is 48, enable
,V/sensors_hal_Ctx(  960): activate sensors is 1400000000000
D/sensors_hal_Thresh(  960): enable: handle=48
I/sensors_hal_SAM(  960): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  960): waitForResponse: timeout=1000
V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  960): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  960): enable: Received response: 0
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35691 ms ago)
I/Adreno-EGL(  960): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  960): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  960): Build Date: 03/02/15 Mon
I/Adreno-EGL(  960): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  960): Remote Branch: 
I/Adreno-EGL(  960): Local Patches: 
I/Adreno-EGL(  960): Reconstruct Branch: 
,D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (994 us)
,I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  960): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  960): processInd: handle 48, count=1
V/sensors_hal_Thresh(  960): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  960): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  960): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  960): poll: count: 256
I/sensors_hal_Ctx(  960): poll: released wakelock sensor_ind
D/sensors_hal_Util(  960): waitForResponse: timeout=0
D/LPWGController(  960): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  960): current mode = 1  value = 1 1
I/LPWGController(  960): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  960): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  960): set_light_backlight: 0
,I/SensorManager(  960): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  960): activate: handle is 46, disable
V/sensors_hal_Ctx(  960): activate sensors is 1000000000000
,D/sensors_hal_LP2(  960): enable: handle=46
D/sensors_hal_LP2(  960): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  960): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
I/DisplayManagerService(  960): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  960): Display changed displayId=0
,V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  960): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  960): Excessive delay in setPowerMode(): 249ms
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  960): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/WifiServerServiceExt(  960): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  960): set CMD_KT_SCAN_INTERVAL
,D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1805): stopPatternFlashing()
D/Cliptray Service( 1805): lockStatus = 0
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1805): RESTART MSG
D/SplitWindow(  960): check instance of lgWin Window{1b10eac u0 SearchPanel}
,D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1788): isRequireNfcCRouting() return true
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
D/NfcService( 1788): Discovery configuration equal, not updating.
D/InputDispatcher(  960): Window went away: Window{2531d3a4 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  960): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2726): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:25:9
D/WeatherService( 2726): 2 : ACTION screen on
D/WeatherService( 2726): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2726): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2726): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:25:9
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
D/AppCleanupService( 4129): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/WifiController(  960): CMD_SCREEN_OFF 
D/WifiController(  960): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1841): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2726): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:25:9
D/WeatherService( 2726): 2 : ACTION screen off
,D/WeatherService( 2726): 2 : TimeTick Receiver Unregister
D/WeatherService( 2726): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:25:9
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
D/AppCleanupService( 4129): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4129): AppUsageStatsSaveTask
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1788): getDefaultRoute
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
,D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/Sensors (  429): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{2fe3d775 type 2 when 161599 com.android.systemui} when 161599
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1753): getCallState : 0
D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 174641490876; DSPS: 5820689; Offset : -3001527347
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{2926930a type 2 when 183284 android} when 183284
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{9f5d77b type 2 when 187049 com.google.android.gms} when 187049
,D/charger_monitor(  472): init target 500000
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 194642163993; DSPS: 6476071; Offset : -3001524991
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 214642955183; DSPS: 7131457; Offset : -3001529394
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 234643709395; DSPS: 7786841; Offset : -3001505834
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  472): init target 500000
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1992): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 254644463137; DSPS: 8442226; Offset : -3001514744
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 274645190577; DSPS: 9097610; Offset : -3001520377
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 294645947913; DSPS: 9752995; Offset : -3001525668
,I/jxcore-log( 5517): --= Surplus to requirements =--
I/jxcore-log( 5517): 
I/jxcore-log( 5517): ****TEST TOOK:  ms ****
I/jxcore-log( 5517): 
I/jxcore-log( 5517): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5517): 
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/AndroidRuntime( 7969): 
D/AndroidRuntime( 7969): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7969): CheckJNI is OFF
,D/AndroidRuntime( 7969): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  960): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  960): Killing 5517:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  960): WIN DEATH: Window{35e26189 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  960): Skipping PackageSetting{15de6b8c com.example.hello/10317} due to missing metadata
D/InputDispatcher(  960): Focus left window: Window{35e26189 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  960): Window went away: Window{35e26189 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  960):   Force finishing activity ActivityRecord{11425418 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  960): Display changed displayId=0
,D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  960): Spurious death for ProcessRecord{9766998 5517:com.test.thalitest/u0a316}, curProc for 5517: null
,I/ActivityManager(  960): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/art     ( 1942): Explicit concurrent mark sweep GC freed 22507(1337KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/21MB, paused 1.723ms total 95.503ms
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
W/System.err( 3643): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3643): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3643): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3643): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3643): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3643): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3643): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3643): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3643): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3643): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3643): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3643): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7995 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
,I/art     ( 5665): Explicit concurrent mark sweep GC freed 4464(232KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/18MB, paused 1.082ms total 173.367ms
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
,D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
,I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e88488e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e88488e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  960): Focus entered window: Window{25a3c3a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
,D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/art     (  960): Explicit concurrent mark sweep GC freed 55040(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 21.187ms total 298.992ms
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     (  960): WaitForGcToComplete blocked for 125.640ms for cause Explicit
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourcesManager( 7995): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7995): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7995): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
,D/KeyguardModel( 1374): handleShortcutListChanged...
D/administrator(  960): Handling package changes for user 0
,I/LGEmail ( 7995): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/InputMethodManagerService(  960): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 5517 uid 10316
D/LGEmail ( 7995): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  960): Timeline: Activity_windows_visible id: ActivityRecord{3fd7dcd0 u0 com.lge.launcher2/.Launcher t221} time:299819
,W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     (  960): Explicit concurrent mark sweep GC freed 8321(486KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.007ms total 314.159ms
E/b       ( 1622): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService(  960): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  960): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  960): removeObsoleteFile: deleting file=222_task.xml
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,D/AndroidRuntime( 7969): Shutting down VM
I/PackageChangeReceiver( 7995): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8026 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  960): Killing 7692:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ResourcesManager(  960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  960): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/libprocessgroup(  960): failed to open /acct/uid_10023/pid_7692/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 8026): onCreate
W/AppUp4:DB( 8026):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 8026):  setFingerPrint start
I/AppUp4:DB( 8026):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8026):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8026):  SDK version = 0
,I/AppUp4:DB( 8026):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8026): AppBoxApplication onCreate()
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AppUp4:PreloadHelper( 8026): added Exclude : com.test.thalitest
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  960): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8048 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 7046:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10006/pid_7046/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@32977188 time:300449

```
