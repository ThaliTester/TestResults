#### Test 586024278176cca_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/SystemConfig( 5376): BUILD Country: EU
I/SystemConfig( 5376): BUILD Operator: OPEN
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
--------- beginning of system
I/ActivityManager(  846): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5417 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 4928:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_4928/cgroup.procs: No such file or directory
W/ActivityManager(  846): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
I/SystemConfig( 5376): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5376): existFile = false
I/SystemConfig( 5376): canReadFile = false
I/SystemConfig( 5376): systemFeature RCS result false
D/SystemConfig( 5376): refreshRcsSupport() :false
I/LockScreenSettings( 5417): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5417): New app installed broadcast received ..
I/LockScreenSettings( 5417): Number of installed packages  1
I/ActivityManager(  846): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5434 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  846): Killing 4225:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_4225/cgroup.procs: No such file or directory
D/EulaProviderUpdateObserver( 5434): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5434): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5201): android.intent.action.PACKAGE_ADDED : com.test.thalitest
D/AndroidRuntime( 5413): 
D/AndroidRuntime( 5413): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5413): CheckJNI is OFF
I/ActivityManager(  846): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5451 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 5100:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10010/pid_5100/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AndroidRuntime( 5413): Calling main entry com.android.commands.am.Am
I/ActivityManager(  846): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{80431c8 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{80431c8 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  846): AppWindowTokenEx init.. 
D/ContextHelper(  846): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1882): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  846): Focus left window: Window{3a5b15a5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5413): Shutting down VM
D/SplitWindow(  846): check instance of lgWin Window{1afe8012 u0 Starting com.test.thalitest}
I/ActivityManager(  846): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5484 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1882): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1882): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1940): Closing mic
I/WindowStateAnimator(  846): Starting window displayed
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@141dc961
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9aa75f7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1373): draw background and invalidate : color = a000000
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
D/BarTransitions( 1373): draw background and invalidate : color = e0d0d0d
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3c30000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,V/audio_hw_primary(  278): stop_input_stream: exit: status(0)
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3c30000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1755): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioFlinger(  278): releasing 16 from 1940 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): purging stale effects
V/AudioSystem( 2704): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb3c30000 exiting
V/AudioSystem( 2018): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioSystem(  846): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3157): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1940, calling pid 278
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
D/ContextHelper( 5484): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5484): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5484): Time to load native libraries: 2 ms (timestamps 95-97)
I/LibraryLoader( 5484): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5484): Binding Chromium to main looper Looper (main, tid 1) {355bd7e2}
V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{160b9cf8 type 2 when 80138 android} when 80138
I/LibraryLoader( 5484): Expected native library version number "",actual native library version number ""
I/chromium( 5484): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5484): Initializing chromium process, singleProcess=true
W/art     ( 5484): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5484): ApplicationContext is null in ApplicationStatus
W/chromium( 5484): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5484): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5484): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5484): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5484): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5484): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5484): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5484): Remote Branch: 
I/Adreno-EGL( 5484): Local Patches: 
I/Adreno-EGL( 5484): Reconstruct Branch: 
I/GAv4    ( 5451): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5451):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5451):   adb logcat -s GAv4
W/GAv4    ( 5451): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5451): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
V/AudioPolicyService(  278): registerClient() client 0xb3c2eb40, uid 10316
D/BluetoothManagerService(  846): Message: 20
D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c711310:true
W/GAv4    ( 5451): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5451): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
I/ActivityManager(  846): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5541 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/AlertService( 3769): Beginning updateAlertNotification
,W/art     ( 5451): Suspending all threads took: 8.668ms
D/AlertService( 3769): No fired or scheduled alerts
,I/NotificationManager( 3769): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 3769): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 3769): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(16) by com.android.calendar
I/GservicesProvider( 5541): Gservices pushing to system: true; secure/global: true
I/NotificationManager( 3769): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3769): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 3769): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3769): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3769): No events found starting within 1 week.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/art     ( 5484): Attempt to remove local handle scope entry from IRT, ignoring
W/ContextImpl( 5451): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/AwContents( 5484): onDetachedFromWindow called when already detached. Ignoring
,I/GoogleHttpClient( 5541): GMS http client unavailable, use old client
D/SystemWebViewEngine( 5484): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5569 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 5221:com.google.android.music:main/u0a81 (adj 15): empty #11
I/art     ( 5451): CheckpointMarkThreadRoots callback created = 0xaaf2d2c0
,W/ResourcesManager( 5451): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5451): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 5451): CheckpointMarkThreadRoots callback created = 0xaaf2d290
W/libprocessgroup(  846): failed to open /acct/uid_10081/pid_5221/cgroup.procs: No such file or directory
,W/art     ( 5484): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5484): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5541): GMS http client unavailable, use old client
,I/NotificationManager( 5451): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Activity( 5484): Activity.onPostResume() called 
,D/OpenGLRenderer( 5484): Render dirty regions requested: true
I/OpenGLRenderer( 5484): Initialized EGL, version 1.4
V/JNIHelp ( 5451): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/OpenGLRenderer( 5484): Enabling debug mode 0
D/Atlas   ( 5484): Validating map...
,D/SplitWindow(  846): check instance of lgWin Window{b547996 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5484): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  846): Killing 5269:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/System  ( 5451): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5451): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  846): failed to open /acct/uid_10014/pid_5269/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InputDispatcher(  846): Focus entered window: Window{b547996 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  846): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  846): Displayed com.test.thalitest/.MainActivity: +1s477ms
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{39a45261 u0 com.test.thalitest/.MainActivity t222} time:81103
I/Timeline( 5484): Timeline: Activity_idle id: android.os.BinderProxy@1449a819 time:81119
,W/BindingManager( 5484): Cannot call determinedVisibility() - never saw a connection for the pid: 5484
,D/JsMessageQueue( 5484): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  846): Killing 5291:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10021/pid_5291/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5615 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 212 ms] updated apps [took 212 ms] 
,D/jxcore_app_log( 5484): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426120704
,I/chromium( 5484): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 5615): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 5484): CheckpointMarkThreadRoots callback created = 0x99d1ec50
,I/art     ( 5484): CheckpointMarkThreadRoots callback created = 0x99d1ec20
,D/Finsky  ( 5615): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5615): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5615): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5615): com.android.vending: cancel(-1050172287) by com.android.vending
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 5615): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@5dbb1cb on behalf of 5615
D/Ads     ( 5615): Skipping gmscore version check
,D/Finsky  ( 5615): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5615): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  846): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5672 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5615): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5615): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5615): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  846): Killing 5320:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10009/pid_5320/cgroup.procs: No such file or directory
W/ResourcesManager( 5672): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5672): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5672): VM with version 2.1.0 has multidex support
I/MultiDex( 5672): install
I/MultiDex( 5672): VM has multidex support, MultiDex support library is disabled.
,I/art     (  846): Explicit concurrent mark sweep GC freed 22926(1144KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.298ms total 188.717ms
,I/ActivityManager(  846): Process com.android.contacts (pid 5376) has died
,V/JNIHelp ( 5672): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5672): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5672): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1152f7fa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5672): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5672): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5672): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5672): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5672): Reading stored module config
D/ChimeraCfgMgr( 5672): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5672): Loading module APK com.google.android.play.games
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/NativeLibraryUtils( 5672): Install completed successfully. count=14 extracted=0
,I/art     ( 5672): CheckpointMarkThreadRoots callback created = 0xb002d380
,I/ActivityManager(  846): Process com.android.gallery3d (pid 5357) has died
I/art     ( 5672): CheckpointMarkThreadRoots callback created = 0xb002d360
,W/art     ( 5672): Suspending all threads took: 7.377ms
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/ChimeraCfgMgr( 5672): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5672): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5672): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/jxcore-log( 5484): Initializing JXcore engine
,W/jxcore-log( 5484): JXcore engine is ready
D/AsyncTaskServiceImpl( 5672): Submit a task: k
,D/ChimeraCfgMgr( 5672): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5672): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5672): Processing package: com.test.thalitest
,D/GassUtils( 5672): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5672): Found info for package com.test.thalitest in db.
,D/WearableService( 1736): callingUid 10006, callindPid: 1736
E/MDM     ( 1736): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5672): Restart initialization of location
,W/Thread-646( 5642): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5537]" dev="sockfs" ino=5537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-646( 5642): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-646( 5642): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8856]" dev="sockfs" ino=8856 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-646( 5642): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-646( 5642): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-646( 5642): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27698]" dev="sockfs" ino=27698 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/PeopleDatabaseHelper( 5672): cleanUpNonGplusAccounts done.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
W/jxcore-log( 5484): Starting JXcore engine
,I/ActivityManager(  846): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5730 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 5672): Storage manager: low false usage 1.73MB avail 2.38GB capacity 4.06GB
,I/ActivityManager(  846): Process com.lge.appbox.client (pid 5340) has died
,I/art     ( 5672): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5672): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/BaseAppContext( 5672): Using Auth Proxy for data requests.
,W/jxcore-log( 5484): Platform android
W/jxcore-log( 5484): 
W/jxcore-log( 5484): Process ARCH arm
W/jxcore-log( 5484): 
,E/BaseAppContext( 5672): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5672): Using Auth Proxy for data requests.
W/IcingInternalCorpora( 5672): getNumBytesRead when not calculated.
,W/BaseAppContext( 5672): Using Auth Proxy for data requests.
,W/BaseAppContext( 5672): Using Auth Proxy for data requests.
,W/BaseAppContext( 5672): Using Auth Proxy for data requests.
W/BaseAppContext( 5672): Using Auth Proxy for data requests.
W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,W/BaseAppContext( 5672): Using Auth Proxy for data requests.
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5730): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5672): Background sticky concurrent mark sweep GC freed 15922(1427KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 5.132ms total 67.649ms
,W/GAV2    ( 5730): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{29c4018a type 0 when 1454934996077 com.google.android.googlequicksearchbox} when 1454934996077
E/Gmail   ( 5730): Error finding the version of the Email provider.....
E/Gmail   ( 5730): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5730): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5730): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5730): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5730): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5730): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5730): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5730): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5730): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1736): No location to return for getLastLocation()
,W/FusedLocationProvider( 1736): location=null
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@3cb8bda8 on behalf of 5672
D/InitAlarmsService( 3769): Clearing and rescheduling alarms.
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/jxcore-log( 5484): JXcore Cordova bridge is ready!
I/jxcore-log( 5484): 
W/jxcore-log( 5484): JXcore engine is started
W/InstanceID/Rpc( 5672): Found 10006
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5730): Observing account changes for notifications
,I/art     ( 5541): Explicit concurrent mark sweep GC freed 7882(397KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.012ms total 59.004ms
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5796 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  846): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5805 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 23.159ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.813ms
,I/Icing   ( 5672): updateResources: need to parse f{com.google.android.gms}
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.036ms
,D/ChimeraCfgMgr( 5672): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5672): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5672): Background sticky concurrent mark sweep GC freed 8522(730KB) AllocSpace objects, 9(144KB) LOS objects, 6% free, 13MB/14MB, paused 7.705ms total 60.911ms
,I/jxcore-log( 5484): Toggling radios to true
I/jxcore-log( 5484): 
,D/BluetoothAdapter( 5484): enable(): BT is already enabled..!
D/WifiServiceImplEx(  846): setWifiEnabled: true pid=5484, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,W/ResourcesManager( 5805): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/WifiService(  846): setWifiEnabled: true pid=5484, uid=10316
D/WifiServiceImplEx(  846): disconnect pid=5484, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  846): reconnect pid=5484, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5484): Radios toggled
I/jxcore-log( 5484): 
I/jxcore-log( 5484): My device name is: LGE-LG-D722
I/jxcore-log( 5484): 
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2791): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  846): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WfdsMonitor( 1808): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@3c6220c1 on behalf of 5672
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@3208f066 on behalf of 5672
D/LGWifiP2pService(  846): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  846): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Clearing all IP addresses on wlan0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/CalendarProvider2( 5805): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1a09b671
V/NativeCrypto( 1736): Read error: ssl=0xb0059c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1736): SSL shutdown failed: ssl=0xb0059c00: I/O error during system call, Broken pipe
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  846): ignoring duplicate network state non-change
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/WifiHS20(  846): hidePasspointNotification off =false
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:36.76 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  846): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  846): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20(  846): hidePasspointNotification off =false
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:36.772 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  846): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): ValidatedState{ when=-19ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-25ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Forcing reevaluation
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,D/CalendarProvider2( 5805): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5805): Created com.android.providers.calendar.CalendarAlarmManager@355bd7e2(com.android.providers.calendar.CalendarProvider2@1a09b671)
D/PhoneMonitor( 5796): Register our PhoneStateListener
,D/CalendarProvider2( 5805): Scheduling check of next Alarm
D/CalendarProvider2( 5805): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5730): notifyAccountChanged
,I/Gmail   ( 5730): getAccountsCursor
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/ConnectivityService(  846): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  846): disableDataServiceNotify
D/WifiHS20(  846): hidePasspointNotification off =false
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:36.891 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DSQN    (  846): stop dsqn bin
I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiNetworkAgent(  846): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  846): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DhcpStateMachine(  846): StoppedState
D/DhcpStateMachine(  846): StoppedState{ when=-148ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  846): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  846): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/PhoneMonitor( 5796): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/CSLegacyTypeTracker(  846): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  846): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5730): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  846): Process com.android.calendar (pid 3769) has died
,D/WifiHS20(  846): hidePasspointNotification off =false
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:37.002 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:37.006 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/QCNEJ   ( 1844): |CORE| No family connected
V/NetworkPolicy(  846): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/Tethering(  846): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateDISCONNECTED
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  846): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1844): |CORE| No family connected
I/QCNEJ   ( 1844): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  846): MasterInitialState.processMessage what=3
V/NetworkPolicy(  846): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1755): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1755):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateSCANNING
I/QCNEJ   ( 1844): |CORE| sendDefaultNwMsg: default = -1
,D/NetworkManagementService(  846): Removing idletimer
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/Settings(  846): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling( 5796): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5796): [parse] Load xml
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/TelephonyAutoProfiling( 5796): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5796): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PhoneMonitor( 5796): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 5672): Internal init done: storage state 0
,I/NotificationManager( 5672): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5850 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  846): Explicit concurrent mark sweep GC freed 33761(1574KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.470ms total 189.279ms
I/Icing   ( 5672): Post-init done
,I/Gmail   ( 5730): getAccountsCursor
,W/ResourcesManager( 5850): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 5850): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5850): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5850): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5850): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5850): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5850): MmsConfig.loadFromResources
E/Babel_SMS( 5850): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5850): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5850): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5850): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5850): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5850): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5850): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5850): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5850): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5850): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5850): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5850): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5850): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5850): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5850): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5850): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5850): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5850): found sensor: Motion Accel, handle=46
,I/art     ( 5850): CheckpointMarkThreadRoots callback created = 0xb002d810
,W/Settings( 5850): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5850): startup - clean
,I/Babel   ( 5850): deleted: false for 0
,I/art     ( 5850): CheckpointMarkThreadRoots callback created = 0xb002d7f0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/CalendarProvider2( 5805): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5805): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/wpa_supplicant( 2791): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/LocSvc_java(  846): onReceive
,I/wpa_supplicant( 2791): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:37.975 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:37.978 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/AudioCapabilities( 5850): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5850): Unsupported mime audio/adpcm
W/AudioCapabilities( 5850): Unsupported mime audio/g726
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.006 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.012 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/AudioCapabilities( 5850): Unsupported mime audio/x-ms-wma
I/wpa_supplicant( 2791): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  846): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
W/AudioCapabilities( 5850): Unsupported mime audio/wma-voice
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/VideoCapabilities( 5850): Unsupported mime video/mjpg
I/WifiServiceExtension(  846): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,W/VideoCapabilities( 5850): Unsupported mime video/theora
I/WifiServerServiceExt(  846): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  846): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  846): setSecurityType  : 2
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.068 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.07 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  846): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  846): Got NetworkAgent Messenger
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  846): NetworkAgent connected
,D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/AudioCapabilities( 5850): Unsupported mime audio/evrc
W/AudioCapabilities( 5850): Unsupported mime audio/qcelp
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
E/WifiStateMachine(  846): Start Dhcp Watchdog 2
D/DhcpStateMachine(  846): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): WaitBeforeStartState
,W/VideoCapabilities( 5850): Unrecognized profile 2130706433 for video/avc
,D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,W/AudioCapabilities( 5850): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5850): Unsupported mime audio/qcelp
W/AudioCapabilities( 5850): Unsupported mime audio/evrc
W/VideoCapabilities( 5850): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5850): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5850): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5850): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5850): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5850): Unrecognized profile 2130706433 for video/avc
,E/WifiStateMachine(  846): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  846): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  846): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e09c2c6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e09c2c6 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): DHCP Start wake lock is acquired.
D/CommandListener(  274): Setting iface cfg
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  846): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/vclib   ( 5850): onServiceConnected
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateCOMPLETED
W/Babel   ( 5850): Attempted to change video mute state without an active call.
,D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateCOMPLETED
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  846): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  846): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  846): ignoring duplicate network state non-change
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.237 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  846): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.249 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine(  846): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20(  846): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/ConnectivityService(  846): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  846): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  846): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  274): netlink response contains error (File exists)
D/ConnectivityService(  846): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  846): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.272 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  846): addLocalRoutetoDefaultNetwork
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  846): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  846): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/QCNEJ   ( 1844): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:38.276 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1844): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,D/Nat464Xlat(  846): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  846): currentScore = 0, newScore = 20
D/ConnectivityService(  846):    accepting network in place of null
D/ConnectivityService(  846): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1755): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  846): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  846): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1755):   my score=50, my filter=[ Transports: CELLU,LAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  846): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  846): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  846): validation of new default Network = false
D/ConnectivityService(  846): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  846): enableDataServiceNotify 
D/DSQN    (  846): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/Tethering(  846): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1844): |CORE| No family connected
I/QCNEJ   ( 1844): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1844): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] wait 500ms before dns check
V/NetworkPolicy(  846): [LG_RESTRICTED] checkMobilePolicy_type()
I/NotificationManager( 5850): com.google.android.talk: cancel(10436) by com.google.android.talk
D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/DSQN    ( 5894): DSQN samuel.seo ver 141203
E/DSQN    ( 5894): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5894): created command queue thread
I/DSQN    ( 5894): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5894): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/ResourcesManager( 5850): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5850): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5672): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/CheckinService( 5672): Checkin interval check for package: unspecified last checkin: 1454934988762 min interval config: 0 actual interval: 9649
D/DhcpStateMachine(  846): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  846): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  846): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5899): version 5.5.6 starting
E/dhcpcd  ( 5899): get_duid: Read-only file system
,I/CheckinService( 5672): Disabling old GoogleServicesFramework version
I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5906 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 5899): wlan0: rebinding lease of 192.168.1.134
,I/AudioManager( 5180): getMode name:com.lge.qremote
,V/JNIHelp ( 5850): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AudioManager( 5180): getMode name:com.lge.qremote
I/AudioManager( 5180): getMode name:com.lge.qremote
I/AudioManager( 5180): getMode name:com.lge.qremote
,I/AudioManager( 5180): getMode name:com.lge.qremote
D/Icing   ( 5672): Loaded CLD2 Version V2.0 - 20141016
D/UEI.SmartControl( 5906): Quickset Services start...
I/UEI.SmartControl( 5906): Manufacture = LGE
,I/CheckinService( 5672): Checking schedule, now: 1454934998629 next: 1454935018731
I/CheckinService( 5672): active receiver: disabled
E/MDM     ( 1736): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5672): Restart initialization of location
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
D/UEI.SmartControl( 5906): File observer start...
W/GCoreFlp( 1736): No location to return for getLastLocation()
E/UEI.SmartControl( 5906): IR Port is disabled: false
D/UEI.SmartControl( 5906): Starting file observer...
D/UEI.SmartControl( 5906): Extracting JNI libs...
W/FusedLocationProvider( 1736): location=null
D/UEI.SmartControl( 5906): --- this system supports 32-bit or 64-bit only
,I/AudioManager( 5180): getMode name:com.lge.qremote
,I/art     ( 5672): Background partial concurrent mark sweep GC freed 22139(1300KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 13MB/21MB, paused 6.436ms total 118.600ms
I/Icing   ( 5672): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/System  ( 5850): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5850): Installed default security provider GmsCore_OpenSSL
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] DNSResolver start dns
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/QCNEJ   ( 1844): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  846): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Checking http://clients3.google.com/generate_204 on "NG700"
I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/administrator(  846): Handling package changes for user 0
I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/DSQN    ( 5894): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5894): restart monitoring
,D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5894): dsqn report finish
D/DSQN    (  846): DSQM DsqnNotification wlan0  1
D/DSQN    (  846): start to monitor internet connection
I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 12:36:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454934998900], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454934998879]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1808): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Validated
D/ConnectivityService(  846): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService(  846): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1755): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1755):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/ActivityManager(  846): Process com.google.android.apps.docs (pid 5451) has died
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/NotificationManager( 5850): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5939 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 5939): onCreate
,W/AppUp4:DB( 5939):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5939):  setFingerPrint start
I/AppUp4:DB( 5939):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5939):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5939):  SDK version = 0
I/AppUp4:DB( 5939):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5939): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5939): onReceive
I/AppUp4:CustModeStarterReceiver( 5939): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5939): Context : android.app.ReceiverRestrictedContext@70a21c4
D/AppUp4:CustFacade( 5939): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5939): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5939): begin check event
I/AppUp4:CustModeStarterReceiver( 5939): Event For Nothing, skip.
D/ConnectivityService(  846): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NotificationService(  846): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  846): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  846): identical MTU - not setting
D/Nat464Xlat(  846): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  846): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
D/ConnectivityService(  846): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  846): enableDataServiceNotify 
D/DSQN    (  846): start dsqn bin
I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5958 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/DSQN    (  846): dsqn is running restart
I/BackupManagerService(  846): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/UEI.SmartControl( 5906): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5906): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5906): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/DSQN    ( 5964): DSQN samuel.seo ver 141203
E/DSQN    ( 5964): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5964): created command queue thread
I/DSQN    ( 5964): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5964): Interface wlan0 netmask 255.255.255.0 0xc0a80186
W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  846): Process com.lge.bnr (pid 5201) has died
D/WifiDataContinuityService(  846): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  846): set CMD_CAPTIVE_CHECK_COMPLETED
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
I/QCNEJ   ( 1844): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:39.494 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/BackupManagerService(  846): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/BackupManagerService(  846): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@148ef21a
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UEI.SmartControl( 5906): --- Selecting new region: 2
,I/UEI.SmartControl( 5906): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5906): Platform has CIR...
D/UEI.SmartControl( 5906): NO CIR support, need to check package...
I/UEI.SmartControl( 5906): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5906): QS Service created
,W/ResourcesManager( 5958): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5958): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5958): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
E/UEI.SmartControl( 5906): QS start get config
,I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/dhcpcd  ( 5899): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/UEI.SmartControl( 5906): Loading JNI Libs...
,D/UEI.SmartControl( 5906):  configuring local db...
D/LocationProviderProxy(  846): applying state to connected service
,I/dhcpcd  ( 5899): wlan0: leased 192.168.1.134 for 86400 seconds
,I/AppConfig( 5958): Total System Memory = 906309632
,I/GalleryUtils( 5958): Application Heap = 96 MB
I/AppConfig( 5958): App Tier : NOT_DEF
D/SystemHelper( 5958): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6000 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
D/UEI.SmartControl( 5906):  ---- Has DB8: true
D/UEI.SmartControl( 5906): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5906): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5906): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5906): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5906): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5906): IrrcClient ++ 
D/irrcClient( 5906): getIrrcService ++ 
,D/irrcClient( 5906): getIrrcService -- 
D/irrcClient( 5906): IrrcClient -- 
W/irrc_jni( 5906): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5906): Services init done
,I/UEI.SmartControl( 5906): Device manager: loading config....
D/UEI.SmartControl( 5906): Config is loaded...
,D/UEI.SmartControl( 5906):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5906): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5906): QS Service init finished
D/UEI.SmartControl( 5906): QS Service version name: 0.1.73
D/UEI.SmartControl( 5906): QS Service version code: 1073
D/UEI.SmartControl( 5906): Service requested: Control
W/ResourcesManager( 6000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5906): Internal service binding...
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
W/ResourcesManager( 6000): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5906): -----IControl: 11
W/ResourcesManager( 6000): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5906): Caller: com.lge.qremote
D/UEI.SmartControl( 5906): ------------ IControl registerCallback...
I/UEI.SmartControl( 5906): Registering callback...
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/UEI.SmartControl( 5906): -----IControl: 19
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  846): DHCPV4 succeeded on wlan0
D/UEI.SmartControl( 5906): Caller: com.lge.qremote
I/UEI.SmartControl( 5906): Registering Services Ready callback...
D/LgDhcpStateMachineHelper(  846): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/UEI.SmartControl( 5906): Notify client services are ready...
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  846): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  846): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  846): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  846): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  846): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  846): RunningState
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  846): onReceive
D/LocSvc_java(  846): got connectivity action
D/UEI.SmartControl( 5906): -----IControl: 8
D/UEI.SmartControl( 5906): Caller: com.lge.qremote
I/ActivityManager(  846): Killing 5434:com.lge.eula/1000 (adj 15): empty #11
,D/LocSvc_java(  846): broadcast - no network connections
D/LocSvc_java(  846): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  846): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  846): onReceive
D/LocSvc_java(  846): got connectivity action
D/LocSvc_java(  846): broadcast - no network connections
D/LocSvc_java(  846): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  846): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  846): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  846): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  846): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  846): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  846): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  846): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  846): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  846): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  846): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  846): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  846): Killing 5417:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,W/libprocessgroup(  846): failed to open /acct/uid_10069/pid_5417/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_5434/cgroup.procs: No such file or directory
,I/SystemConfig( 6000): BUILD Country: EU
,I/SystemConfig( 6000): BUILD Operator: OPEN
I/ActivityManager(  846): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6023 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 5569:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_5569/cgroup.procs: No such file or directory
,I/SystemConfig( 6000): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6000): existFile = false
I/SystemConfig( 6000): canReadFile = false
I/SystemConfig( 6000): systemFeature RCS result false
D/SystemConfig( 6000): refreshRcsSupport() :false
I/LockScreenSettings( 6023): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6023): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6043 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 5615:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10036/pid_5615/cgroup.procs: No such file or directory
,W/ResourcesManager( 6043): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GAv4-SVC( 5672): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 5730): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1844): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1844): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 13:36:41.135 DNS addrs= 192.168.1.1, 0.0.0.0, 
,V/WifiInternetCheck(  846): Single check msg out of sync, ignoring.
,D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  846): onReceive
D/LocSvc_java(  846): got connectivity action
D/LocSvc_java(  846): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  846): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  846): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  846): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  846): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  846): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  846): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 30242(1858KB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 13MB/22MB, paused 3.735ms total 130.585ms
,I/ActivityManager(  846): Killing 5730:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10053/pid_5730/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6092 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3d171f21 type 2 when 90611 com.android.providers.calendar} when 90611
D/Finsky  ( 6092): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  846): Process com.lge.qremote (pid 5180) has died
,D/Finsky  ( 6092): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6092): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6092): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6092): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@1bf19fa7 on behalf of 6092
D/Ads     ( 6092): Skipping gmscore version check
,D/Finsky  ( 6092): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  846): Explicit concurrent mark sweep GC freed 75410(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.261ms total 201.109ms
,I/ActivityManager(  846): Process com.uei.lg.quicksetsdk.lite (pid 5906) has died
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3c8c9aa3 type 2 when 91315 com.google.android.gms} when 91315
D/Finsky  ( 6092): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PackageBroadcastService( 5672): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 6092): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6092): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  846): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6144 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5672): Null package name or gms related package.  Ignoreing.
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
I/DSQN    ( 5964): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5964): restart monitoring
,D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  846): DSQM DsqnNotification wlan0  1
D/DSQN    (  846): start to monitor internet connection
I/DSQN    ( 5964): dsqn report finish
V/WifiInternetCheck(  846): isHttpConnectionAvailable - We got a valid response : 204
,I/Icing   ( 5672): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6144): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  846): Message: 20
D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@283d1dce:true
,D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6169 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6144): Create singleton instance
,D/UEI.SmartControl( 6169): Quickset Services start...
I/UEI.SmartControl( 6169): Manufacture = LGE
,D/UEI.SmartControl( 6169): File observer start...
I/AudioManager( 6144): getMode name:com.lge.qremote
E/UEI.SmartControl( 6169): IR Port is disabled: false
D/UEI.SmartControl( 6169): Starting file observer...
D/UEI.SmartControl( 6169): Extracting JNI libs...
D/UEI.SmartControl( 6169): --- this system supports 32-bit or 64-bit only
,I/AudioManager( 6144): getMode name:com.lge.qremote
V/SetupWizard( 5796): Connected to Gservices successfully
,D/UEI.SmartControl( 6169): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6169): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6169): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,D/LocationInitializer( 5672): Restart initialization of location
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
,E/MDM     ( 1736): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1736): propertyValue:false
,I/UEI.SmartControl( 6169): --- Selecting new region: 2
,I/UEI.SmartControl( 6169): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6169): Platform has CIR...
D/UEI.SmartControl( 6169): NO CIR support, need to check package...
I/UEI.SmartControl( 6169): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6169): QS Service created
I/ActivityManager(  846): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6205 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  308): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.560ms
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.688ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.138ms
,E/UEI.SmartControl( 6169): QS start get config
,D/UEI.SmartControl( 6169): Loading JNI Libs...
,D/UEI.SmartControl( 6169):  configuring local db...
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6205): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6205): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 6169):  ---- Has DB8: true
,I/Gmail   ( 6205): Observing account changes for notifications
W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 6169): QS start statue = true Error code = 0
D/UEI.SmartControl( 6169): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6169): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,E/Gmail   ( 6205): Error finding the version of the Email provider.....
E/Gmail   ( 6205): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6205): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6205): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6205): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6205): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6205): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6205): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6205): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6205): We do not support migrating this version of the Email provider.
D/UEI.SmartControl( 6169): IRRCDataComm has AudioManager!!!!.
I/Gmail   ( 6205): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/irrc_jni( 6169): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6169): IrrcClient ++ 
D/irrcClient( 6169): getIrrcService ++ 
D/irrcClient( 6169): getIrrcService -- 
D/irrcClient( 6169): IrrcClient -- 
W/irrc_jni( 6169): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6169): Services init done
,I/UEI.SmartControl( 6169): Device manager: loading config....
D/UEI.SmartControl( 6169): QS Service init finished
D/UEI.SmartControl( 6169): QS Service version name: 0.1.73
D/UEI.SmartControl( 6169): QS Service version code: 1073
D/UEI.SmartControl( 6169): Service requested: Control
D/UEI.SmartControl( 6169): Config is loaded...
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 6169):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6169): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6169): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6169): -----IControl: 11
,D/UEI.SmartControl( 6169): Caller: com.lge.qremote
D/UEI.SmartControl( 6169): ------------ IControl registerCallback...
,D/UEI.SmartControl( 6169): Internal service binding...
I/UEI.SmartControl( 6169): Registering callback...
D/UEI.SmartControl( 6169): -----IControl: 19
D/UEI.SmartControl( 6169): Caller: com.lge.qremote
I/UEI.SmartControl( 6169): Registering Services Ready callback...
I/UEI.SmartControl( 6169): Notify client services are ready...
D/UEI.SmartControl( 6169): -----IControl: 8
D/UEI.SmartControl( 6169): Caller: com.lge.qremote
I/ActivityManager(  846): Killing 5939:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Icing   ( 5672): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Gmail   ( 6205): notifyAccountChanged
I/Gmail   ( 6205): getAccountsCursor
I/Gmail   ( 6205): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6205): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6205): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6205): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  846): Killing 5805:com.android.providers.calendar/u0a14 (adj 15): empty #12
,I/Icing   ( 5672): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  846): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/libprocessgroup(  846): failed to open /acct/uid_10014/pid_5805/cgroup.procs: No such file or directory
W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_5939/cgroup.procs: No such file or directory
I/ActivityManager(  846): Killing 5850:com.google.android.talk/u0a61 (adj 15): empty #11
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_5850/cgroup.procs: No such file or directory
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6258): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Gmail   ( 6205): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/IndexDatabaseHelper( 6258): Using schema version: 115
,I/IndexDatabaseHelper( 6258): Index is fine
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/ActivityManager(  846): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6284 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 5958:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10023/pid_5958/cgroup.procs: No such file or directory
,D/Finsky  ( 6092): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  846): RTC_WAKEUP set : Alarm{32d4a08c type 0 when 1454935004763 com.android.vending} when 1454935004763
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6284): [StartReceiver][getUpdateNecessity]update = false
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6284): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd( 6092): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6092): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6092): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6092): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6308 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6092): propertyValue:false
D/libc-netbsd( 6092): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6092): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6308): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd( 6092): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6092): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel_SMS( 6308): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6308): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6308): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6308): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6308): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6308): MmsConfig.loadFromResources
E/Babel_SMS( 6308): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6308): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6308): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6308): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6308): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6308): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6308): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6308): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6308): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6308): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6308): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6308): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6308): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6308): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6308): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6308): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6308): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6308): found sensor: Motion Accel, handle=46
,I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5484): 
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/art     ( 6308): CheckpointMarkThreadRoots callback created = 0xb002d810
,W/Settings( 6308): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6308): startup - clean
I/art     ( 6308): CheckpointMarkThreadRoots callback created = 0xb002d7e0
,I/Babel   ( 6308): deleted: false for 0
,I/qtaguid ( 6092): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6092): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6092): untagSocket(41) failed with errno -22
,D/Finsky  ( 6092): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/AudioCapabilities( 6308): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6308): Unsupported mime audio/adpcm
W/AudioCapabilities( 6308): Unsupported mime audio/g726
W/AudioCapabilities( 6308): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6308): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6308): Unsupported mime video/mjpg
W/VideoCapabilities( 6308): Unsupported mime video/theora
W/AudioCapabilities( 6308): Unsupported mime audio/evrc
,W/AudioCapabilities( 6308): Unsupported mime audio/qcelp
W/VideoCapabilities( 6308): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6308): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6308): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6308): Unsupported mime audio/evrc,
W/VideoCapabilities( 6308): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6308): Unsupported profile 4 for video/mp4v-es
,I/art     (  846): Explicit concurrent mark sweep GC freed 20018(1005KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.451ms total 164.540ms
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6284): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6308): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6308): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6308): Unrecognized profile 2130706433 for video/avc
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
W/VideoCapabilities( 6308): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6284): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/art     ( 6308): Suspending all threads took: 7.057ms
D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/vclib   ( 6308): onServiceConnected
W/Babel   ( 6308): Attempted to change video mute state without an active call.
,I/NotificationManager( 6308): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  846): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6340 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6000:com.android.contacts/u0a18 (adj 15): empty #11
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  846): tsOffsetIs: Apps: 94973974968; DSPS: 3210940; Offset : -3019054654
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/ActivityManager(  846): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6359 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/libprocessgroup(  846): failed to open /acct/uid_10018/pid_6000/cgroup.procs: No such file or directory
V/AlarmManager(  846): RTC_WAKEUP set : Alarm{908ea16 type 0 when 1454935006303 com.google.android.googlequicksearchbox} when 1454935006303
,W/ResourcesManager( 6359): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6340): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6340): CalendarApplication.onCreate()
,I/MultiDex( 6359): VM with version 2.1.0 has multidex support
I/MultiDex( 6359): install
I/MultiDex( 6359): VM has multidex support, MultiDex support library is disabled.
D/PreferenceKeysParser( 6340): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6340): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2f19e4d7, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@70a21c4, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@373248ad, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@355bd7e2, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@eadf773, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@17699630, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3cd7c2a9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce3902e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@146697cf, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2b09e55c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1840e065, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@b1c813a, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@175ee1eb, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2fdfb48, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@a641de1, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2ac17706, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3b47b1c7, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1c9b83f4, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1323b71d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@56dfd92, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@403a363, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@12e6eb60, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1449a819, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@30ea60de, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@70312bf, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2abf5d8c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2843acd5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@537acea, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@16601bdb, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@35cac678, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@289f4151, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@275badb6, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba9ab7, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3821d224, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2045a18d, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@34ecef42, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@8d42b53, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3cbbec90, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2577c989, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1c5ebd8e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1bec29af, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@49b41bc, 
D/GeneralP,referenceUtils( 6340): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
V/JNIHelp ( 6359): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Config  ( 6340): [init]
I/Config  ( 6340): LGCalendar ver.4.40.17
I/Config  ( 6340): start check model
I/Config  ( 6340): start check native_ca
I/Config  ( 6340): Config Operator=OPEN, Country=EU
D/Config  ( 6340): [setDefaultValuesToPref]
D/Config  ( 6340): [parseProfiles]
D/ProfilesParser( 6340): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6340): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6340): [updateProfiletoCountryInfo]
D/GeneralPreference( 6340): [checkAndMigrateOldPreference]
D/AlertReceiver( 6340): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/qtaguid ( 6092): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6092): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6092): untagSocket(41) failed with errno -22
,I/InitNotificationRingtoneService( 6340): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6340): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6340): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
W/ActivityThread( 6359): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6359): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26b00c54: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6359): Installed default security provider GmsCore_OpenSSL
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/NotificationManager( 6359): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6359): com.google.android.gms: cancel(39789) by com.google.android.gms
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/ChimeraCfgMgr( 6359): Reading stored module config
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6340): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6340): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6340): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6340): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6340): onHandleIntent
D/HolidayDataLoader( 6340): readJsonAsset : holiday.json
D/ChimeraCfgMgr( 6359): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/AlertService( 6340): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/HolidayIntentService( 6340): onHandleIntent:holiday data empty
,I/ActivityManager(  846): Process com.google.android.apps.plus (pid 6043) has died
,E/AgendaWidgetManager( 6340): [updateWidgets] 
D/MonthWidgetProvider( 6340): [onReceive]
D/CalendarWidgetProvider( 6340): [onReceive]
D/CalendarWidgetProvider( 6340): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6340): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6340): [onReceive]
D/CalendarWidgetProvider( 6340): [onReceive]
D/CalendarWidgetProvider( 6340): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/CalendarTypeController( 6340): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WiFiOffLoadBroadcast( 6258): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
,D/NativeLibraryUtils( 6359): Install completed successfully. count=14 extracted=0
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5484): 
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/art     ( 6092): WaitForGcToComplete blocked for 86.651ms for cause HomogeneousSpaceCompact
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CAR.SERVICE( 6359): Connecting to CarCallService...
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/art     ( 6359): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6359): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6258): MCCMNC not supported: null
,I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5484): 
I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5484): 
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/CAR.SERVICE( 6359): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6359): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6359): Creating a new PhoneAdapter instance
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6407 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ActivityManager(  846): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6359): setListener: com.google.android.gms.car.dn@461cf33
I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5484): 
I/art     ( 6092): CheckpointMarkThreadRoots callback created = 0xb017f2e0
,I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5484): 
I/art     ( 6092): CheckpointMarkThreadRoots callback created = 0xb017f2d0
,I/ActivityManager(  846): Process com.google.android.gm (pid 6205) has died
W/ActivityManager(  846): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6359): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6359): Starting CarCallService with initial phone null
I/NotificationManager( 6308): com.google.android.talk: cancel(8) by com.google.android.talk
,I/NotificationManager( 6359): com.google.android.gms: cancel(10436) by com.google.android.gms
W/ResourcesManager( 6308): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6308): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CAR.SERVICE( 6359): Package validated; name: com.android.vending
,W/art     ( 6308): Suspending all threads took: 12.402ms
,I/AppUp4:AppBoxCP( 6407): onCreate
W/AppUp4:DB( 6407):  [AppBoxDatabaseHelper] construct
I/NotificationManager( 6092): com.android.vending: cancel(10436) by com.android.vending
I/AppUp4:DB( 6407):  setFingerPrint start
I/AppUp4:DB( 6407):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,V/Finsky  ( 6092): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/AppUp4:DB( 6407):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6407):  SDK version = 0
I/AppUp4:DB( 6407):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6407): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6407): onReceive
I/AppUp4:CustModeStarterReceiver( 6407): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,W/System  ( 6308): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6308): Installed default security provider GmsCore_OpenSSL
D/AppUp4:CustFacade( 6407): Context : android.app.ReceiverRestrictedContext@70a21c4
D/AppUp4:CustFacade( 6407): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6407): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6407): begin check event
I/AppUp4:CustModeStarterReceiver( 6407): Event For Nothing, skip.
,I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6431 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6431): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6431): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6431): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Process com.android.settings (pid 6258) has died
,I/AppConfig( 6431): Total System Memory = 906309632
I/GalleryUtils( 6431): Application Heap = 96 MB
I/AppConfig( 6431): App Tier : NOT_DEF
,D/SystemHelper( 6431): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6451 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,W/ResourcesManager( 6451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6451): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6451): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6451): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6451): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6451): BUILD Country: EU
I/SystemConfig( 6451): BUILD Operator: OPEN
,I/SystemConfig( 6451): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6451): existFile = false
I/SystemConfig( 6451): canReadFile = false
I/SystemConfig( 6451): systemFeature RCS result false
D/SystemConfig( 6451): refreshRcsSupport() :false
,D/LockScreenSettings( 6023): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6023): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/qtaguid ( 6092): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6092): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6092): untagSocket(41) failed with errno -22
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6470 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6092): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6092): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6092): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6092): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{366e0d7c type 0 when 1454935008806 com.android.vending} when 1454935008806
,D/UEI.SmartControl( 6169): Internal timer expired: 1
,D/WearableService( 1736): callingUid 10006, callindPid: 1736
,D/DeviceConnectionService( 1736): client connected with version: 8296000
D/Finsky  ( 6092): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6092): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  846): Killing 6284:com.lge.sync/1000 (adj 15): empty #11
I/ActivityManager(  846): Killing 6169:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #12
,W/System.err( 6144): android.os.DeadObjectException
,W/System.err( 6144): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6144): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6144): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6144): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6144): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6144): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6144): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6144): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6144): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6144): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6144): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6144): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6144): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6144): android.os.DeadObjectException
W/System.err( 6144): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6144): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6144): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6144): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6144): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6144): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6144): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6144): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6144): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6144): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6144): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6144): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6144): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6284/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10089/pid_6169/cgroup.procs: No such file or directory
W/ActivityManager(  846): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6499 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5672): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/UEI.SmartControl( 6499): Quickset Services start...
I/UEI.SmartControl( 6499): Manufacture = LGE
D/UEI.SmartControl( 6499): File observer start...
E/UEI.SmartControl( 6499): IR Port is disabled: false
D/UEI.SmartControl( 6499): Starting file observer...
D/UEI.SmartControl( 6499): Extracting JNI libs...
D/UEI.SmartControl( 6499): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  846): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6527 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 5672): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 85 ms] updated apps [took 84 ms] 
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 33.925ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.239ms
,D/UEI.SmartControl( 6499): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6499): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6499): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.071ms
,I/Icing   ( 5672): updateResources: need to parse f{com.google.android.gms}
I/UEI.SmartControl( 6499): --- Selecting new region: 2
I/UEI.SmartControl( 6499): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6499): Platform has CIR...
D/UEI.SmartControl( 6499): NO CIR support, need to check package...
I/UEI.SmartControl( 6499): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6499): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/UEI.SmartControl( 6499): QS start get config
,D/UEI.SmartControl( 6499): Loading JNI Libs...
,D/UEI.SmartControl( 6499):  configuring local db...
I/MusicStore( 6527): Database version: 120
,D/UEI.SmartControl( 6499):  ---- Has DB8: true
,D/UEI.SmartControl( 6499): QS start statue = true Error code = 0
D/UEI.SmartControl( 6499): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6499): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6499): IRRCDataComm has AudioManager!!!!.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6527): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/irrc_jni( 6499): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6499): IrrcClient ++ 
D/irrcClient( 6499): getIrrcService ++ 
D/irrcClient( 6499): getIrrcService -- 
D/irrcClient( 6499): IrrcClient -- 
W/irrc_jni( 6499): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6499): Services init done
I/UEI.SmartControl( 6499): Device manager: loading config....
D/UEI.SmartControl( 6499): QS Service init finished
,D/UEI.SmartControl( 6499): QS Service version name: 0.1.73
D/UEI.SmartControl( 6499): QS Service version code: 1073
D/UEI.SmartControl( 6499): Service requested: Control
D/UEI.SmartControl( 6499): Config is loaded...
D/UEI.SmartControl( 6499): -----IControl: 11
,D/UEI.SmartControl( 6499): Caller: com.lge.qremote
D/UEI.SmartControl( 6499): ------------ IControl registerCallback...
D/UEI.SmartControl( 6499): Internal service binding...
I/UEI.SmartControl( 6499): Registering callback...
D/UEI.SmartControl( 6499): -----IControl: 19
D/UEI.SmartControl( 6499): Caller: com.lge.qremote
I/UEI.SmartControl( 6499): Registering Services Ready callback...
I/UEI.SmartControl( 6499): Notify client services are ready...
D/UEI.SmartControl( 6499): -----IControl: 8
D/UEI.SmartControl( 6499): Caller: com.lge.qremote
D/UEI.SmartControl( 6499):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6499): Notify AllClients services are ready: 0
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6527): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6527): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6527): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6527): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6527): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6527): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6527): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ce9167f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6527): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6527): GMSCore installation verified
I/ConfigStore( 6527): Config Database version: 1
,I/art     (  846): Explicit concurrent mark sweep GC freed 17760(782KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.252ms total 176.204ms
,I/MediaRouter( 6527): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6527): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6527): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  846): Killing 6144:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10106/pid_6144/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6527): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6580 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Icing   ( 5672): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/GHttpClientFactory( 6527): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6527): Using platform SSLCertificateSocketFactory
I/ActivityManager(  846): Killing 5796:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/Icing   ( 5672): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/ResourcesManager( 6580): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6580): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6580): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_5796/cgroup.procs: No such file or directory
,I/NotificationManager( 6527): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  846): Killing 6407:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_6407/cgroup.procs: No such file or directory
,I/LGEmail ( 6580): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6580): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6580): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6614 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  846): Process com.google.android.apps.plus (pid 6470) has died
,I/HubEmail( 6580): JNI_OnLoad()
I/HubEmail( 6580): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6580): registerNatives()
I/HubEmail( 6580): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6580): registerNativeMethods()
I/HubEmail( 6580): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6580): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6580): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6614): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6614): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6614): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6614): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6614): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6614): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6614): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6614): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6643 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6614): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6614): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6614): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6614): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6614): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6614): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  846): Killing 6431:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10023/pid_6431/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6643): onCreate
W/AppUp4:DB( 6643):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6643):  setFingerPrint start
I/AppUp4:DB( 6643):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6643):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6643):  SDK version = 0
I/AppUp4:DB( 6643):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6643): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6643): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6643): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6643): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6643): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6643): onReceive
I/AppUp4:CustModeStarterReceiver( 6643): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6643): Context : android.app.ReceiverRestrictedContext@eadf773
D/AppUp4:CustFacade( 6643): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6643): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6643): begin check event
I/AppUp4:CustModeStarterReceiver( 6643): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6643): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6643): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6643): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6643): handleAsyncCustNotification do not startCustService
I/ActivityManager(  846): Killing 6451:com.android.contacts/u0a18 (adj 15): empty #11
D/AlertService( 6340): Beginning updateAlertNotification
,W/libprocessgroup(  846): failed to open /acct/uid_10018/pid_6451/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = false
,I/ActivityManager(  846): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6662 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6678 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6662): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 6662): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1a09b671
,D/CalendarProvider2( 6662): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6662): Created com.android.providers.calendar.CalendarAlarmManager@355bd7e2(com.android.providers.calendar.CalendarProvider2@1a09b671)
,D/AlertService( 6340): No fired or scheduled alerts
,I/NotificationManager( 6340): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6340): com.android.calendar: cancel(20) by com.android.calendar
D/PhoneMonitor( 6678): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6678): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6678): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  846): Killing 6023:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/AlertService( 6340): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,W/libprocessgroup(  846): failed to open /acct/uid_10069/pid_6023/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Killing 6359:com.google.android.gms:car/u0a6 (adj 15): empty #11
V/DownloadManager( 3222): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/PhoneMonitor( 6678): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6678): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6678): [parse] Load xml
V/TelephonyAutoProfiling( 6678): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6678): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6678): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_6359/cgroup.procs: No such file or directory
,W/ActivityManager(  846): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
V/DownloadManager( 3222): DownloadService onCreate
I/NotificationManager( 3222): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3222): in removeSpuriousFiles
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@39af07fd on behalf of 3222
I/DownloadManager( 3222): in trimDatabase
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@ea3acf2 on behalf of 3222
I/ActivityManager(  846): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6713 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3222): DownloadService onStartCommand
V/DownloadManager( 3222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5672): Checkin interval check for package: unspecified last checkin: 1454934988762 min interval config: 0 actual interval: 23782
D/AlarmScheduler( 6340): No events found starting within 1 week.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@202b99c0 on behalf of 3222
,I/CheckinService( 5672): Checking schedule, now: 1454935012595 next: 1454935018731
I/CheckinService( 5672): active receiver: disabled
,I/ActivityManager(  846): Killing 6340:com.android.calendar/u0a13 (adj 15): empty #11
,I/ActivityManager(  846): Killing 6499:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,E/libprocessgroup(  846): failed to kill 1 processes for processgroup 6499
,W/libprocessgroup(  846): failed to open /acct/uid_10013/pid_6340/cgroup.procs: No such file or directory
D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:52
,I/ActivityManager(  846): Killing 6308:com.google.android.talk/u0a61 (adj 15): empty #11
V/DownloadManager( 3222): DownloadService onDestroy
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:53
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_6308/cgroup.procs: No such file or directory
,W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6742 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6742): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6742): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6742): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6742): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6742): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6742): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6742): MmsConfig.loadFromResources
E/Babel_SMS( 6742): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6742): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6742): CheckpointMarkThreadRoots callback created = 0xb002d4d0
,D/SensorManager( 6742): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6742): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6742): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6742): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6742): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6742): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6742): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6742): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6742): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6742): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6742): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6742): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6742): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6742): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6742): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6742): found sensor: Motion Accel, handle=46
,I/art     ( 6742): CheckpointMarkThreadRoots callback created = 0xb002d4c0
W/Settings( 6742): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6742): startup - clean
,I/Babel   ( 6742): deleted: false for 0
,W/AudioCapabilities( 6742): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6742): Unsupported mime audio/adpcm
W/AudioCapabilities( 6742): Unsupported mime audio/g726
W/AudioCapabilities( 6742): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6742): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6742): Unsupported mime video/mjpg
W/VideoCapabilities( 6742): Unsupported mime video/theora
I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6779 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6742): Unsupported mime audio/evrc
,W/AudioCapabilities( 6742): Unsupported mime audio/qcelp
W/VideoCapabilities( 6742): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6742): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6742): Unsupported mime audio/qcelp
W/AudioCapabilities( 6742): Unsupported mime audio/evrc
W/VideoCapabilities( 6742): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6742): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6742): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6742): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6742): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6742): onServiceConnected
,W/Babel   ( 6742): Attempted to change video mute state without an active call.
I/NotificationManager( 6742): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6742): propertyValue:false
,I/Babel   ( 6742): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  846): Killing 6092:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10036/pid_6092/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6779): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6779):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6779):   adb logcat -s GAv4
W/GAv4    ( 6779): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6779): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6779): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WebViewFactory( 6779): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/LibraryLoader( 6779): Time to load native libraries: 4 ms (timestamps 3474-3478)
I/LibraryLoader( 6779): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6779): Binding Chromium to main looper Looper (main, tid 1) {20193284}
I/LibraryLoader( 6779): Expected native library version number "",actual native library version number ""
I/chromium( 6779): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6779): Initializing chromium process, singleProcess=true
W/art     ( 6779): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6779): ApplicationContext is null in ApplicationStatus
,W/chromium( 6779): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6779): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6779): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6779): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6779): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6779): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6779): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6779): Remote Branch: 
I/Adreno-EGL( 6779): Local Patches: 
I/Adreno-EGL( 6779): Reconstruct Branch: 
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/NSApplication( 6779): Starting up...
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,V/AudioPolicyService(  278): registerClient() client 0xb551ce80, uid 10079
,W/AudioManagerAndroid( 6779): Requires BLUETOOTH permission
I/ActivityManager(  846): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6844 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6527:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10081/pid_6527/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6863 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6580:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10021/pid_6580/cgroup.procs: No such file or directory
,W/ResourcesManager( 6863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/iu.SyncManager( 5672): SYNC; picasa accounts
,D/NetworkLogImpl( 5672): Loaded NetworkSpeedPredictor
I/iu.Environment( 5672): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  846): Killing 6614:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 5672): num queued entries: 0
,I/iu.UploadsManager( 5672): num updated entries: 0
I/iu.SyncManager( 5672): NEXT; no task
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6614/cgroup.procs: No such file or directory
,I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5484): 
,I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5484): 
,I/jxcore-log( 5484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5484): 
,I/ActivityManager(  846): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6897 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.861ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 20.507ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 20.929ms
,I/MusicStore( 6897): Database version: 120
,I/art     (  846): Explicit concurrent mark sweep GC freed 19129(911KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.435ms total 140.300ms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6897): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6897): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6897): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ce9167f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6897): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6897): GMSCore installation verified
,I/ConfigStore( 6897): Config Database version: 1
,I/MediaRouter( 6897): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6897): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6897): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6897): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6927 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6897): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6897): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6927): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6927): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Killing 6643:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_6643/cgroup.procs: No such file or directory
,I/LGEmail ( 6927): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 6897): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 6927): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/jxcore-log( 5484): Test app app.js loaded
I/jxcore-log( 5484): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5484): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eca66fd added. We now have 1 listener(s)
D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
I/jxcore-log( 5484): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5484): 
,D/eas_req ( 6927): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/chromium( 5484): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6959 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6927): JNI_OnLoad()
,I/HubEmail( 6927): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6927): registerNatives()
I/HubEmail( 6927): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6927): registerNativeMethods()
I/HubEmail( 6927): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6927): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  846): Killing 6662:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/Settings( 6927): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  846): failed to open /acct/uid_10014/pid_6662/cgroup.procs: No such file or directory
D/LGDMClient( 6959): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6959): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6959): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6959): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6959): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6959): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6983 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6959): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6959): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6959): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6959): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6959): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  846): Killing 6678:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_6678/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6983): onCreate
W/AppUp4:DB( 6983):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6983):  setFingerPrint start
I/AppUp4:DB( 6983):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6983):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6983):  SDK version = 0
I/AppUp4:DB( 6983):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6983): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6983): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6983): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6983): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6983): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6983): onReceive
I/AppUp4:CustModeStarterReceiver( 6983): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6983): Context : android.app.ReceiverRestrictedContext@eadf773
D/AppUp4:CustFacade( 6983): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6983): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6983): begin check event
I/AppUp4:CustModeStarterReceiver( 6983): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6983): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6983): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6983): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6983): handleAsyncCustNotification do not startCustService
I/ActivityManager(  846): Killing 6713:com.lge.drmservice/u0a51 (adj 15): empty #11
I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = false
W/libprocessgroup(  846): failed to open /acct/uid_10051/pid_6713/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7002 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7002): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7002): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7002): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  846): Killing 6742:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7002): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7002): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7002): [parse] Load xml
V/TelephonyAutoProfiling( 7002): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7002): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7002): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_6742/cgroup.procs: No such file or directory
,V/DownloadManager( 3222): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3222): DownloadService onCreate
I/DownloadManager( 3222): in removeSpuriousFiles
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@bbba63e on behalf of 3222
I/DownloadManager( 3222): in trimDatabase
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@3d80dc9f on behalf of 3222
,I/NotificationManager( 3222): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/ActivityManager(  846): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7024 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3222): DownloadService onStartCommand
V/DownloadManager( 3222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5672): Checkin interval check for package: unspecified last checkin: 1454934988762 min interval config: 0 actual interval: 29292
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@3ec7e84a on behalf of 3222
,I/CheckinService( 5672): Checking schedule, now: 1454935018084 next: 1454935018731
I/CheckinService( 5672): active receiver: disabled
V/DownloadManager( 3222): DownloadService onDestroy
,I/ActivityManager(  846): Killing 6779:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10079/pid_6779/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:58
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:58
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7045 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7045): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7045): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7045): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7045): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7045): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7045): MmsConfig.loadFromResources
E/Babel_SMS( 7045): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7045): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7045): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7045): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7045): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7045): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7045): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7045): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 7045): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7045): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7045): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7045): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7045): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7045): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7045): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7045): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7045): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7045): found sensor: Motion Accel, handle=46
W/Settings( 7045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7045): startup - clean
I/CheckinService( 5672): Done disabling old GoogleServicesFramework version
,I/Babel   ( 7045): deleted: false for 0
,I/art     ( 7045): CheckpointMarkThreadRoots callback created = 0xb002d920
I/art     ( 7045): CheckpointMarkThreadRoots callback created = 0xb002d8f0
,I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7076 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7045): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7045): Unsupported mime audio/adpcm
W/AudioCapabilities( 7045): Unsupported mime audio/g726
W/AudioCapabilities( 7045): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7045): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7045): Unsupported mime video/mjpg
W/VideoCapabilities( 7045): Unsupported mime video/theora
,W/AudioCapabilities( 7045): Unsupported mime audio/evrc
W/AudioCapabilities( 7045): Unsupported mime audio/qcelp
W/VideoCapabilities( 7045): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7045): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7045): Unsupported mime audio/qcelp
W/AudioCapabilities( 7045): Unsupported mime audio/evrc
W/VideoCapabilities( 7045): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7045): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7045): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7045): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7045): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7045): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7045): onServiceConnected
W/Babel   ( 7045): Attempted to change video mute state without an active call.
,I/NotificationManager( 7045): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7045): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7045): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7045): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7045): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 7045): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7076): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7076):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7076):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7076): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7045): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  846): Killing 6844:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7076): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7076): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  846): failed to open /acct/uid_10048/pid_6844/cgroup.procs: No such file or directory
,I/WebViewFactory( 7076): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7076): Time to load native libraries: 2 ms (timestamps 7970-7972)
I/LibraryLoader( 7076): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7076): Binding Chromium to main looper Looper (main, tid 1) {20193284}
I/LibraryLoader( 7076): Expected native library version number "",actual native library version number ""
I/chromium( 7076): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7076): Initializing chromium process, singleProcess=true
,W/art     ( 7076): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7076): ApplicationContext is null in ApplicationStatus
W/chromium( 7076): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7076): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7076): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7076): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7076): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7076): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7076): Remote Branch: 
I/Adreno-EGL( 7076): Local Patches: 
I/Adreno-EGL( 7076): Reconstruct Branch: 
I/NSApplication( 7076): Starting up...
,V/AudioPolicyService(  278): registerClient() client 0xb4027340, uid 10079
,W/AudioManagerAndroid( 7076): Requires BLUETOOTH permission
I/ActivityManager(  846): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7148 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6863:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_6863/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7167 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 6897:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10081/pid_6897/cgroup.procs: No such file or directory
,W/ResourcesManager( 7167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Killing 6927:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10021/pid_6927/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7191 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,W/ResourcesManager( 7191): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WeatherService( 2688): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:37:0
D/WeatherService( 2688): 2 : TimeTick Intent And Screen On
D/WeatherService( 2688): 2 : SDK version : 21
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
,D/WeatherReflect( 2688): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
D/lim     ( 2688): 2 : time = 13:37
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : Different view - status_min_formatted : 36 != 37
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2688): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2688): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/Weather4x2_optimus( 2688): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2688): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2688): forecast size is 0
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2688): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2688): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2688): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2688): url is : null
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2688): 2 : update view, appWidgetId: 2
D/WeatherService( 2688): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:37:0
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,D/BluetoothManagerService(  846): Message: 20
,D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f1f4747:true
D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
,I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7219 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
V/LGMDMManager( 7191): Create singleton instance
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.269ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 20.889ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.155ms
,D/UEI.SmartControl( 7219): Quickset Services start...
,I/UEI.SmartControl( 7219): Manufacture = LGE
D/UEI.SmartControl( 7219): File observer start...
E/UEI.SmartControl( 7219): IR Port is disabled: false
D/UEI.SmartControl( 7219): Starting file observer...
I/AudioManager( 7191): getMode name:com.lge.qremote
D/UEI.SmartControl( 7219): Extracting JNI libs...
D/UEI.SmartControl( 7219): --- this system supports 32-bit or 64-bit only
E/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  846): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7239 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7219): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7219): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7219): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7219): --- Selecting new region: 2
I/UEI.SmartControl( 7219): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7219): Platform has CIR...
D/UEI.SmartControl( 7219): NO CIR support, need to check package...
I/UEI.SmartControl( 7219): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7219): QS Service created
I/art     (  846): Explicit concurrent mark sweep GC freed 19746(979KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.038ms total 138.703ms
,E/UEI.SmartControl( 7219): QS start get config
,D/UEI.SmartControl( 7219): Loading JNI Libs...
,D/UEI.SmartControl( 7219):  configuring local db...
I/MusicStore( 7239): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 7239): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7239): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7239): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 7219):  ---- Has DB8: true
D/UEI.SmartControl( 7219): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7219): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7219): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7219): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7219): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7219): IrrcClient ++ 
D/irrcClient( 7219): getIrrcService ++ 
,D/irrcClient( 7219): getIrrcService -- 
D/irrcClient( 7219): IrrcClient -- 
W/irrc_jni( 7219): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7219): Services init done
I/UEI.SmartControl( 7219): Device manager: loading config....
,D/UEI.SmartControl( 7219): QS Service init finished
D/UEI.SmartControl( 7219): QS Service version name: 0.1.73
D/UEI.SmartControl( 7219): QS Service version code: 1073
D/UEI.SmartControl( 7219): Service requested: Control
D/UEI.SmartControl( 7219): Config is loaded...
,D/UEI.SmartControl( 7219): Internal service binding...
D/UEI.SmartControl( 7219): -----IControl: 11
D/UEI.SmartControl( 7219): Caller: com.lge.qremote
D/UEI.SmartControl( 7219): ------------ IControl registerCallback...
I/UEI.SmartControl( 7219): Registering callback...
D/UEI.SmartControl( 7219): -----IControl: 19
D/UEI.SmartControl( 7219): Caller: com.lge.qremote
I/UEI.SmartControl( 7219): Registering Services Ready callback...
I/UEI.SmartControl( 7219): Notify client services are ready...
W/ActivityThread( 7239): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7239): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ce9167f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7239): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7239): GMSCore installation verified
D/UEI.SmartControl( 7219): -----IControl: 8
,D/UEI.SmartControl( 7219): Caller: com.lge.qremote
I/ConfigStore( 7239): Config Database version: 1
,I/ActivityManager(  846): Killing 6959:com.lge.lgdmsclient/1000 (adj 15): empty #11
D/UEI.SmartControl( 7219):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7219): Notify AllClients services are ready: 0
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6959/cgroup.procs: No such file or directory
,I/MediaRouter( 7239): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7239): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7239): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  846): Killing 6983:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_6983/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7239): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7273 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7239): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7239): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  846): Killing 7002:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7273): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_7002/cgroup.procs: No such file or directory
,I/NotificationManager( 7239): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7273): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7273): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/eas_req ( 7273): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 7273): JNI_OnLoad()
I/HubEmail( 7273): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7273): registerNatives()
,I/HubEmail( 7273): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7273): registerNativeMethods()
I/HubEmail( 7273): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7273): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  846): Killing 7024:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10051/pid_7024/cgroup.procs: No such file or directory
,W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7299): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7299): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7299): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7299): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7299): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7299): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7323 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7299): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7299): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7299): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7299): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7299): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7299): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  846): Killing 7045:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_7045/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7323): onCreate
,W/AppUp4:DB( 7323):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7323):  setFingerPrint start
I/AppUp4:DB( 7323):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7323):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7323):  SDK version = 0
I/AppUp4:DB( 7323):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7323): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7323): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7323): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7323): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7323): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7323): onReceive
I/AppUp4:CustModeStarterReceiver( 7323): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7323): Context : android.app.ReceiverRestrictedContext@eadf773
D/AppUp4:CustFacade( 7323): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7323): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7323): begin check event
I/AppUp4:CustModeStarterReceiver( 7323): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7323): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7323): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7323): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7323): handleAsyncCustNotification do not startCustService
I/ActivityManager(  846): Killing 7076:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10079/pid_7076/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = true
D/PhoneState( 3157): setPdpRejectCasuse : false
I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7342 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7342): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7342): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7342): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  846): Killing 7148:com.android.chrome/u0a48 (adj 15): empty #11
,D/PhoneMonitor( 7342): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7342): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7342): [parse] Load xml
V/TelephonyAutoProfiling( 7342): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7342): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7342): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  846): failed to open /acct/uid_10048/pid_7148/cgroup.procs: No such file or directory
,V/DownloadManager( 3222): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3222): DownloadService onCreate
I/DownloadManager( 3222): in removeSpuriousFiles
,I/NotificationManager( 3222): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@513bc31 on behalf of 3222
I/DownloadManager( 3222): in trimDatabase
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@2ba43f16 on behalf of 3222
,I/ActivityManager(  846): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7364 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3222): DownloadService onStartCommand
V/DownloadManager( 3222): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@20193284 on behalf of 3222
I/CheckinService( 5672): Checkin interval check for package: unspecified last checkin: 1454934988762 min interval config: 0 actual interval: 33462
,I/CheckinService( 5672): Checking schedule, now: 1454935022270 next: 1454935018731
,I/CheckinService( 5672): active receiver: enabled
V/DownloadManager( 3222): DownloadService onDestroy
,I/CheckinService( 5672): Preparing to send checkin request
I/EventLogService( 5672): Accumulating logs since 1454934981223
,D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:2
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:2
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7388 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7388): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5672): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5672): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5541): Explicit concurrent mark sweep GC freed 2812(111KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 348us total 24.846ms
,I/Babel_SMS( 7388): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7388): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7388): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7388): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7388): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7388): MmsConfig.loadFromResources
E/Babel_SMS( 7388): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7388): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 7388): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7388): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7388): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7388): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7388): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7388): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7388): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7388): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7388): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7388): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7388): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7388): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7388): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7388): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7388): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7388): found sensor: Motion Accel, handle=46
W/Settings( 7388): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7388): startup - clean
I/art     ( 7388): CheckpointMarkThreadRoots callback created = 0xb002d8a0
,I/Babel   ( 7388): deleted: false for 0
I/art     ( 7388): CheckpointMarkThreadRoots callback created = 0xb002d880
,I/ActivityManager(  846): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7424 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{11ea3dad type 0 when 1454935018731 com.google.android.gms} when 1454935018731
I/ActivityManager(  846): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7437 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  846): RTC_WAKEUP set : Alarm{205528e2 type 0 when 1454935022846 com.android.vending} when 1454935022846
,W/ResourcesManager( 7424): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7424): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7460 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 7388): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7388): Unsupported mime audio/adpcm
W/AudioCapabilities( 7388): Unsupported mime audio/g726
W/AudioCapabilities( 7388): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7388): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7388): Unsupported mime video/mjpg
,W/VideoCapabilities( 7388): Unsupported mime video/theora
,I/MultiDex( 7424): VM with version 2.1.0 has multidex support
,I/MultiDex( 7424): install
I/MultiDex( 7424): VM has multidex support, MultiDex support library is disabled.
W/AudioCapabilities( 7388): Unsupported mime audio/evrc
W/AudioCapabilities( 7388): Unsupported mime audio/qcelp
W/VideoCapabilities( 7388): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7388): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7388): Unsupported mime audio/qcelp
W/AudioCapabilities( 7388): Unsupported mime audio/evrc
W/VideoCapabilities( 7388): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7388): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7388): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7388): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7388): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7388): Unrecognized profile 2130706433 for video/avc
,I/art     (  846): Explicit concurrent mark sweep GC freed 12428(604KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.209ms total 148.202ms
I/vclib   ( 7388): onServiceConnected
W/Babel   ( 7388): Attempted to change video mute state without an active call.
,I/NotificationManager( 7388): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7388): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7388): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7388): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7388): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
V/JNIHelp ( 7424): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/System.out( 7388): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7460): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7460): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7460): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7460):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7460):   adb logcat -s GAv4
,I/Babel   ( 7388): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 7460): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7460): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/ActivityThread( 7424): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7424): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26b00c54: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7424): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7424): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7424): com.google.android.gms: cancel(39789) by com.google.android.gms
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7460): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/Finsky  ( 7437): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/GAv4    ( 7460): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7460): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 7424): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7424): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7424): Install completed successfully. count=14 extracted=0
,D/Finsky  ( 7437): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7437): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7437): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7437): com.android.vending: cancel(-1050172287) by com.android.vending
,D/WVCdm   (  278): Instantiating CDM.
I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
,D/Finsky  ( 7437): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7437): [1] Libraries$2.run: Finished loading 1 libraries.
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@261d36a2 on behalf of 7437
D/Ads     ( 7437): Skipping gmscore version check
,D/Finsky  ( 7437): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=4227480085
D/Finsky  ( 7437): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WebViewFactory( 7460): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7460): Time to load native libraries: 2 ms (timestamps 2792-2794)
I/LibraryLoader( 7460): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7460): Binding Chromium to main looper Looper (main, tid 1) {20193284}
,I/LibraryLoader( 7460): Expected native library version number "",actual native library version number ""
I/chromium( 7460): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7460): Initializing chromium process, singleProcess=true
,W/art     ( 7460): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7460): ApplicationContext is null in ApplicationStatus
W/chromium( 7460): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7460): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7460): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7460): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7460): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7460): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7460): Remote Branch: 
I/Adreno-EGL( 7460): Local Patches: 
I/Adreno-EGL( 7460): Reconstruct Branch: 
D/Finsky  ( 7437): [945] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7437): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  846): Killing 7167:com.google.android.apps.plus/u0a86 (adj 15): empty #11
V/AudioPolicyService(  278): registerClient() client 0xb4143340, uid 10079
,W/AudioManagerAndroid( 7460): Requires BLUETOOTH permission
I/art     ( 7424): CheckpointMarkThreadRoots callback created = 0xb00d0dc0
,W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_7167/cgroup.procs: No such file or directory
,I/art     ( 7424): CheckpointMarkThreadRoots callback created = 0xb00d0db0
I/NSApplication( 7460): Starting up...
I/ActivityManager(  846): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7549 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 7219:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 25.582ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.618ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.798ms
,W/System.err( 7191): android.os.DeadObjectException
,W/System.err( 7191): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7191): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7191): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7191): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7191): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7191): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7191): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7191): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7191): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7191): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7191): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7191): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7191): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7191): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7191): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7191): android.os.DeadObjectException
W/System.err( 7191): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7191): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7191): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7191): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7191): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7191): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7191): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7191): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7191): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7191): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7191): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7191): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7191): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7191): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7191): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/dex2oat ( 7567): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  846): Killing 7191:com.lge.qremote/u0a106 (adj 15): empty #12
,I/dex2oat ( 7567): dex2oat took 104.203ms (threads: 4)
,I/Adreno-EGL( 7424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7424): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7424): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7424): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7424): Remote Branch: 
I/Adreno-EGL( 7424): Local Patches: 
I/Adreno-EGL( 7424): Reconstruct Branch: 
,W/libprocessgroup(  846): failed to open /acct/uid_10089/pid_7219/cgroup.procs: No such file or directory
W/ActivityManager(  846): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/libprocessgroup(  846): failed to open /acct/uid_10106/pid_7191/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7583 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7239:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10081/pid_7239/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,W/ResourcesManager( 7583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 7424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7424): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7424): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7424): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7424): Remote Branch: 
I/Adreno-EGL( 7424): Local Patches: 
I/Adreno-EGL( 7424): Reconstruct Branch: 
I/ActivityManager(  846): Killing 7273:com.lge.email/u0a21 (adj 15): empty #11
,I/Adreno-EGL( 7424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7424): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7424): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7424): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7424): Remote Branch: 
I/Adreno-EGL( 7424): Local Patches: 
I/Adreno-EGL( 7424): Reconstruct Branch: 
,W/libprocessgroup(  846): failed to open /acct/uid_10021/pid_7273/cgroup.procs: No such file or directory
,I/WVCdm   (  278): CdmEngine::OpenSession
,I/ActivityManager(  846): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7610 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7610): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7610): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1a09b671
,D/CalendarProvider2( 7610): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7610): Created com.android.providers.calendar.CalendarAlarmManager@355bd7e2(com.android.providers.calendar.CalendarProvider2@1a09b671)
D/CalendarProviderBroadcastReceiver( 7610): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7610): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7610): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7610): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7610): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  846): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7632 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/CalendarProvider2( 7610): [IntentService] Release Lock
,D/CalendarProvider2( 7610): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  846): Killing 7299:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7299/cgroup.procs: No such file or directory
,W/ResourcesManager( 7632): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  846): Message: 20
D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e3c80bb:true
,D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
D/BluetoothAdapterService(484675630)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c9b83f4
I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7650 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7632): Create singleton instance
,I/AudioManager( 7632): getMode name:com.lge.qremote
,I/WVCdm   (  278): CdmEngine::CloseSession
I/ActivityManager(  846): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7669 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=2959246893
,D/UEI.SmartControl( 7650): Quickset Services start...
,I/UEI.SmartControl( 7650): Manufacture = LGE
D/UEI.SmartControl( 7650): File observer start...
E/UEI.SmartControl( 7650): IR Port is disabled: false
D/UEI.SmartControl( 7650): Starting file observer...
D/UEI.SmartControl( 7650): Extracting JNI libs...
D/UEI.SmartControl( 7650): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7650): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7650): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7650): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7650): --- Selecting new region: 2
I/UEI.SmartControl( 7650): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7650): Platform has CIR...
D/UEI.SmartControl( 7650): NO CIR support, need to check package...
,I/UEI.SmartControl( 7650): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7650): QS Service created
E/UEI.SmartControl( 7650): QS start get config
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 114974751939; DSPS: 3866326; Offset : -3019070827
,D/UEI.SmartControl( 7650): Loading JNI Libs...
D/UEI.SmartControl( 7650):  configuring local db...
W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7669): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7669): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7669): Observing account changes for notifications
,E/Gmail   ( 7669): Error finding the version of the Email provider.....
E/Gmail   ( 7669): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7669): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7669): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7669): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7669): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7669): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7669): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7669): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7669): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7669): getAccountsCursor
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7650):  ---- Has DB8: true
,D/UEI.SmartControl( 7650): QS start statue = true Error code = 0
D/UEI.SmartControl( 7650): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7650): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7650): IRRCDataComm has AudioManager!!!!.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/irrc_jni( 7650): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7650): IrrcClient ++ 
D/irrcClient( 7650): getIrrcService ++ 
,D/irrcClient( 7650): getIrrcService -- 
D/irrcClient( 7650): IrrcClient -- 
,W/irrc_jni( 7650): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7650): Services init done
I/UEI.SmartControl( 7650): Device manager: loading config....
D/UEI.SmartControl( 7650): QS Service init finished
D/UEI.SmartControl( 7650): QS Service version name: 0.1.73
D/UEI.SmartControl( 7650): QS Service version code: 1073
D/UEI.SmartControl( 7650): Service requested: Control
,D/UEI.SmartControl( 7650): Config is loaded...
D/UEI.SmartControl( 7650):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7650): Notify AllClients services are ready: 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 7650): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7650): -----IControl: 11
D/UEI.SmartControl( 7650): Internal service binding...
,D/UEI.SmartControl( 7650): Caller: com.lge.qremote
D/UEI.SmartControl( 7650): ------------ IControl registerCallback...
I/UEI.SmartControl( 7650): Registering callback...
D/UEI.SmartControl( 7650): -----IControl: 19
D/UEI.SmartControl( 7650): Caller: com.lge.qremote
I/UEI.SmartControl( 7650): Registering Services Ready callback...
I/UEI.SmartControl( 7650): Notify client services are ready...
D/UEI.SmartControl( 7650): -----IControl: 8
D/UEI.SmartControl( 7650): Caller: com.lge.qremote
,I/AudioManager( 7632): getMode name:com.lge.qremote
I/ActivityManager(  846): Killing 7342:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/Gmail   ( 7669): notifyAccountChanged
,I/Gmail   ( 7669): getAccountsCursor
I/Gmail   ( 7669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7669): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7669): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  846): Killing 7323:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_7342/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_7323/cgroup.procs: No such file or directory
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  846): Killing 7364:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10051/pid_7364/cgroup.procs: No such file or directory
,D/WearableService( 1736): callingUid 10006, callindPid: 1736
E/MDM     ( 1736): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5672): Restart initialization of location
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     (  846): Explicit concurrent mark sweep GC freed 23020(1047KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.121ms total 150.353ms
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
I/AudioManager( 7632): getMode name:com.lge.qremote
D/Finsky  ( 7437): [950] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7736 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,D/libc-netbsd( 7437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 7736): Register our PhoneStateListener
,I/Gmail   ( 7669): getAccountsCursor
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 7736): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7736): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7736): [parse] Load xml
V/TelephonyAutoProfiling( 7736): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7736): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 7437): propertyValue:false
D/PhoneMonitor( 7736): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/MusicWidget( 2655): mDelayedStopHandler : unbind
I/CheckinService( 5672): Checkin interval check for package: unspecified last checkin: 1454934988762 min interval config: 0 actual interval: 38693
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/MusicBrowser( 2704): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2704): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2704): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2704): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2704): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2704): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2704): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2704): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7632): getMode name:com.lge.qremote
I/AudioManager( 7632): getMode name:com.lge.qremote
I/CheckinService( 5672): Checkin interval check for package: unspecified last checkin: 1454934988762 min interval config: 0 actual interval: 38745
I/MediaFocusControl(  846):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@30ea60decom.lge.music.MediaPlaybackService$6@70312bf
D/MusicBrowser( 2704): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/LocationInitializer( 5672): Restart initialization of location
,I/MusicBrowser( 2704): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@146697cf
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/MusicBrowser( 2704): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2704): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2704): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
E/MDM     ( 1736): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
,I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
I/MusicBrowser( 2704): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/AudioManager( 7632): getMode name:com.lge.qremote
I/MusicBrowser( 2704): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2704): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2704): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2704): reset
I/AudioManager( 7632): getMode name:com.lge.qremote
,V/MediaPlayer[Native]( 2704): setListener
V/MediaPlayer[Native]( 2704): disconnect
V/MediaPlayer[Native]( 2704): destructor
W/ContextImpl( 3605): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/AudioFlinger(  278): releasing 19 from 2704 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2704): disconnect
I/AudioManager( 7632): getMode name:com.lge.qremote
D/MusicBrowser( 2704): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2704): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2704): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2704): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2704): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2704): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2704): [SmartShareManagerClient] unregisterListener: 717184396
W/SmartShareClient( 2704): [SmartShareManagerClient] unregisterListener invalid listener: 717184396
I/SmartShareClient( 2704): [SmartShareManagerClient] terminate service: 2704/MediaPlaybackService/926042285
E/HomeCloudIF( 2704): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2704): [SmartShareManagerClient] unbindService context:android.app.Application@2843acd5
V/CloudHub( 2704): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2704): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2704): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2704): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2704): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/AudioManager( 7632): getMode name:com.lge.qremote
I/CloudHub( 2704): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29984
,I/AudioManager( 7632): getMode name:com.lge.qremote
I/AudioManager( 7632): getMode name:com.lge.qremote
I/AudioManager( 7632): getMode name:com.lge.qremote
,I/AudioManager( 7632): getMode name:com.lge.qremote
I/AudioManager( 7632): getMode name:com.lge.qremote
,I/AudioManager( 7632): getMode name:com.lge.qremote
I/ActivityManager(  846): Killing 7460:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  846): failed to kill 1 processes for processgroup 7460
,I/WVCdm   (  278): CdmEngine::CloseSession
I/WVCdm   (  278): L3 Terminate.
,I/CheckinRequestBuilder( 5672): Classify the device as Phone.
,I/ActivityManager(  846): Killing 7549:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10048/pid_7549/cgroup.procs: No such file or directory
,D/libc-netbsd( 5672): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5672): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5672): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5672): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5672): propertyValue:false
D/libc-netbsd( 5672): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5672): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5672): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5672): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5672): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5672): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5672): Sending checkin request (9830 bytes)
,I/CheckinRequestBuilder( 5672): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5672): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5672): Classify the device as Phone.
,I/CheckinTask( 5672): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5672): Checking schedule, now: 1454935029106 next: 1455462278101
I/CheckinService( 5672): active receiver: disabled
,I/CheckinService( 5672): Checking schedule, now: 1454935029134 next: 1455462278101
,I/CheckinService( 5672): active receiver: disabled
D/CheckinService( 5672): Recording last checkin time for package unspecified as 1454935029143
V/SetupWizard( 7736): Connected to Gservices successfully
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/GAV2    ( 7669): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 7650): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1844): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  846): Handling package changes for user 0
I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7819 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 7583:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/NotificationManager( 7388): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7388): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7388): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_7583/cgroup.procs: No such file or directory
I/NotificationService(  846): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  846): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/AppUp4:AppBoxCP( 7819): onCreate
I/BackupManagerService(  846): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/AppUp4:DB( 7819):  [AppBoxDatabaseHelper] construct
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/BackupManagerService(  846): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  846): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b527ad2
,I/AppUp4:DB( 7819):  setFingerPrint start
I/AppUp4:DB( 7819):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7819):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7819):  SDK version = 0
I/AppUp4:DB( 7819):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7819): AppBoxApplication onCreate()
V/JNIHelp ( 7388): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:CustModeStarterReceiver( 7819): onReceive
I/AppUp4:CustModeStarterReceiver( 7819): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7819): Context : android.app.ReceiverRestrictedContext@70a21c4
D/AppUp4:CustFacade( 7819): isCustomizationCompleted : false
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AppUp4:CustFacade( 7819): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7819): begin check event
I/AppUp4:CustModeStarterReceiver( 7819): Event For Nothing, skip.
I/ActivityManager(  846): Killing 7610:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/System  ( 7388): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7388): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  846): failed to open /acct/uid_10014/pid_7610/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7843 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7843): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/LocationProviderProxy(  846): applying state to connected service
,I/AppConfig( 7843): Total System Memory = 906309632
,I/GalleryUtils( 7843): Application Heap = 96 MB
,I/AppConfig( 7843): App Tier : NOT_DEF
D/SystemHelper( 7843): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7863 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7437:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10036/pid_7437/cgroup.procs: No such file or directory
,W/ResourcesManager( 7863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7863): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7863): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7863): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7863): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7863): BUILD Country: EU
I/SystemConfig( 7863): BUILD Operator: OPEN
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  485): init target 500000
,I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
,I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
,D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/WifiController(  846): battery changed pluggedType: 2
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ActivityManager(  846): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7897 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 2704:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  278): 2704 died, releasing its sessions
V/AudioFlinger(  278):  pid 1755 @ 0
V/AudioFlinger(  278):  pid 3157 @ 1
,V/AudioFlinger(  278):  pid 3157 @ 2
W/libprocessgroup(  846): failed to open /acct/uid_10028/pid_2704/cgroup.procs: No such file or directory
I/SystemConfig( 7863): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7863): existFile = false
I/SystemConfig( 7863): canReadFile = false
,I/SystemConfig( 7863): systemFeature RCS result false
D/SystemConfig( 7863): refreshRcsSupport() :false
I/LockScreenSettings( 7897): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  846): Explicit concurrent mark sweep GC freed 23504(1231KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.043ms total 165.835ms
,D/LockScreenSettings( 7897): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7897): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7897): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7897): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7897): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7921 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 7669:com.google.android.gm/u0a53 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 26.726ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.484ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 26.035ms
,W/libprocessgroup(  846): failed to open /acct/uid_10053/pid_7669/cgroup.procs: No such file or directory
,W/ResourcesManager( 7921): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  846): Killing 7736:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
,I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7954 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_7736/cgroup.procs: No such file or directory
,D/Finsky  ( 7954): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 7954): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7954): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7954): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7954): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3222): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3222): created cursor android.database.sqlite.SQLiteCursor@461cf33 on behalf of 7954
D/Finsky  ( 7954): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7954): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7954): Skipping gmscore version check
D/Finsky  ( 7954): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5672): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5672): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7954): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 5672): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/Icing   ( 5672): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5672): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  846): Killing 7650:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7632): android.os.DeadObjectException
,W/System.err( 7632): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7632): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7632): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7632): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7632): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7632): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7632): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7632): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7632): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7632): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7632): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7632): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7632): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7632): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7632): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7632): android.os.DeadObjectException
W/System.err( 7632): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7632): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7632): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7632): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7632): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7632): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7632): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7632): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7632): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7632): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7632): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7632): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7632): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7632): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7632): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  846): failed to open /acct/uid_10089/pid_7650/cgroup.procs: No such file or directory
W/ActivityManager(  846): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8011 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 8011): Quickset Services start...
,I/UEI.SmartControl( 8011): Manufacture = LGE
D/UEI.SmartControl( 8011): File observer start...
E/UEI.SmartControl( 8011): IR Port is disabled: false
D/UEI.SmartControl( 8011): Starting file observer...
D/UEI.SmartControl( 8011): Extracting JNI libs...
D/UEI.SmartControl( 8011): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8011): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8011): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8011): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 8011): --- Selecting new region: 2
I/UEI.SmartControl( 8011): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8011): Platform has CIR...
D/UEI.SmartControl( 8011): NO CIR support, need to check package...
I/UEI.SmartControl( 8011): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8011): QS Service created
E/UEI.SmartControl( 8011): QS start get config
,D/UEI.SmartControl( 8011): Loading JNI Libs...
,D/UEI.SmartControl( 8011):  configuring local db...
D/UEI.SmartControl( 8011):  ---- Has DB8: true
,D/UEI.SmartControl( 8011): QS start statue = true Error code = 0
,D/UEI.SmartControl( 8011): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8011): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8011): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8011): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8011): IrrcClient ++ 
D/irrcClient( 8011): getIrrcService ++ 
D/irrcClient( 8011): getIrrcService -- 
D/irrcClient( 8011): IrrcClient -- 
W/irrc_jni( 8011): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8011): Services init done
,I/UEI.SmartControl( 8011): Device manager: loading config....
D/UEI.SmartControl( 8011): QS Service init finished
D/UEI.SmartControl( 8011): QS Service version name: 0.1.73
D/UEI.SmartControl( 8011): Config is loaded...
D/UEI.SmartControl( 8011): QS Service version code: 1073
D/UEI.SmartControl( 8011): Service requested: Control
I/ActivityManager(  846): Killing 7424:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,D/UEI.SmartControl( 8011): -----IControl: 11
D/UEI.SmartControl( 8011): Caller: com.lge.qremote
D/UEI.SmartControl( 8011): ------------ IControl registerCallback...
I/UEI.SmartControl( 8011): Registering callback...
D/UEI.SmartControl( 8011): -----IControl: 19
D/UEI.SmartControl( 8011): Caller: com.lge.qremote
I/UEI.SmartControl( 8011): Registering Services Ready callback...
I/UEI.SmartControl( 8011): Notify client services are ready...
D/UEI.SmartControl( 8011): -----IControl: 8
,D/UEI.SmartControl( 8011): Caller: com.lge.qremote
D/UEI.SmartControl( 8011):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 8011): Notify AllClients services are ready: 0
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_7424/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8011): Internal service binding...
,I/AudioManager( 7632): getMode name:com.lge.qremote
I/AudioManager( 7632): getMode name:com.lge.qremote
I/AudioManager( 7632): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  846): Killing 7388:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_7388/cgroup.procs: No such file or directory
,D/charger_monitor(  485): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 8011): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 134983299744; DSPS: 4521966; Offset : -3019068257
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
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{23544dc7 type 2 when 145860 com.google.android.gms} when 145860
,I/PerfProfileCollectorService( 5672): Turn off PerfProfile Collection
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PerfProfileCollectorService( 5672): removeStateFiles() called
I/VacuumService( 1736): Vacuum at: now=1454935057532 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  846): ALS enabled for SRE
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28363 ms ago)
,D/qdlights(  846): set_light_backlight: 251
,D/qdlights(  846): set_light_backlight: 248
,D/qdlights(  846): set_light_backlight: 245
,D/qdlights(  846): set_light_backlight: 241
,D/qdlights(  846): set_light_backlight: 238
,D/qdlights(  846): set_light_backlight: 235
,D/qdlights(  846): set_light_backlight: 231
,D/qdlights(  846): set_light_backlight: 228
,D/qdlights(  846): set_light_backlight: 225
,D/qdlights(  846): set_light_backlight: 221
,D/qdlights(  846): set_light_backlight: 218
,D/qdlights(  846): set_light_backlight: 215
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  846): set_light_backlight: 211
,D/qdlights(  846): set_light_backlight: 208
,D/qdlights(  846): set_light_backlight: 205
,D/qdlights(  846): set_light_backlight: 201
,D/qdlights(  846): set_light_backlight: 198
,D/qdlights(  846): set_light_backlight: 195
,D/qdlights(  846): set_light_backlight: 191
,D/qdlights(  846): set_light_backlight: 188
,D/qdlights(  846): set_light_backlight: 185
,D/qdlights(  846): set_light_backlight: 181
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
D/qdlights(  846): set_light_backlight: 178
,D/qdlights(  846): set_light_backlight: 175
,D/qdlights(  846): set_light_backlight: 171
,D/qdlights(  846): set_light_backlight: 168
,D/qdlights(  846): set_light_backlight: 165
,D/qdlights(  846): set_light_backlight: 161
,D/qdlights(  846): set_light_backlight: 158
,D/qdlights(  846): set_light_backlight: 155
,D/qdlights(  846): set_light_backlight: 151
,D/qdlights(  846): set_light_backlight: 148
,D/qdlights(  846): set_light_backlight: 145
,D/qdlights(  846): set_light_backlight: 141
,D/qdlights(  846): set_light_backlight: 138
,D/qdlights(  846): set_light_backlight: 135
,D/qdlights(  846): set_light_backlight: 131
,D/qdlights(  846): set_light_backlight: 128
,D/qdlights(  846): set_light_backlight: 125
,D/qdlights(  846): set_light_backlight: 121
,D/qdlights(  846): set_light_backlight: 118
,D/qdlights(  846): set_light_backlight: 115
,D/qdlights(  846): set_light_backlight: 111
,D/qdlights(  846): set_light_backlight: 108
,D/qdlights(  846): set_light_backlight: 105
,D/qdlights(  846): set_light_backlight: 101
,D/qdlights(  846): set_light_backlight: 98
,D/qdlights(  846): set_light_backlight: 95
,D/qdlights(  846): set_light_backlight: 91
,D/qdlights(  846): set_light_backlight: 88
,D/qdlights(  846): set_light_backlight: 85
,D/qdlights(  846): set_light_backlight: 81
,D/qdlights(  846): set_light_backlight: 78
,D/qdlights(  846): set_light_backlight: 75
,D/qdlights(  846): set_light_backlight: 71
,D/qdlights(  846): set_light_backlight: 68
,D/qdlights(  846): set_light_backlight: 65
,D/qdlights(  846): set_light_backlight: 61
,D/qdlights(  846): set_light_backlight: 58
,D/qdlights(  846): set_light_backlight: 55
,D/qdlights(  846): set_light_backlight: 51
,D/qdlights(  846): set_light_backlight: 48
,D/qdlights(  846): set_light_backlight: 45
,D/qdlights(  846): set_light_backlight: 41
,D/qdlights(  846): set_light_backlight: 38
,D/qdlights(  846): set_light_backlight: 35
,D/qdlights(  846): set_light_backlight: 31
,D/qdlights(  846): set_light_backlight: 28
,D/qdlights(  846): set_light_backlight: 25
,D/qdlights(  846): set_light_backlight: 21
,D/qdlights(  846): set_light_backlight: 18
,D/qdlights(  846): set_light_backlight: 15
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  846): set_light_backlight: 11
,D/qdlights(  846): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 154984219111; DSPS: 5177356; Offset : -3019064729
,I/PowerManagerService(  846): ALS enabled for SRE
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35358 ms ago)
I/PowerManagerService(  846): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  846): ALS enabled for SRE
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35371 ms ago)
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  846): Sleeping (uid 1000)...
D/LPWGController(  846): [updateScreenState] screen on = false
D/LPWGController(  846): disable proximity sensor
,D/LPWGController(  846): enable proximity sensor
I/SensorManager(  846): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@12409d8d] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  846): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  846): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  846): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  846): activate: handle is 48, enable
V/sensors_hal_Ctx(  846): activate sensors is 1400000000000
D/sensors_hal_Thresh(  846): enable: handle=48
I/sensors_hal_SAM(  846): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  846): waitForResponse: timeout=1000
V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  846): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  846): enable: Received response: 0
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35411 ms ago)
I/Adreno-EGL(  846): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  846): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  846): Build Date: 03/02/15 Mon
I/Adreno-EGL(  846): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  846): Remote Branch: 
I/Adreno-EGL(  846): Local Patches: 
I/Adreno-EGL(  846): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1348 us)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Sensors (  425): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  846): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  846): processInd: handle 48, count=1
V/sensors_hal_Thresh(  846): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  846): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  846): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  846): poll: count: 256
I/sensors_hal_Ctx(  846): poll: released wakelock sensor_ind
D/sensors_hal_Util(  846): waitForResponse: timeout=0
D/LPWGController(  846): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  846): current mode = 1  value = 1 1
I/LPWGController(  846): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  846): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  846): set_light_backlight: 0
,I/SensorManager(  846): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  846): activate: handle is 46, disable
V/sensors_hal_Ctx(  846): activate sensors is 1000000000000
D/sensors_hal_LP2(  846): enable: handle=46
D/sensors_hal_LP2(  846): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  846): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  846): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  846): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  846): Display changed displayId=0
,D/DSDPConnection( 1755): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  846): Excessive delay in setPowerMode(): 204ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  846): Got set_interactive hint
D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/WifiServerServiceExt(  846): sendKtScanInterval  mRtspPlay : false
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 846
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
,V/voice   (  278): voice_set_parameters: enter: screen_state=on
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
I/WifiServerServiceExt(  846): set CMD_KT_SCAN_INTERVAL
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/GpsLocationProvider(  846): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1844): |CORE| sendScreenState: state:true
I/LEDService( 1808): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1808): stopPatternFlashing()
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
I/LEDService( 1808): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
I/LEDService( 1808): updateLightsLocked : turn off led
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1808): RESTART MSG
D/SplitWindow(  846): check instance of lgWin Window{30401890 u0 SearchPanel}
,I/Cliptray Service( 1808): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1808): lockStatus = 0
D/LNfcService( 1791): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1791): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1791): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1791): isRequireNfcCRouting() return true
D/LNfcService( 1791): isHCERoutingtoHost() return : true
D/NfcService( 1791): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): newParams.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): screenState= 3
D/NfcService( 1791): Discovery configuration equal, not updating.
D/InputDispatcher(  846): Window went away: Window{211b527a u0 SearchPanel}
I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,D/Ulp_jni (  846): JNI:system_update. Event-0
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 51342(3MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 13MB/22MB, paused 2.066ms total 144.450ms
,V/PhoneApp( 1755): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:48
,D/WeatherService( 2688): 2 : ACTION screen on
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:48
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): ACTION_SCREEN_ON
D/AppCleanupService( 4041): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 846
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  846): CMD_SCREEN_OFF 
D/WifiController(  846): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  846): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1844): |CORE| sendScreenState: state:false
,I/LEDService( 1808): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1808): stopPatternFlashing()
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
I/Sensors (  425): sns_pwr.c(301):releasing wakelock
I/LEDService( 1808): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1808): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1808): clear
I/LEDService( 1808): updateLightsLocked : turn on led
E/LEDService( 1808): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1808): Can't handle this request of patternId:0
D/LEDHandler( 1808): RESTART MSG
I/Cliptray Service( 1808): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1791): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1791): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1882): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1755): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:48
D/WeatherService( 2688): 2 : ACTION screen off
D/WeatherService( 2688): 2 : TimeTick Receiver Unregister
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:48
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): ACTION_SCREEN_OFF
D/AppCleanupService( 4041): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4041): AppUsageStatsSaveTask
E/NxpNfcJni( 1791): getReconnectState = 0x0
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
D/LNfcService( 1791): isRequireNfcCRouting() return true
D/LNfcService( 1791): isHCERoutingtoHost() return : true
D/NfcService( 1791): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): newParams.techmask= mTechMask: 0
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): screenState= 1
E/NxpNfcJni( 1791): getReconnectState = 0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{22268589 type 2 when 161285 com.android.systemui} when 161285
,D/PhoneUtils( 1755): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1755): getCallState : 0
,D/PhoneUtils( 1755): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 174985037853; DSPS: 5832743; Offset : -3019069363
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=403491214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{14af45af type 2 when 181667 android} when 181667
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=403491214 [*alarm*], flags=0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1736): disconnect managed GoogleApiClient
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{a362dbc type 2 when 187232 com.google.android.gms} when 187232
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/PhenotypeConfigurator( 1736): Scheduling Phenotype for one-off execution 1050 seconds from now (1454935098811)
,D/GetConfigurationSnapshotOperation( 1736): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1736): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1736): propertyValue:false
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 194985736648; DSPS: 6488126; Offset : -3019073748
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 214986459453; DSPS: 7143510; Offset : -3019081906
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 234987221060; DSPS: 7798894; Offset : -3019053737
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1808): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,D/LEDHandler( 1808): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1808): Battery Level Remaining: 100%
D/LEDHandler( 1808): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1844): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1844): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 254987980792; DSPS: 8454279; Offset : -3019056137
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 274988656200; DSPS: 9109662; Offset : -3019082504
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5484): --= Surplus to requirements =--
I/jxcore-log( 5484): 
I/jxcore-log( 5484): ****TEST TOOK:  ms ****
I/jxcore-log( 5484): 
I/jxcore-log( 5484): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5484): 
,D/AndroidRuntime( 8194): 
D/AndroidRuntime( 8194): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8194): CheckJNI is OFF
,D/AndroidRuntime( 8194): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  846): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  846): Killing 5484:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  846): Skipping PackageSetting{f19e6a4 com.example.hello/10317} due to missing metadata
,I/WindowState(  846): WIN DEATH: Window{b547996 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  846): Focus left window: Window{b547996 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  846): Window went away: Window{b547996 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  846):   Force finishing activity ActivityRecord{39a45261 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  846): Display changed displayId=0
D/DSDPConnection( 1755): Display #0 changed.
,W/ActivityManager(  846): Spurious death for ProcessRecord{3d3e7dec 5484:com.test.thalitest/u0a316}, curProc for 5484: null
,I/ActivityManager(  846): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1882): [Launcher.java:5203:onStart()]onStart
I/QCNEJ   ( 1844): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1882): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8221 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/System.err( 3605): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/art     ( 5672): Explicit concurrent mark sweep GC freed 8569(471KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/18MB, paused 928us total 123.842ms
W/System.err( 3605): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3605): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3605): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3605): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3605): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3605): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3605): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3605): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3605): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
,W/System.err( 3605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1882): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]LGActivityUtil( 1882): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1882): [Launcher.java:929:onResume()]onResume end
I/Activity( 1882): Activity.onPostResume() called 
I/art     ( 1940): Explicit concurrent mark sweep GC freed 21420(1252KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 6.190ms total 175.393ms
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]EVENT( 1882): [Launcher.java:986:onPause()]onPause
,W/[LGHome]LGWallpaperInfo( 1882): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1882): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1373): handleShortcutListChanged...
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9aa75f7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9aa75f7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  846): Focus entered window: Window{3a5b15a5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 8221): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8221): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8221): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1882): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): handleShortcutListChanged...
I/[LGHome]EVENT( 1882): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1882): [setNavigationBarColor] color=0x 0
,I/art     (  846): Explicit concurrent mark sweep GC freed 60436(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 5.025ms total 315.991ms
,I/art     (  846): WaitForGcToComplete blocked for 181.226ms for cause Explicit
I/LGEmail ( 8221): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8221): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/administrator(  846): Handling package changes for user 0
,W/InputMethodManagerService(  846): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  846): Got RemoteException sending setActive(false) notification to pid 5484 uid 10316
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{3903adb2 u0 com.lge.launcher2/.Launcher t221} time:292586
,W/IInputConnectionWrapper( 1882): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1611): Unable to connect to the editor to retrieve text... will retry later
I/PackageChangeReceiver( 8221): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/art     (  846): Explicit concurrent mark sweep GC freed 8048(482KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.932ms total 283.167ms
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1882): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1882): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1882): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/AppUp4:PreloadHelper( 7819): added Exclude : com.test.thalitest
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/ActivityManager(  846): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8253 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7843:com.android.gallery3d/u0a23 (adj 15): empty #11
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/libprocessgroup(  846): failed to open /acct/uid_10023/pid_7843/cgroup.procs: No such file or directory
,I/NotificationService(  846): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  846): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  846): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AndroidRuntime( 8194): Shutting down VM
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
I/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 8253): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8253): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8253): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8253): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/IndexDatabaseHelper( 8253): Using schema version: 115
,I/IndexDatabaseHelper( 8253): Index is fine
I/Timeline( 1882): Timeline: Activity_idle id: android.os.BinderProxy@22a6f820 time:293175
,I/art     ( 1882): Explicit concurrent mark sweep GC freed 26924(1468KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.157ms total 57.444ms

```
