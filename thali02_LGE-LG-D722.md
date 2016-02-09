#### Test 58380500306a2c5_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/ResourcesManager( 5221): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,--------- beginning of main
I/SystemConfig( 5221): BUILD Country: EU
I/SystemConfig( 5221): BUILD Operator: OPEN
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5248 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 4781:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_4781/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
I/SystemConfig( 5221): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5221): existFile = false
I/SystemConfig( 5221): canReadFile = false
I/SystemConfig( 5221): systemFeature RCS result false
D/SystemConfig( 5221): refreshRcsSupport() :false
I/LockScreenSettings( 5248): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5248): New app installed broadcast received ..
D/AndroidRuntime( 5244): 
D/AndroidRuntime( 5244): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/LockScreenSettings( 5248): Number of installed packages  1
D/AndroidRuntime( 5244): CheckJNI is OFF
I/ActivityManager(  853): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5270 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  853): Killing 4151:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_4151/cgroup.procs: No such file or directory
D/EulaProviderUpdateObserver( 5270): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5270): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5049): android.intent.action.PACKAGE_ADDED : com.test.thalitest
I/ActivityManager(  853): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5298 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 5031:com.lge.clock/u0a10 (adj 15): empty #11
I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 351us total 25.262ms
I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.445ms
D/AndroidRuntime( 5244): Calling main entry com.android.commands.am.Am
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.044ms
W/libprocessgroup(  853): failed to open /acct/uid_10010/pid_5031/cgroup.procs: No such file or directory
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2cc66860 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2cc66860 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  853): AppWindowTokenEx init.. 
D/ContextHelper(  853): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  853): Focus left window: Window{207271b5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5244): Shutting down VM
I/[LGHome]EVENT( 1955): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  853): check instance of lgWin Window{f1341ea u0 Starting com.test.thalitest}
I/ActivityManager(  853): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5317 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1955): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1955): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  853): Starting window displayed
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1380): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2269f1c6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1380): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1380):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1380): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1380): draw background and invalidate : color = 11000000
D/BarTransitions( 1380): draw background and invalidate : color = b0b0b0b
I/HotwordDetector( 2037): Closing mic
I/MicrophoneInputStream( 2037): mic_close com.google.android.apps.gsa.speech.audio.u@2202318d
V/AudioRecord( 2037): stop()
D/AudioRecord( 2037): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a48000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  283): setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a48000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 2037): stop()
V/AudioRecord( 2037): stop()
V/AudioRecord( 2037): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1817): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2037): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2084): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1380): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 3160): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): releasing 16 from 2037 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioSystem( 2749): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb3a48000 exiting
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546dde0)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 2037, calling pid 283
I/HotwordRecognitionRnr( 2037): Hotword detection finished
D/ContextHelper( 5317): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/HotwordRecognitionRnr( 2037): Stopping hotword detection.
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WebViewFactory( 5317): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5317): Time to load native libraries: 2 ms (timestamps 9516-9518)
I/LibraryLoader( 5317): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5317): Binding Chromium to main looper Looper (main, tid 1) {21763c0c}
I/LibraryLoader( 5317): Expected native library version number "",actual native library version number ""
I/chromium( 5317): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5317): Initializing chromium process, singleProcess=true
W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5317): ApplicationContext is null in ApplicationStatus
W/chromium( 5317): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5317): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5317): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5317): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5317): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5317): Remote Branch: 
I/Adreno-EGL( 5317): Local Patches: 
I/Adreno-EGL( 5317): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb39b1fa0, uid 10316
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c3e62cb:true
D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2cac1aa8 type 2 when 79711 android} when 79711
D/AlertService( 3711): Beginning updateAlertNotification
I/ActivityManager(  853): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5363 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GAv4    ( 5298): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5298):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5298):   adb logcat -s GAv4
,D/AlertService( 3711): No fired or scheduled alerts
I/NotificationManager( 3711): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 3711): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(10) by com.android.calendar
,W/GAv4    ( 5298): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/NotificationManager( 3711): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3711): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3711): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3711): No events found starting within 1 week.
,W/GAv4    ( 5298): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5298): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5298): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/GservicesProvider( 5363): Gservices pushing to system: true; secure/global: true
W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5317): onDetachedFromWindow called when already detached. Ignoring
,I/GoogleHttpClient( 5363): GMS http client unavailable, use old client
D/SystemWebViewEngine( 5317): CordovaWebView is running on device made by: LGE
,W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5363): GMS http client unavailable, use old client
,I/Activity( 5317): Activity.onPostResume() called 
,D/OpenGLRenderer( 5317): Render dirty regions requested: true
I/OpenGLRenderer( 5317): Initialized EGL, version 1.4
D/OpenGLRenderer( 5317): Enabling debug mode 0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5298): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
D/Atlas   ( 5317): Validating map...
D/SplitWindow(  853): check instance of lgWin Window{1df4eba2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5402 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 5069:com.google.android.music:main/u0a81 (adj 15): empty #11
W/ResourcesManager( 5298): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5298): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_5069/cgroup.procs: No such file or directory
,W/chromium( 5317): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  853): Killing 5120:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/ResourcesManager( 5402): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5298): CheckpointMarkThreadRoots callback created = 0xb050cad0
,W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_5120/cgroup.procs: No such file or directory
,V/JNIHelp ( 5298): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5298): CheckpointMarkThreadRoots callback created = 0xb050cab0
,D/InputDispatcher(  853): Focus entered window: Window{1df4eba2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/System  ( 5298): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5298): Installed default security provider GmsCore_OpenSSL
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  853): Displayed com.test.thalitest/.MainActivity: +1s474ms
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{1e87e119 u0 com.test.thalitest/.MainActivity t222} time:80466
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Timeline( 5317): Timeline: Activity_idle id: android.os.BinderProxy@3642224b time:80501
,W/BindingManager( 5317): Cannot call determinedVisibility() - never saw a connection for the pid: 5317
,D/JsMessageQueue( 5317): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  853): Killing 5139:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_5139/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5438 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 2037): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 2037): UpdateCorporaTask done [took 196 ms] updated apps [took 196 ms] 
,D/jxcore_app_log( 5317): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426123264
,I/chromium( 5317): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 5438): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 5317): CheckpointMarkThreadRoots callback created = 0x9c13e450
,I/art     ( 5317): CheckpointMarkThreadRoots callback created = 0x9c13e420
,D/Finsky  ( 5438): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5438): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5438): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5438): com.android.vending: cancel(-1050172287) by com.android.vending
,I/NotificationManager( 5438): com.android.vending: cancel(1003285959) by com.android.vending
,V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@2eb6a104 on behalf of 5438
D/Ads     ( 5438): Skipping gmscore version check
,D/Finsky  ( 5438): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5438): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  853): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5480 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5438): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5438): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5438): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  853): Killing 5165:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10009/pid_5165/cgroup.procs: No such file or directory
W/ResourcesManager( 5480): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5480): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5480): VM with version 2.1.0 has multidex support
I/MultiDex( 5480): install
I/MultiDex( 5480): VM has multidex support, MultiDex support library is disabled.
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1881): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
W/MainApplication( 5049): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/charger_monitor(  470): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
W/MainApplication( 5049): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
,I/art     (  853): Explicit concurrent mark sweep GC freed 20672(1023KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.045ms total 174.932ms
,V/JNIHelp ( 5480): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5480): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5480): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d7ef164: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5480): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5480): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5480): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5480): Reading stored module config
,D/PackageBroadcastService( 5480): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager(  853): Process com.android.contacts (pid 5221) has died
,D/ChimeraCfgMgr( 5480): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5480): Loading module APK com.google.android.play.games
,D/QcrilMsgTunnelSocket( 2324): readRilMessage: Buffer = [B@3c74e1e0 HexData = [010000000404000011000000514f454d484f4f4bef0308000100000003]
D/QcrilMsgTunnelSocket( 2324): Rcvd UNSOL response with 28 bytes data for SUB0
D/QcrilMsgTunnelSocket( 2324): Response ID 525295 is not served in this process.
D/QcrilMsgTunnelSocket( 2324): To broadcast an Intent via the notifier to external apps
D/QcrilMsgTunnelIfaceManager( 2324): handleMessage what = 0
D/QcrilMsgTunnelIfaceManager( 2324): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1817): Received Broadcast Intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1817): Oem ID in QCRILHOOK UNSOL RESP is QOEMHOOK
,V/TelephonyAutoProfiling( 1817): [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
,W/art     ( 5480): Suspending all threads took: 44.282ms
,D/PhoneInterfaceManager( 1817): [PhoneIntfMgr] handleMessage : 2
,D/PhoneInterfaceManager( 1817): [PhoneIntfMgr] handleMessage : 3
,D/NativeLibraryUtils( 5480): Install completed successfully. count=14 extracted=0
,I/art     ( 5480): CheckpointMarkThreadRoots callback created = 0xb042d3b0
,I/art     ( 5480): CheckpointMarkThreadRoots callback created = 0xb042d390
,W/jxcore-log( 5317): Initializing JXcore engine
,W/jxcore-log( 5317): JXcore engine is ready
D/ChimeraCfgMgr( 5480): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5480): Module APK com.google.android.play.games already loaded
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
W/Thread-631( 5457): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5842]" dev="sockfs" ino=5842 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
I/ActivityManager(  853): Process com.android.gallery3d (pid 5202) has died
W/Thread-631( 5457): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-631( 5457): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5876]" dev="sockfs" ino=5876 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-631( 5457): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-631( 5457): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-631( 5457): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[23013]" dev="sockfs" ino=23013 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/ChimeraCfgMgr( 5480): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/jxcore-log( 5317): Starting JXcore engine
,D/AsyncTaskServiceImpl( 5480): Submit a task: k
,D/ChimeraCfgMgr( 5480): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5480): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5480): Processing package: com.test.thalitest
,I/PeopleDatabaseHelper( 5480): cleanUpNonGplusAccounts done.
,D/GassUtils( 5480): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 5480): Found info for package com.test.thalitest in db.
I/Icing   ( 5480): Storage manager: low false usage 1.77MB avail 2.38GB capacity 4.06GB
,D/WearableService( 1789): callingUid 10006, callindPid: 1789
W/BaseAppContext( 5480): Using Auth Proxy for data requests.
E/MDM     ( 1789): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5480): Restart initialization of location
,D/AuthorizationBluetoothService( 1789): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1789): com.google.android.gms: cancel(0) by com.google.android.gms
I/art     ( 5480): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5480): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/jxcore-log( 5317): Platform android
W/jxcore-log( 5317): 
W/jxcore-log( 5317): Process ARCH arm
W/jxcore-log( 5317): 
,I/ActivityManager(  853): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5542 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/BaseAppContext( 5480): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5480): Using Auth Proxy for data requests.
W/BaseAppContext( 5480): Using Auth Proxy for data requests.
,W/BaseAppContext( 5480): Using Auth Proxy for data requests.
W/BaseAppContext( 5480): Using Auth Proxy for data requests.
W/BaseAppContext( 5480): Using Auth Proxy for data requests.
,W/GCoreFlp( 1789): No location to return for getLastLocation()
W/FusedLocationProvider( 1789): location=null
W/IcingInternalCorpora( 5480): getNumBytesRead when not calculated.
,W/BaseAppContext( 5480): Using Auth Proxy for data requests.
,I/ActivityManager(  853): Process com.lge.appbox.client (pid 5185) has died
,W/ActivityManager(  853): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{1f90a15f type 0 when 1454971731332 com.android.providers.contacts} when 1454971731332
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{3039d7ac type 2 when 59454 com.google.android.talk} when 59454
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{3a2b040a type 0 when 1455058181497 com.google.android.googlequicksearchbox} when 1455058181497
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/jxcore-log( 5317): JXcore Cordova bridge is ready!
I/jxcore-log( 5317): 
,W/jxcore-log( 5317): JXcore engine is started
I/Gmail   ( 5542): getAccountsCursor
,D/InitAlarmsService( 3711): Clearing and rescheduling alarms.
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5480): updateResources: need to parse f{com.google.android.gms}
W/GAV2    ( 5542): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  853): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5592 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5542): Error finding the version of the Email provider.....
E/Gmail   ( 5542): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5542): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5542): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5542): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5542): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5542): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5542): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5542): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5542): We do not support migrating this version of the Email provider.
,D/ChimeraCfgMgr( 5480): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5480): Module APK com.google.android.play.games already loaded
,I/jxcore-log( 5317): Toggling radios to true
I/jxcore-log( 5317): 
I/Gmail   ( 5542): getAccountsCursor
,D/BluetoothAdapter( 5317): enable(): BT is already enabled..!
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiServiceImplEx(  853): setWifiEnabled: true pid=5317, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  853): setWifiEnabled: true pid=5317, uid=10316
,D/WifiServiceImplEx(  853): disconnect pid=5317, uid=10316, packageName=com.test.thalitest
W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/WifiServiceImplEx(  853): reconnect pid=5317, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5317): Radios toggled
I/jxcore-log( 5317): 
W/ResourcesManager( 5592): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/jxcore-log( 5317): My device name is: LGE-LG-D722
I/jxcore-log( 5317): 
I/wpa_supplicant( 2810): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  853): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2810): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1881): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5542): Observing account changes for notifications
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  853): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1789): Read error: ssl=0xb0461600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1789): SSL shutdown failed: ssl=0xb0461600: I/O error during system call, Broken pipe
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
,D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  853): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-8ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Forcing reevaluation
D/WifiServiceExtension( 1881): isInternetCheckAvailable return false
,D/CalendarProvider2( 5592): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1ccd63e3
,I/ActivityManager(  853): Process com.lge.lockscreensettings (pid 5248) has died
D/WifiHS20(  853): hidePasspointNotification off =false
,I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:42.123 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/GCoreFlp( 1789): No location to return for getLastLocation()
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/FusedLocationProvider( 1789): location=null
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/WifiHS20(  853): hidePasspointNotification off =false
,I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:42.143 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  853): Start Disconnecting Watchdog 1
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/wpa_supplicant( 2810): wlan0: CTRL-EVENT-SCAN-STARTED 
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  853): Default network via Wi-Fi disconnect. stop DSQN
D/WifiHS20(  853): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:42.179 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DSQN    (  853): disableDataServiceNotify
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/DSQN    (  853): stop dsqn bin
D/WifiServiceExtension( 1881): isInternetCheckAvailable return false
D/WifiNetworkAgent(  853): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/ConnectivityService(  853): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  853): hidePasspointNotification off =false
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  853): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  853): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524292
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:42.22 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/CSLegacyTypeTracker(  853): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  853): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:42.235 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiServerServiceExt(  853): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
D/Tethering(  853): MasterInitialState.processMessage what=3
V,/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
D/DhcpStateMachine(  853): StoppedState
D/DhcpStateMachine(  853): StoppedState{ when=-77ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/QCNEJ   ( 1917): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1817): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  853): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1817):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkManagementService(  853): Removing idletimer
W/QCNEJ   ( 1917): |CORE| No family connected
I/QCNEJ   ( 1917): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{7cb439d type 2 when 85005 com.google.android.gms} when 85005
D/CalendarProvider2( 5592): [getOrCreateCalendarAlarmManager]
W/Settings(  853): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1917): |CORE| sendDefaultNwMsg: default = -1
D/WIFI    (  853): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/CalendarProvider2( 5592): Created com.android.providers.calendar.CalendarAlarmManager@21763c0c(com.android.providers.calendar.CalendarProvider2@1ccd63e3)
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateSCANNING
E/ConnectivityService(  853): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/CalendarProvider2( 5592): Scheduling check of next Alarm
,D/CalendarProvider2( 5592): SCHEDULE_ALARM_REMOVE
D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
,W/InstanceID/Rpc( 5480): Found 10006
I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 5363): Explicit concurrent mark sweep GC freed 7884(396KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 809us total 55.943ms
,D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5638 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5542): notifyAccountChanged
,I/Gmail   ( 5542): getAccountsCursor
I/Gmail   ( 5542): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5480): Internal init done: storage state 0
I/Gmail   ( 5542): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/NotificationManager( 5480): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Gmail   ( 5542): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5542): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Icing   ( 5480): Post-init done
D/PhoneMonitor( 5638): Register our PhoneStateListener
,D/PhoneMonitor( 5638): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5638): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5638): [parse] Load xml
,V/TelephonyAutoProfiling( 5638): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5638): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5638): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/Gmail   ( 5542): getAccountsCursor
D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  853): Explicit concurrent mark sweep GC freed 34164(1574KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.468ms total 175.669ms
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5665 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  853): Process com.lge.bnr (pid 5049) has died
,W/ResourcesManager( 5665): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2810): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/CalendarProvider2( 5592): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/LocSvc_java(  853): onReceive
W/ContentResolver( 5592): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.339 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.34 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateASSOCIATING
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2810): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.379 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/wpa_supplicant( 2810): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2810): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateFOUR_WAY_HANDSHAKE
I/WifiServiceExtension(  853): setVHTCapabilityType  : false
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.403 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
,I/WifiServerServiceExt(  853): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  853): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  853): setSecurityType  : 2
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.432 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.435 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/ConnectivityService(  853): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  853): Got NetworkAgent Messenger
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  853): NetworkAgent connected
D/WifiServiceExtension( 1881): isInternetCheckAvailable return false
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  853): Start Dhcp Watchdog 2
,D/DhcpStateMachine(  853): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
I/Babel_SMS( 5665): MmsConfig: mnc/mcc: 0/0
D/DhcpStateMachine(  853): WaitBeforeStartState
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateGROUP_HANDSHAKE
I/Babel_SMS( 5665): MmsConfig.loadMmsSettings
I/Babel_SMS( 5665): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5665): MmsConfig.loadFromDatabase
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateCOMPLETED
,E/Babel_SMS( 5665): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5665): MmsConfig.loadFromResources
E/Babel_SMS( 5665): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5665): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
E/WifiStateMachine(  853): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  853): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f5a26a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f5a26a6 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): DHCP Start wake lock is acquired.
,D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  853): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateCOMPLETED
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  853): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  853): ignoring duplicate network state non-change
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiServiceExtension( 1881): isInternetCheckAvailable return false
D/ConnectivityService(  853): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1881): isInternetCheckAvailable return false
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.615 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.636 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
E/WifiStateMachine(  853): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.651 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1917): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:43.653 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1917): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
E/ConnectivityService(  853): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  853): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  853): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/SensorManager( 5665): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5665): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5665): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5665): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5665): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5665): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5665): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5665): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5665): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5665): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5665): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5665): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5665): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5665): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5665): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5665): found sensor: Motion Accel, handle=46
D/ConnectivityService(  853): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  853): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  853): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  853): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  853): currentScore = 0, newScore = 20
D/ConnectivityService(  853):    accepting network in place of null
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  853): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WIFI    (  853): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wait 500ms before dns check
D/TelephonyNetworkFactory-1( 1817): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
E/ConnectivityService(  853): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  853): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/Telep,honyNetworkFactory-1( 1817):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  853): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  853): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  853): MasterInitialState.processMessage what=3
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): validation of new default Network = false
D/ConnectivityService(  853): Default network via Wi-Fi connected. start DSQN
W/QCNEJ   ( 1917): |CORE| No family connected
I/QCNEJ   ( 1917): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/DSQN    (  853): enableDataServiceNotify 
D/DSQN    (  853): start dsqn bin
I/QCNEJ   ( 1917): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524290
I/DSQN    ( 5704): DSQN samuel.seo ver 141203
E/DSQN    ( 5704): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5704): created command queue thread
I/DSQN    ( 5704): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5704): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/art     ( 5665): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/Icing   ( 5480): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/art     ( 5665): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,D/DhcpStateMachine(  853): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  853): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  853): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
I/dhcpcd  ( 5707): version 5.5.6 starting
E/dhcpcd  ( 5707): get_duid: Read-only file system
I/ActivityManager(  853): Process com.android.calendar (pid 3711) has died
,D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/Settings( 5665): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/Icing   ( 5480): Loaded CLD2 Version V2.0 - 20141016
I/Babel_Crash( 5665): startup - clean
,I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058173859 min interval config: 0 actual interval: 10018
I/Icing   ( 5480): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/dhcpcd  ( 5707): wlan0: rebinding lease of 192.168.1.134
I/CheckinService( 5480): Disabling old GoogleServicesFramework version
I/[SystemUI]QPairHandler( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1917): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1380): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/Babel   ( 5665): deleted: false for 0
,I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  853): Handling package changes for user 0
I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/CheckinService( 5480): Checking schedule, now: 1455058184078 next: 1455058203825
I/CheckinService( 5480): active receiver: disabled
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver start dns
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,V/NetworkPolicy(  853): [LG_RESTRICTED] checkMobilePolicy_type()
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Checking http://clients3.google.com/generate_204 on "NG700"
I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3e77d1eb
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/art     ( 5665): Suspending all threads took: 8.407ms
I/DSQN    ( 5704): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5704): restart monitoring
,I/DSQN    ( 5704): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  853): DSQM DsqnNotification wlan0  1
D/DSQN    (  853): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:49:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455058184315], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455058184299]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1881): isInternetCheckAvailable return false
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
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDataContinuityService(  853): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1817): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1817):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  853): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/AudioCapabilities( 5665): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5665): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5665): Unsupported mime audio/g726
,W/AudioCapabilities( 5665): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5665): Unsupported mime audio/wma-voice
D/LCardEmulationManager( 1864): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1864): getDefaultRoute
W/VideoCapabilities( 5665): Unsupported mime video/mjpg
,W/VideoCapabilities( 5665): Unsupported mime video/theora
,W/AudioCapabilities( 5665): Unsupported mime audio/evrc
,W/AudioCapabilities( 5665): Unsupported mime audio/qcelp
W/VideoCapabilities( 5665): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5723 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5010): getMode name:com.lge.qremote
,W/AudioCapabilities( 5665): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5665): Unsupported mime audio/qcelp
W/AudioCapabilities( 5665): Unsupported mime audio/evrc
W/VideoCapabilities( 5665): Unsupported mime video/mp4v-esdp
,I/AudioManager( 5010): getMode name:com.lge.qremote
I/VideoCapabilities( 5665): Unsupported profile 4 for video/mp4v-es
,I/AudioManager( 5010): getMode name:com.lge.qremote
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/VideoCapabilities( 5665): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5665): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5665): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5665): Unrecognized profile 2130706433 for video/avc
,D/UEI.SmartControl( 5723): Quickset Services start...
I/vclib   ( 5665): onServiceConnected
W/Babel   ( 5665): Attempted to change video mute state without an active call.
I/UEI.SmartControl( 5723): Manufacture = LGE
,D/UEI.SmartControl( 5723): File observer start...
E/UEI.SmartControl( 5723): IR Port is disabled: false
D/UEI.SmartControl( 5723): Starting file observer...
I/AudioManager( 5010): getMode name:com.lge.qremote
D/UEI.SmartControl( 5723): Extracting JNI libs...
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/UEI.SmartControl( 5723): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AudioManager( 5010): getMode name:com.lge.qremote
,I/NotificationManager( 5665): com.google.android.talk: cancel(10436) by com.google.android.talk
E/MDM     ( 1789): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ConnectivityService(  853): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
D/LocationInitializer( 5480): Restart initialization of location
D/AuthorizationBluetoothService( 1789): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1789): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  853): Process com.google.android.apps.docs (pid 5298) has died
,W/GCoreFlp( 1789): No location to return for getLastLocation()
W/FusedLocationProvider( 1789): location=null
I/AudioManager( 5010): getMode name:com.lge.qremote
,W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourcesManager( 5665): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5665): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 5665): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5750 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5723): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5723): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5723): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 372us total 23.475ms
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
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
I/dhcpcd  ( 5707): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 574us total 29.684ms
,D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524295
I/QCNEJ   ( 1917): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/DSQN    (  853): dsqn is running restart
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:45.065 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 30.100ms
,I/DSQN    ( 5765): DSQN samuel.seo ver 141203
E/DSQN    ( 5765): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5765): created command queue thread
I/DSQN    ( 5765): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5765): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/UEI.SmartControl( 5723): --- Selecting new region: 2
I/UEI.SmartControl( 5723): -- Running on KitKat(19) and above! JNI will be used.
,I/dhcpcd  ( 5707): wlan0: leased 192.168.1.134 for 86400 seconds
I/ActivityManager(  853): Process com.google.android.apps.plus (pid 5402) has died
,V/JNIHelp ( 5665): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/UEI.SmartControl( 5723): Platform has CIR...
,D/UEI.SmartControl( 5723): NO CIR support, need to check package...
I/UEI.SmartControl( 5723): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5723): QS Service created
,I/AppUp4:AppBoxCP( 5750): onCreate
,W/AppUp4:DB( 5750):  [AppBoxDatabaseHelper] construct
W/System  ( 5665): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5665): Installed default security provider GmsCore_OpenSSL
I/AppUp4:DB( 5750):  setFingerPrint start
I/AppUp4:DB( 5750):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AppUp4:DB( 5750):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5750):  SDK version = 0
I/AppUp4:DB( 5750):  beforefinger == newfinger no write in DB
,I/ActivityManager(  853): Process com.lge.eula (pid 5270) has died
I/BackgroundMemoryTrimmer( 2037): Trimming objects from memory, since app is in the background.
,I/PhoneApp( 1817): onTrimMemory: 10
I/PhoneApp( 1817): trim memory
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/AppUp4:AppBoxApplication( 5750): AppBoxApplication onCreate()
D/LocSvc_java(  853): broadcast - no network connections
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): broadcast - no network connections
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:0 arg2:1
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
D/AlarmManagerService(  853): Setting time of day to sec=1455058185
W/AlarmManagerService(  853): Unable to set rtc to 1455058185: Invalid argument
,I/AppUp4:CustModeStarterReceiver( 5750): onReceive
,I/AppUp4:CustModeStarterReceiver( 5750): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/GCoreNlp( 1789): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/AppUp4:CustFacade( 5750): Context : android.app.ReceiverRestrictedContext@1f6d7b5e
D/AppUp4:CustFacade( 5750): isCustomizationCompleted : false
E/lowmemorykiller(  242): Error writing /proc/5542/oom_score_adj; errno=22
D/WeatherService( 2727): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:49:45
D/WeatherService( 2727): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/[SystemUI]Clock( 1380): onReceive = android.intent.action.TIME_SET
D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/WeatherService( 2727): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2727): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2727): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2727): 2 : Fixed theme : optimus
I/LgeClockWidgetControlView( 1380): time changed, timezoneChanged : false
I/CalendarProvider2( 5592): onReceive() android.intent.action.TIME_SET
,D/WeatherReflect( 2727): 2 : Map key string is -2
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
D/lim     ( 2727): 2 : time = 23:49
I/WeatherReflect( 2727): Model Name : LG-D722
E/UEI.SmartControl( 5723): QS start get config
D/WeatherTheme( 2727): 2 : exactly same view!
D/WeatherTheme( 2727): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2727): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:49:45
I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5795 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/AppUp4:CustFacade( 5750): isSimDevice : true
I/[LGHome]LGDateChangeReceiver( 1955): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1955): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]LGCalendarIcon( 1955): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/UEI.SmartControl( 5723): Loading JNI Libs...
,D/UEI.SmartControl( 5723):  configuring local db...
,I/ActivityManager(  853): Process com.google.android.gm (pid 5542) has died
,I/PhoneApp( 1817): onTrimMemory: 15
I/PhoneApp( 1817): trim memory
,D/AppUp4:CustModeStarterReceiver( 5750): begin check event
I/AppUp4:CustModeStarterReceiver( 5750): Event For Nothing, skip.
,W/ResourcesManager( 5795): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5795): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5795): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  853): DHCPV4 succeeded on wlan0
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
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5813 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocationProviderProxy(  853): applying state to connected service
D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 5813): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5813): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5813): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5723):  ---- Has DB8: true
,D/UEI.SmartControl( 5723): QS start statue = true Error code = 0
D/UEI.SmartControl( 5723): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5723): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5723): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5723): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5723): IrrcClient ++ 
D/irrcClient( 5723): getIrrcService ++ 
,D/irrcClient( 5723): getIrrcService -- 
D/irrcClient( 5723): IrrcClient -- 
W/irrc_jni( 5723): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5723): Services init done
,I/LGEmail ( 5795): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/UEI.SmartControl( 5723): Device manager: loading config....
D/LGEmail ( 5795): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/UEI.SmartControl( 5723): QS Service init finished
,D/UEI.SmartControl( 5723): QS Service version name: 0.1.73
D/UEI.SmartControl( 5723): QS Service version code: 1073
D/UEI.SmartControl( 5723): Service requested: Control
D/UEI.SmartControl( 5723): Config is loaded...
,D/UEI.SmartControl( 5723): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5723): Service.onTrimMemory: 10
E/UEI.SmartControl( 5723): Setup service releasing memory...
,D/UEI.SmartControl( 5723): -----IControl: 11
D/UEI.SmartControl( 5723): Caller: com.lge.qremote
,D/UEI.SmartControl( 5723): ------------ IControl registerCallback...
I/AppConfig( 5813): Total System Memory = 906309632
I/UEI.SmartControl( 5723): Registering callback...
D/UEI.SmartControl( 5723): -----IControl: 19
D/UEI.SmartControl( 5723): Caller: com.lge.qremote
I/UEI.SmartControl( 5723): Registering Services Ready callback...
I/UEI.SmartControl( 5723): Notify client services are ready...
D/UEI.SmartControl( 5723): -----IControl: 8
,D/UEI.SmartControl( 5723): Caller: com.lge.qremote
,I/GalleryUtils( 5813): Application Heap = 96 MB
I/AppConfig( 5813): App Tier : NOT_DEF
D/UEI.SmartControl( 5723):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5723): Notify AllClients services are ready: 0
D/SystemHelper( 5813): region [EU], country [EU], operator [OPEN], sub-operator []
,I/art     ( 5723): Explicit concurrent mark sweep GC freed 10572(754KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 445us total 78.376ms
D/UEI.SmartControl( 5723): Service.onTrimMemory: 15
E/UEI.SmartControl( 5723): Setup service releasing memory...
D/UEI.SmartControl( 5723): Internal service binding...
I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5839 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 5839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5839): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5839): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5839): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5839): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5856 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Process com.android.vending (pid 5438) has died
,I/SystemConfig( 5839): BUILD Country: EU
I/SystemConfig( 5839): BUILD Operator: OPEN
,I/QCNEJ   ( 1917): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1917): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:49:46.289 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ALBootInit( 5856): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 5856): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5856): [setNextAlert] start
D/Alarms  ( 5856): [setNextAlert] (1)
,D/Alarms  ( 5856):  minTime  = 0
D/Alarms  ( 5856):  -- OK multi -- 0
E/jeny.kim( 5856): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5856): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/SystemConfig( 5839): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5839): existFile = false
I/SystemConfig( 5839): canReadFile = false
I/SystemConfig( 5839): systemFeature RCS result false
D/SystemConfig( 5839): refreshRcsSupport() :false
V/WifiInternetCheck(  853): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5878 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  853): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/CommonUtil( 5856): BUILD Operator: OPEN
,D/Alarms  ( 5856): broadcastToWidgetProvider : false
D/Alarms  ( 5856): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider(  853): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 5856): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 5856): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@511ef6a
V/DigitalAppWidgetProvider( 5856): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@511ef6a
,D/QuickCoverProvider( 5856): onReceiver
I/LockScreenSettings( 5878): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5898 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1789): Explicit concurrent mark sweep GC freed 28333(1718KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 13MB/22MB, paused 1.207ms total 104.767ms
I/NotificationManager( 2037): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  853): Process com.lge.qremote (pid 5010) has died
,D/LockScreenSettings( 5878): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5878): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5878): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5878): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5878): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,W/ResourcesManager( 5898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5917 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/CalendarApplication( 5898): CalendarApplication.onCreate()
D/PreferenceKeysParser( 5898): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5898): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2dd69c99, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1f6d7b5e, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@5e85b3f, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@21763c0c, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2eb6955, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@511ef6a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@35916c5b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@7510cf8, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@f4645d1, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3ad79836, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2df07337, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@260600a4, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@27986e0d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@387d01c2, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf0bd3, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@12f48310, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@6ade09, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@11d780e, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf4922f, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1806c03c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@33da51c5, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3d071a, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3642224b, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@119da428, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@27134541, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@13947ae6, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@78e9827, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3f3cdad4, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@b8df47d, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@19d5f72, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@27428fc3, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@32f6d040, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@380a5b79, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3cde00be, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1fb4651f, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@b98b06c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@154c3635, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf56aca, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2044343b, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@25966758, lg_preferences_alerts_vibratetype=com.android.calendar.adap,tation.PreferenceKey$KeyData@1a9700b1, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@e676996, lg
,W/ResourcesManager( 5917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/GeneralPreferenceUtils( 5898): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5898): [init]
,I/Config  ( 5898): LGCalendar ver.4.40.17
I/Config  ( 5898): start check model
I/Config  ( 5898): start check native_ca
I/Config  ( 5898): Config Operator=OPEN, Country=EU
D/Config  ( 5898): [setDefaultValuesToPref]
D/Config  ( 5898): [parseProfiles]
D/ProfilesParser( 5898): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5898): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5898): [updateProfiletoCountryInfo]
D/GeneralPreference( 5898): [checkAndMigrateOldPreference]
I/ActivityManager(  853): Process com.lge.email (pid 5795) has died
,E/AgendaWidgetManager( 5898): [updateWidgets] 
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{1dc2695 type 2 when 90039 com.android.providers.calendar} when 90039
I/InitNotificationRingtoneService( 5898): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5898): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/art     ( 3189): Explicit concurrent mark sweep GC freed 10592(602KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 475us total 43.734ms
,I/AlertUtils( 5898): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
D/MonthWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5898): [onUpdateAndInitCalendarTime]
W/HolidayIntentService( 5898): onHandleIntent
D/HolidayDataLoader( 5898): readJsonAsset : holiday.json
,E/HolidayIntentService( 5898): onHandleIntent:holiday data empty
,I/ActivityManager(  853): Process com.uei.lg.quicksetsdk.lite (pid 5723) has died
,D/WeekWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 5898): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2727): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:49:47
I/art     (  853): Explicit concurrent mark sweep GC freed 69092(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 7.415ms total 203.493ms
,D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/Weather_cast( 2727): 2 : set auto-update time : 2/10 2:49
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,D/WeatherAncestor( 2727): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:49:47
D/WeatherService( 2727): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5898): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5898): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/ActivityManager(  853): Process com.android.providers.calendar (pid 5592) has died
,I/ActivityManager(  853): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2727): 2 : Utils getTopActivity com.lge.launcher2 / true
I/AlertUtils( 5898): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5898): End InitializeAlertRingtoneService.onHandleIntent
D/WeatherService( 2727): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2727): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/UpdateIcingCorporaServi( 2037): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5965 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
I/UpdateIcingCorporaServi( 2037): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  853): propertyValue:false
I/DSQN    ( 5765): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5765): restart monitoring
D/TimeService( 5942): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455058187717
D/        ( 5942): TimeServiceNative: User Time to be set is 1455058187717
D/QC-time-services( 5942): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5942): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5942): Lib:time_genoff_operation: pargs->ts_val = 1455058187717
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/QC-time-services( 5942): Lib:time_genoff_operation: Send to server  passed!!
I/DSQN    ( 5765): dsqn report finish
D/DSQN    (  853): DSQM DsqnNotification wlan0  1
D/DSQN    (  853): start to monitor internet connection
D/QC-time-services(  358): Daemon: Connection accepted:time_genoff
D/QC-time-services(  358): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455058187717
D/QC-time-services(  358): Daemon:genoff_opr: Base = 2, val = 1455058187717, operation = 0
D/QC-time-services(  358): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/23/70 2:51:16
,D/QC-time-services(  358): Daemon:Value read from RTC seconds = 14957476000
D/QC-time-services(  358): Daemon:new time 1455058187717 
D/QC-time-services(  358): Daemon: delta 1440100711717 genoff 1440100711717 
D/QC-time-services(  358): Daemon:genoff_persistent_update: Writing genoff = 1440100711717 to memory
D/QC-time-services(  358): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  358): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  358): Updating the TOD offset
D/QC-time-services(  358): Daemon:genoff_persistent_update: Writing genoff = 1440100711717 to memory
D/QC-time-services(  358): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  358): Daemon:time_persistent_memory_opr:Genoff write operation 
,V/WifiInternetCheck(  853): isHttpConnectionAvailable - We got a valid response : 204
E/QC-time-services(  358): Daemon:Update to modem bit set
D/QC-time-services(  358): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 5942): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  358): Daemon: Base = 2, Value being sent to MODEM = 1124135911717
E/QC-time-services(  358): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  358): Daemon: Time-services: Waiting to acceptconnection
I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058173859 min interval config: 0 actual interval: 13904
,D/Finsky  ( 5965): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5965): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5965): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5965): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5965): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@15e9f6ed on behalf of 5965
D/Ads     ( 5965): Skipping gmscore version check
,D/Finsky  ( 5965): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5965): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5965): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5480): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5965): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6017 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5480): Null package name or gms related package.  Ignoreing.
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  853): Killing 5638:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/Icing   ( 5480): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_5638/cgroup.procs: No such file or directory
,W/ResourcesManager( 6017): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1521b05f:true
,D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6039 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6017): Create singleton instance
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 22.966ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.645ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.150ms
,I/AudioManager( 6017): getMode name:com.lge.qremote
,I/AudioManager( 6017): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6039): Quickset Services start...
,I/UEI.SmartControl( 6039): Manufacture = LGE
D/UEI.SmartControl( 6039): File observer start...
E/UEI.SmartControl( 6039): IR Port is disabled: false
D/UEI.SmartControl( 6039): Starting file observer...
D/UEI.SmartControl( 6039): Extracting JNI libs...
D/UEI.SmartControl( 6039): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6062 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6039): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6039): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6039): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6039): --- Selecting new region: 2
I/UEI.SmartControl( 6039): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6039): Platform has CIR...
D/UEI.SmartControl( 6039): NO CIR support, need to check package...
I/UEI.SmartControl( 6039): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6039): QS Service created
E/UEI.SmartControl( 6039): QS start get config
,D/PhoneMonitor( 6062): Register our PhoneStateListener
,D/UEI.SmartControl( 6039): Loading JNI Libs...
,D/UEI.SmartControl( 6039):  configuring local db...
V/SetupWizard( 6062): Connected to Gservices successfully
,I/ActivityManager(  853): Killing 5750:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/PhoneMonitor( 6062): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6062): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6062): [parse] Load xml
,V/TelephonyAutoProfiling( 6062): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6062): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6062): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_5750/cgroup.procs: No such file or directory
,D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,D/WearableService( 1789): callingUid 10006, callindPid: 1789
D/UEI.SmartControl( 6039):  ---- Has DB8: true
D/LocationInitializer( 5480): Restart initialization of location
D/AuthorizationBluetoothService( 1789): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1789): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UEI.SmartControl( 6039): QS start statue = true Error code = 0
D/UEI.SmartControl( 6039): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6039): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6039): IRRCDataComm has AudioManager!!!!.
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/irrc_jni( 6039): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6039): IrrcClient ++ 
,D/irrcClient( 6039): getIrrcService ++ 
D/irrcClient( 6039): getIrrcService -- 
D/irrcClient( 6039): IrrcClient -- 
W/irrc_jni( 6039): IRRCPlayer_nativeInit -- 
I/NotificationManager( 1789): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1789): propertyValue:false
W/GCoreFlp( 1789): No location to return for getLastLocation()
W/FusedLocationProvider( 1789): location=null
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{b4b54c8 type 2 when 92548 com.google.android.gms} when 92548
D/UEI.SmartControl( 6039): Services init done
D/UEI.SmartControl( 6039): QS Service init finished
I/UEI.SmartControl( 6039): Device manager: loading config....
D/UEI.SmartControl( 6039): QS Service version name: 0.1.73
D/UEI.SmartControl( 6039): QS Service version code: 1073
,D/UEI.SmartControl( 6039): Service requested: Control
D/UEI.SmartControl( 6039): Config is loaded...
D/UEI.SmartControl( 6039):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6039): Notify AllClients services are ready: 0
,D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 6039): Request IControl service: devices are loaded...
I/ActivityManager(  853): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6099 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6039): Internal service binding...
,D/UEI.SmartControl( 6039): -----IControl: 11
D/UEI.SmartControl( 6039): Caller: com.lge.qremote
D/UEI.SmartControl( 6039): ------------ IControl registerCallback...
I/UEI.SmartControl( 6039): Registering callback...
D/UEI.SmartControl( 6039): -----IControl: 19
D/UEI.SmartControl( 6039): Caller: com.lge.qremote
I/UEI.SmartControl( 6039): Registering Services Ready callback...
I/UEI.SmartControl( 6039): Notify client services are ready...
,D/UEI.SmartControl( 6039): -----IControl: 8
D/UEI.SmartControl( 6039): Caller: com.lge.qremote
I/ActivityManager(  853): Killing 5839:com.android.contacts/u0a18 (adj 15): empty #11
,I/Icing   ( 5480): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  853): Killing 5813:com.android.gallery3d/u0a23 (adj 15): empty #12
,I/Icing   ( 5480): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  853): failed to open /acct/uid_10018/pid_5839/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_5813/cgroup.procs: No such file or directory
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{955f4e0 type 0 when 1455058189821 com.android.vending} when 1455058189821
,D/Finsky  ( 5965): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
,D/libc-netbsd( 5965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 5965): propertyValue:false
D/libc-netbsd( 5965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd( 5965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Gmail   ( 6099): getAccountsCursor
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6099): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6099): Error finding the version of the Email provider.....
E/Gmail   ( 6099): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6099): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6099): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6099): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6099): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6099): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6099): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6099): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6099): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6099): getAccountsCursor
I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/NotificationManager(  853): android: cancelAsUser(2) by android
I/Gmail   ( 6099): Observing account changes for notifications
,I/qtaguid ( 5965): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5965): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5965): untagSocket(41) failed with errno -22
D/Finsky  ( 5965): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/art     (  853): Explicit concurrent mark sweep GC freed 25489(1245KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.162ms total 152.825ms
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  853): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6169 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  853): Process com.lge.clock (pid 5856) has died
,I/NotificationManager(  853): android: cancelAsUser(2) by android
,W/ResourcesManager( 6169): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6169): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Gmail   ( 6099): notifyAccountChanged
,I/MultiDex( 6169): VM with version 2.1.0 has multidex support
I/MultiDex( 6169): install
I/MultiDex( 6169): VM has multidex support, MultiDex support library is disabled.
I/Gmail   ( 6099): getAccountsCursor
I/Gmail   ( 6099): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6099): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  853): Process com.google.android.apps.plus (pid 5917) has died
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6099): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6099): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6141): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6141): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/JNIHelp ( 6169): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/qtaguid ( 5965): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5965): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5965): untagSocket(41) failed with errno -22
,W/ActivityThread( 6169): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6169): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dea156e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6169): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6169): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6169): com.google.android.gms: cancel(39789) by com.google.android.gms
I/IndexDatabaseHelper( 6141): Using schema version: 115
D/ChimeraCfgMgr( 6169): Reading stored module config
I/IndexDatabaseHelper( 6141): Index is fine
,I/ActivityManager(  853): Process com.lge.lockscreensettings (pid 5878) has died
,D/ChimeraCfgMgr( 6169): Loading module com.google.android.gms.car from APK com.google.android.gms
I/Gmail   ( 6099): getAccountsCursor
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 94376853093; DSPS: 3191314; Offset : -3016450102
D/NativeLibraryUtils( 6169): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6169): Connecting to CarCallService...
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{98b95f6 type 0 when 1455058191525 com.google.android.googlequicksearchbox} when 1455058191525
,I/art     ( 6169): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6169): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CAR.SERVICE( 6169): com.google.android.projection.gearhead isn't installed.
,I/art     ( 5965): CheckpointMarkThreadRoots callback created = 0xb0571700
,D/CAR.TEL.Service( 6169): Creating a new CarCallService.
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/CAR.TEL.PhoneAdapter( 6169): Creating a new PhoneAdapter instance
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6169): setListener: com.google.android.gms.car.dn@1854f315
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6169): Returning an existing PhoneAdapter instance.
I/art     ( 5965): CheckpointMarkThreadRoots callback created = 0xb05716d0
D/CAR.TEL.Service( 6169): Starting CarCallService with initial phone null
I/NotificationManager( 6169): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  853): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6206 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5317): 
W/art     ( 6169): Suspending all threads took: 6.034ms
,D/CAR.SERVICE( 6169): Package validated; name: com.android.vending
,I/NotificationManager( 5965): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5965): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/PCSuite ( 6206): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6206): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6206): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
I/PCSuite ( 6206): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6206): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6206): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
I/PCSuite ( 6206): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6206): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6206): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
I/PCSuite ( 6206): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6206): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6206): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6141): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/AlertReceiver( 5898): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 5898): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 5898): [updateWidgets] 
D/MonthWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5898): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [onReceive]
D/CalendarWidgetProvider( 5898): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 5898): [onCreate] mContext.getPackageName() = com.android.calendar
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
I/PCSuite ( 6206): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6206): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
I/PCSuite ( 6206): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6206): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6235 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/NotificationManager( 5665): com.google.android.talk: cancel(8) by com.google.android.talk
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/AppUp4:AppBoxCP( 6235): onCreate
,W/AppUp4:DB( 6235):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6235):  setFingerPrint start
I/AppUp4:DB( 6235):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6235):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6235):  SDK version = 0
I/AppUp4:DB( 6235):  beforefinger == newfinger no write in DB
,I/ActivityManager(  853): Process com.google.android.setupwizard (pid 6062) has died
,D/AppUp4:AppBoxApplication( 6235): AppBoxApplication onCreate()
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppUp4:CustModeStarterReceiver( 6235): onReceive
I/AppUp4:CustModeStarterReceiver( 6235): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,I/NotificationManager(  853): android: cancelAsUser(2) by android
D/AppUp4:CustFacade( 6235): Context : android.app.ReceiverRestrictedContext@1f6d7b5e
D/AppUp4:CustFacade( 6235): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6235): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6235): begin check event
I/AppUp4:CustModeStarterReceiver( 6235): Event For Nothing, skip.
I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6255 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 6255): Total System Memory = 906309632
,I/qtaguid ( 5965): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5965): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5965): untagSocket(41) failed with errno -22
I/GalleryUtils( 6255): Application Heap = 96 MB
I/AppConfig( 6255): App Tier : NOT_DEF
D/SystemHelper( 6255): region [EU], country [EU], operator [OPEN], sub-operator []
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5317): 
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6274 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5317): 
,W/ResourcesManager( 6274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6274): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6274): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6274): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6274): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5317): 
W/ResourcesManager( 5965): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5965): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5965): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5317): 
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/SystemConfig( 6274): BUILD Country: EU
I/SystemConfig( 6274): BUILD Operator: OPEN
,D/Finsky  ( 5965): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{c5a52e7 type 0 when 1455058193508 com.android.vending} when 1455058193508
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5317): 
D/DeviceConnectionService( 1789): client connected with version: 8296000
,I/ActivityManager(  853): Process com.google.android.gm (pid 6099) has died
,D/Finsky  ( 5965): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5965): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6294 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6274): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6274): existFile = false
I/SystemConfig( 6274): canReadFile = false
I/SystemConfig( 6274): systemFeature RCS result false
D/SystemConfig( 6274): refreshRcsSupport() :false
,I/ActivityManager(  853): Killing 5942:com.qualcomm.timeservice/1000 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_5942/cgroup.procs: No such file or directory
,I/LockScreenSettings( 6294): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6294): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6294): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6294): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6294): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6294): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6314 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 5363:com.google.process.gapps/u0a6 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_5363/cgroup.procs: No such file or directory
,W/ResourcesManager( 6314): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  853): Killing 6141:com.android.settings/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6039): Internal timer expired: 1
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6141/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 2037): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5480): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 2037): UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] 
,I/ActivityManager(  853): Start proc com.google.process.gapps for broadcast com.google.android.gsf/.settings.GoogleLocationSettings$LocationSettingsChangedListener: pid=6340 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/PackageBroadcastService( 5480): Null package name or gms related package.  Ignoreing.
I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 301us total 23.320ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 24.042ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.202ms
,I/Icing   ( 5480): updateResources: need to parse f{com.google.android.gms}
I/GservicesProvider( 6340): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 6340): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6340): GMS http client unavailable, use old client
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6370 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6039:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6017): android.os.DeadObjectException
,W/System.err( 6017): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6017): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6017): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6017): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6017): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6017): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6017): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6017): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6017): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6017): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6017): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6017): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6017): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6017): android.os.DeadObjectException
W/System.err( 6017): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6017): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6017): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6017): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6017): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6017): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6017): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6017): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6017): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6017): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6017): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6017): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6017): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_6039/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6394 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PhoneMonitor( 6370): Register our PhoneStateListener
,D/PhoneMonitor( 6370): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6370): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6370): [parse] Load xml
,V/TelephonyAutoProfiling( 6370): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6370): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6370): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/art     (  853): Explicit concurrent mark sweep GC freed 19467(880KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.286ms total 171.566ms
I/art     (  853): WaitForGcToComplete blocked for 43.455ms for cause HeapTrim
,I/ActivityManager(  853): Killing 6206:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6394): Quickset Services start...
,I/UEI.SmartControl( 6394): Manufacture = LGE
D/UEI.SmartControl( 6394): File observer start...
E/UEI.SmartControl( 6394): IR Port is disabled: false
D/UEI.SmartControl( 6394): Starting file observer...
D/UEI.SmartControl( 6394): Extracting JNI libs...
D/UEI.SmartControl( 6394): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6394): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6394): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6394): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6394): --- Selecting new region: 2
,I/UEI.SmartControl( 6394): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6394): Platform has CIR...
D/UEI.SmartControl( 6394): NO CIR support, need to check package...
I/UEI.SmartControl( 6394): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6394): QS Service created
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6206/cgroup.procs: No such file or directory
,D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/UEI.SmartControl( 6394): QS start get config
,I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6426 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6394): Loading JNI Libs...
,I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058173859 min interval config: 0 actual interval: 22131
D/UEI.SmartControl( 6394):  configuring local db...
I/Icing   ( 5480): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/CheckinService( 5480): Checking schedule, now: 1455058196079 next: 1455058203825
I/CheckinService( 5480): active receiver: disabled
,I/Icing   ( 5480): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  853): Killing 6017:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 6394):  ---- Has DB8: true
,W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_6017/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6394): QS start statue = true Error code = 0
D/UEI.SmartControl( 6394): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6394): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6394): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6394): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6394): IrrcClient ++ 
D/irrcClient( 6394): getIrrcService ++ 
,D/irrcClient( 6394): getIrrcService -- 
D/irrcClient( 6394): IrrcClient -- 
W/irrc_jni( 6394): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6394): Services init done
I/UEI.SmartControl( 6394): Device manager: loading config....
D/UEI.SmartControl( 6394): QS Service init finished
,D/UEI.SmartControl( 6394): QS Service version name: 0.1.73
D/UEI.SmartControl( 6394): QS Service version code: 1073
D/UEI.SmartControl( 6394): Service requested: Control
D/UEI.SmartControl( 6394): Config is loaded...
,D/UEI.SmartControl( 6394):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6394): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6394): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6394): Service.onUnbind: IControl
D/UEI.SmartControl( 6394): Service.onDestroy
D/UEI.SmartControl( 6394): Shutdown IRRCPlayer... 
,W/irrc_jni( 6394): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6394): ~IrrcClient ++ 
D/irrcClient( 6394): ~IrrcClient -- 
W/irrc_jni( 6394): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6394): Blaster closed
D/UEI.SmartControl( 6394): Blaster closed
D/UEI.SmartControl( 6394): Shut down QS...
D/UEI.SmartControl( 6394): Stopped file observer...
,I/UEI.SmartControl( 6394): QS lib stop result = true
D/UEI.SmartControl( 6394): QS shutdown complete
D/UEI.SmartControl( 6394): QS Service created
I/MusicStore( 6426): Database version: 120
E/UEI.SmartControl( 6394): QS start get config
,D/UEI.SmartControl( 6394):  configuring local db...
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6426): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6426): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6426): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 6394):  ---- Has DB8: true
,D/UEI.SmartControl( 6394): QS start statue = true Error code = 0
D/UEI.SmartControl( 6394): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6394): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6394): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6394): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6394): IrrcClient ++ 
D/irrcClient( 6394): getIrrcService ++ 
D/irrcClient( 6394): getIrrcService -- 
D/irrcClient( 6394): IrrcClient -- 
,W/irrc_jni( 6394): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6394): Services init done
D/UEI.SmartControl( 6394): QS Service init finished
D/UEI.SmartControl( 6394): QS Service version name: 0.1.73
D/UEI.SmartControl( 6394): QS Service version code: 1073
,D/UEI.SmartControl( 6394): Service requested: Control
I/UEI.SmartControl( 6394): Device manager: loading config....
D/UEI.SmartControl( 6394): Config is loaded...
,E/ActivityThread( 6394): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@7510cf8 that was originally bound here
E/ActivityThread( 6394): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@7510cf8 that was originally bound here
E/ActivityThread( 6394): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6394): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6394): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6394): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6394): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6394): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6394): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6394): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6394): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6394): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6394): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6394): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6394): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6394): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6394): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6394): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6394): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6394): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6394): Internal service binding...
W/ResourcesManager( 6426): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6394):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6394): Notify AllClients services are ready: 0
,V/JNIHelp ( 6426): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6426): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6426): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1db09b01: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6426): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6426): GMSCore installation verified
I/ConfigStore( 6426): Config Database version: 1
,D/CAR.SERVICE( 6169): mConnectedToCar = false, abort
,E/ActivityThread( 6169): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1b43755d that was originally bound here
E/ActivityThread( 6169): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1b43755d that was originally bound here
E/ActivityThread( 6169): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6169): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6169): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6169): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6169): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6169): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6169): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6169): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6169): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6169): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6169): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6169): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6169): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6169): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6169): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6169): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6169): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6169): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6169): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6169): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6169): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6169): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6169): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6169): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@14cd4cc that was originally bound here
E/ActivityThread( 6169): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@14cd4cc that was originally bound here
E/ActivityThread( 6169): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6169): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6169): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6169): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6169): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6169): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6169): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6169): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6169): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6169): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6169): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6169): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6169): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6169): 	at android.app.ActivityThread.access,$1900(ActivityThread.java:155)
E/ActivityThread( 6169): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6169): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6169): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6169): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6169): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6169): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6169): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6169): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  853): Unbind failed: could not find connection for android.os.BinderProxy@c5a988e
,I/MediaRouter( 6426): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6426): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6426): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  853): Killing 6235:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_6235/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6426): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6473 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6426): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AlertService( 5898): Beginning updateAlertNotification
I/GoogleURLConnFactory( 6426): Using platform SSLCertificateSocketFactory
I/ActivityManager(  853): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6491 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Killing 6255:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager( 6473): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6491): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6491): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1ccd63e3
,W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_6255/cgroup.procs: No such file or directory
,I/NotificationManager( 6426): com.google.android.music: cancel(1061) by com.google.android.music
D/CalendarProvider2( 6491): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6491): Created com.android.providers.calendar.CalendarAlarmManager@21763c0c(com.android.providers.calendar.CalendarProvider2@1ccd63e3)
D/AlertService( 5898): No fired or scheduled alerts
,I/NotificationManager( 5898): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 5898): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 5898): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5898): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5898): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  853): Killing 6274:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10018/pid_6274/cgroup.procs: No such file or directory
,I/LGEmail ( 6473): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/AlarmScheduler( 5898): No events found starting within 1 week.
D/LGEmail ( 6473): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  853): Killing 5665:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_5665/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Killing 5898:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_5898/cgroup.procs: No such file or directory
,D/eas_req ( 6473): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6525 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6473): JNI_OnLoad()
I/HubEmail( 6473): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6473): registerNatives()
I/HubEmail( 6473): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6473): registerNativeMethods()
I/HubEmail( 6473): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6473): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  853): Killing 6294:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_6294/cgroup.procs: No such file or directory
W/Settings( 6473): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6525): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6525): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6525): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6525): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6525): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6525): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6549 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6525): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6525): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6525): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6525): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6525): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  853): Killing 6169:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_6169/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6549): onCreate
,W/AppUp4:DB( 6549):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6549):  setFingerPrint start
,I/AppUp4:DB( 6549):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6549):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6549):  SDK version = 0
I/AppUp4:DB( 6549):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6549): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6549): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6549): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6549): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6549): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6549): onReceive
I/AppUp4:CustModeStarterReceiver( 6549): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6549): Context : android.app.ReceiverRestrictedContext@2eb6955
D/AppUp4:CustFacade( 6549): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6549): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6549): begin check event
I/AppUp4:CustModeStarterReceiver( 6549): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6549): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6549): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6549): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6549): handleAsyncCustNotification do not startCustService
I/ActivityManager(  853): Killing 6314:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_6314/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6370): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6370): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3189): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3189): DownloadService onCreate
I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6573 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/DownloadManager( 3189): in removeSpuriousFiles
I/NotificationManager( 3189): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@6288922 on behalf of 3189
I/DownloadManager( 3189): in trimDatabase
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@2b56efb3 on behalf of 3189
,V/DownloadManager( 3189): DownloadService onStartCommand
V/DownloadManager( 3189): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@2dea156e on behalf of 3189
I/ActivityManager(  853): Killing 5965:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10036/pid_5965/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2727): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:49:58
V/DownloadManager( 3189): DownloadService onDestroy
D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/WeatherAncestor( 2727): connectivity changed - connection : true
D/Weather_cast( 2727): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2727): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:49:58
D/WeatherService( 2727): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6602 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2727): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2727): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2727): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6602): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6602): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6602): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6602): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6602): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6602): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6602): MmsConfig.loadFromResources
E/Babel_SMS( 6602): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6602): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6602): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6602): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6602): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6602): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6602): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6602): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6602): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6602): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6602): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6602): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6602): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6602): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6602): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6602): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6602): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6602): found sensor: Motion Accel, handle=46
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 6602): CheckpointMarkThreadRoots callback created = 0xb042d410
,W/Settings( 6602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6602): startup - clean
I/Babel   ( 6602): deleted: false for 0
I/art     ( 6602): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6638 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6602): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6602): Unsupported mime audio/adpcm
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/AudioCapabilities( 6602): Unsupported mime audio/g726
W/AudioCapabilities( 6602): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6602): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6602): Unsupported mime video/mjpg
W/VideoCapabilities( 6602): Unsupported mime video/theora
,W/AudioCapabilities( 6602): Unsupported mime audio/evrc
,W/AudioCapabilities( 6602): Unsupported mime audio/qcelp
W/VideoCapabilities( 6602): Unrecognized profile 2130706433 for video/avc
I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]Clock( 1380): called onTimeUpdated()
I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
,W/AudioCapabilities( 6602): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6602): Unsupported mime audio/qcelp
W/AudioCapabilities( 6602): Unsupported mime audio/evrc
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
W/VideoCapabilities( 6602): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6602): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6602): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6602): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6602): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6602): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6602): onServiceConnected
,W/Babel   ( 6602): Attempted to change video mute state without an active call.
I/NotificationManager( 6602): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6602): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6602): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6602): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6602): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6602): propertyValue:false
D/WeatherService( 2727): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:50:0
D/WeatherService( 2727): 2 : TimeTick Intent And Screen On
D/WeatherService( 2727): 2 : SDK version : 21
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2727): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2727): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2727): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 2727): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/WeatherService( 2727): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2727): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2727): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2727): 2 : Fixed theme : optimus
D/WeatherReflect( 2727): 2 : Map key string is -2
,D/lim     ( 2727): 2 : time = 23:50
I/WeatherReflect( 2727): Model Name : LG-D722
D/WeatherTheme( 2727): 2 : Different view - status_min_formatted : 49 != 50
D/WeatherTheme( 2727): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2727): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2727): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2727): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/Babel   ( 6602): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  853): Killing 6394:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/Weather4x2_optimus( 2727): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2727): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2727): forecast size is 0
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
D/Theme   ( 2727): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2727): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2727): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2727): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2727): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2727): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2727): setTouchIntent, appWidgetId: 2
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_6394/cgroup.procs: No such file or directory
,D/Theme_WeatherAncestor_optimus( 2727): url is : null
D/Theme   ( 2727): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2727): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2727): 2 : update view, appWidgetId: 2
D/WeatherService( 2727): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:50:0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6638): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6638): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6638): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6638): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6638): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6638):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6638):   adb logcat -s GAv4
,W/GAv4    ( 6638): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6638): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6638): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1955): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1955): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/WebViewFactory( 6638): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6638): Time to load native libraries: 2 ms (timestamps 3751-3753)
I/LibraryLoader( 6638): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6638): Binding Chromium to main looper Looper (main, tid 1) {343cb61e}
I/LibraryLoader( 6638): Expected native library version number "",actual native library version number ""
I/chromium( 6638): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6638): Initializing chromium process, singleProcess=true
W/art     ( 6638): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6638): ApplicationContext is null in ApplicationStatus
,W/chromium( 6638): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6638): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6638): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6638): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6638): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6638): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6638): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6638): Remote Branch: 
I/Adreno-EGL( 6638): Local Patches: 
I/Adreno-EGL( 6638): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb39b1ec0, uid 10079
,W/AudioManagerAndroid( 6638): Requires BLUETOOTH permission
I/NSApplication( 6638): Starting up...
I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6701 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6426:com.google.android.music:main/u0a81 (adj 15): empty #11
I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 293us total 25.671ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 391us total 21.750ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.140ms
,W/libprocessgroup(  853): failed to open /acct/uid_10081/pid_6426/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6729 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6491:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_6491/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 6729): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  853): Explicit concurrent mark sweep GC freed 17661(860KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.721ms total 144.848ms
,I/iu.SyncManager( 5480): SYNC; picasa accounts
,D/NetworkLogImpl( 5480): Loaded NetworkSpeedPredictor
I/iu.Environment( 5480): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  853): Killing 6473:com.lge.email/u0a21 (adj 15): empty #11
I/iu.UploadsManager( 5480): num queued entries: 0
,I/iu.UploadsManager( 5480): num updated entries: 0
I/iu.SyncManager( 5480): NEXT; no task
W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_6473/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6760 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6760): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6760): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5317): 
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6760): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6760): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6760): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5317): 
W/ActivityThread( 6760): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6760): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1db09b01: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6760): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6760): GMSCore installation verified
I/ConfigStore( 6760): Config Database version: 1
,I/MediaRouter( 6760): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6760): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6760): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6760): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6792 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6760): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6760): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  853): Killing 6525:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 6792): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6792): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6792): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6525/cgroup.procs: No such file or directory
,I/LGEmail ( 6792): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 6760): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 6792): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6792): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6816 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6792): JNI_OnLoad()
I/HubEmail( 6792): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6792): registerNatives()
I/HubEmail( 6792): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6792): registerNativeMethods()
I/HubEmail( 6792): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6792): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  853): Killing 6549:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_6549/cgroup.procs: No such file or directory
,W/Settings( 6792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6816): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6816): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6816): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6816): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6816): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6816): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6840 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6816): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6816): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6816): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6816): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6816): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  853): Killing 6370:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/CheckinService( 5480): Done disabling old GoogleServicesFramework version
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_6370/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6840): onCreate
,W/AppUp4:DB( 6840):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6840):  setFingerPrint start
I/AppUp4:DB( 6840):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6840):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6840):  SDK version = 0
I/AppUp4:DB( 6840):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6840): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6840): onReceive
I/AppUp4:CustModeStarterReceiver( 6840): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6840): Context : android.app.ReceiverRestrictedContext@2eb6955
D/AppUp4:CustFacade( 6840): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6840): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6840): begin check event
I/AppUp4:CustModeStarterReceiver( 6840): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6840): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6840): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6840): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6840): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  853): Killing 6573:com.lge.drmservice/u0a51 (adj 15): empty #11
I/jxcore-log( 5317): Test app app.js loaded
I/jxcore-log( 5317): 
,W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_6573/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = false
I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6863 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5317): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a473bd7 added. We now have 1 listener(s)
D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
,I/jxcore-log( 5317): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5317): 
,I/chromium( 5317): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PhoneMonitor( 6863): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6863): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6863): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  853): Killing 6602:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6863): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6863): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6863): [parse] Load xml
V/TelephonyAutoProfiling( 6863): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6863): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6863): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_6602/cgroup.procs: No such file or directory
,V/DownloadManager( 3189): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3189): DownloadService onCreate
I/DownloadManager( 3189): in removeSpuriousFiles
I/NotificationManager( 3189): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@255f0c9c on behalf of 3189
I/DownloadManager( 3189): in trimDatabase
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@8261a7a on behalf of 3189
I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6895 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3189): DownloadService onStartCommand
V/DownloadManager( 3189): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@c9e5688 on behalf of 3189
I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058173859 min interval config: 0 actual interval: 30580
,I/CheckinService( 5480): Checking schedule, now: 1455058204447 next: 1455058203825
I/CheckinService( 5480): active receiver: enabled
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/DownloadManager( 3189): DownloadService onDestroy
I/CheckinService( 5480): Preparing to send checkin request
I/EventLogService( 5480): Accumulating logs since 1455058166613
,D/WeatherAncestor( 2727): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:4
,D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/WeatherAncestor( 2727): connectivity changed - connection : true
D/Weather_cast( 2727): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2727): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:4
D/WeatherService( 2727): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6913 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2727): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2727): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2727): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6913): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5480): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5480): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 6913): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6913): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6913): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6913): MmsConfig.loadFromDatabase
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel_SMS( 6913): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6913): MmsConfig.loadFromResources
E/Babel_SMS( 6913): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6913): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6913): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6913): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6913): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6913): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6913): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6913): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6913): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6913): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6913): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6913): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6913): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6913): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6913): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6913): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6913): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6913): found sensor: Motion Accel, handle=46
,W/Settings( 6913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6913): startup - clean
I/Babel   ( 6913): deleted: false for 0
,I/art     ( 6913): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/ActivityManager(  853): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6951 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 6913): CheckpointMarkThreadRoots callback created = 0xb042d480
,W/AudioCapabilities( 6913): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6913): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6913): Unsupported mime audio/g726
W/AudioCapabilities( 6913): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6913): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6913): Unsupported mime video/mjpg
,W/VideoCapabilities( 6913): Unsupported mime video/theora
W/ResourcesManager( 6951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 6913): Unsupported mime audio/evrc
,W/AudioCapabilities( 6913): Unsupported mime audio/qcelp
W/VideoCapabilities( 6913): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6969 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/AudioCapabilities( 6913): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6913): Unsupported mime audio/qcelp
W/AudioCapabilities( 6913): Unsupported mime audio/evrc
W/VideoCapabilities( 6913): Unsupported mime video/mp4v-esdp
,I/MultiDex( 6951): VM with version 2.1.0 has multidex support
I/MultiDex( 6951): install
I/MultiDex( 6951): VM has multidex support, MultiDex support library is disabled.
I/VideoCapabilities( 6913): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6913): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6913): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6913): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6913): Unrecognized profile 2130706433 for video/avc
,V/JNIHelp ( 6951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager( 6969): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/art     (  853): Explicit concurrent mark sweep GC freed 19552(977KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.950ms total 166.460ms
,I/vclib   ( 6913): onServiceConnected
W/Babel   ( 6913): Attempted to change video mute state without an active call.
W/ActivityThread( 6951): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6951): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dea156e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6951): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6951): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6951): com.google.android.gms: cancel(39789) by com.google.android.gms
D/libc-netbsd( 6913): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6913): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6913): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6913): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6913): propertyValue:false
I/NotificationManager( 6913): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Babel   ( 6913): connection state changed from UNKNOWN to CONNECTED
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f461e65:true
I/art     ( 6951): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6951): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  853): Process com.google.android.music:main (pid 6760) has died
D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
,D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6996 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6951): Install completed successfully. count=14 extracted=0
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.853ms
,V/LGMDMManager( 6969): Create singleton instance
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.419ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.559ms
D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
I/AudioManager( 6969): getMode name:com.lge.qremote
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
D/UEI.SmartControl( 6996): Quickset Services start...
,I/UEI.SmartControl( 6996): Manufacture = LGE
D/UEI.SmartControl( 6996): File observer start...
E/UEI.SmartControl( 6996): IR Port is disabled: false
D/UEI.SmartControl( 6996): Starting file observer...
D/UEI.SmartControl( 6996): Extracting JNI libs...
D/UEI.SmartControl( 6996): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7016 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  283): PrepareKeyRequest: nonce=3458778877
D/UEI.SmartControl( 6996): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6996): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6996): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  853): Process com.lge.email (pid 6792) has died
,I/UEI.SmartControl( 6996): --- Selecting new region: 2
I/UEI.SmartControl( 6996): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6996): Platform has CIR...
D/UEI.SmartControl( 6996): NO CIR support, need to check package...
I/UEI.SmartControl( 6996): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6996): QS Service created
E/UEI.SmartControl( 6996): QS start get config
,D/UEI.SmartControl( 6996): Loading JNI Libs...
D/UEI.SmartControl( 6996):  configuring local db...
,I/MusicStore( 7016): Database version: 120
,I/art     ( 6951): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,I/art     ( 6951): CheckpointMarkThreadRoots callback created = 0xb04cbe30
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7016): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7016): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7016): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/UEI.SmartControl( 6996):  ---- Has DB8: true
,D/UEI.SmartControl( 6996): QS start statue = true Error code = 0
D/UEI.SmartControl( 6996): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6996): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/ResourcesManager( 7016): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7016): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6996): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6996): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6996): IrrcClient ++ 
D/irrcClient( 6996): getIrrcService ++ 
D/irrcClient( 6996): getIrrcService -- 
D/irrcClient( 6996): IrrcClient -- 
W/irrc_jni( 6996): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6996): Services init done
,D/UEI.SmartControl( 6996): QS Service init finished
D/UEI.SmartControl( 6996): QS Service version name: 0.1.73
I/UEI.SmartControl( 6996): Device manager: loading config....
D/UEI.SmartControl( 6996): QS Service version code: 1073
D/UEI.SmartControl( 6996): Service requested: Control
D/UEI.SmartControl( 6996): Config is loaded...
V/JNIHelp ( 7016): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 6996):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 6996): Request IControl service: devices are loaded...
I/UEI.SmartControl( 6996): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6996): Internal service binding...
D/UEI.SmartControl( 6996): -----IControl: 11
D/UEI.SmartControl( 6996): Caller: com.lge.qremote
D/UEI.SmartControl( 6996): ------------ IControl registerCallback...
I/UEI.SmartControl( 6996): Registering callback...
D/UEI.SmartControl( 6996): -----IControl: 19
D/UEI.SmartControl( 6996): Caller: com.lge.qremote
I/UEI.SmartControl( 6996): Registering Services Ready callback...
,I/UEI.SmartControl( 6996): Notify client services are ready...
D/UEI.SmartControl( 6996): -----IControl: 8
D/UEI.SmartControl( 6996): Caller: com.lge.qremote
,I/dex2oat ( 7044): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityThread( 7016): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7016): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1db09b01: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7016): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7016): GMSCore installation verified
,I/ConfigStore( 7016): Config Database version: 1
,W/dex2oat ( 7044): Verification of void com.google.ccc.abuse.droidguard.droidguasso.Droidguasso.<init>() took 101.699ms
,I/dex2oat ( 7044): dex2oat took 222.732ms (threads: 4)
,I/Adreno-EGL( 6951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6951): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6951): Remote Branch: 
I/Adreno-EGL( 6951): Local Patches: 
I/Adreno-EGL( 6951): Reconstruct Branch: 
,I/ActivityManager(  853): Process com.lge.appbox.client (pid 6840) has died
,I/MediaRouter( 7016): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7016): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7016): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7016): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7055 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7016): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7016): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7055): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7055): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  853): Killing 6816:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6816/cgroup.procs: No such file or directory
,I/LGEmail ( 7055): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7055): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/NotificationManager( 7016): com.google.android.music: cancel(1061) by com.google.android.music
,I/Adreno-EGL( 6951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6951): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6951): Remote Branch: 
I/Adreno-EGL( 6951): Local Patches: 
I/Adreno-EGL( 6951): Reconstruct Branch: 
,I/Adreno-EGL( 6951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6951): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6951): Remote Branch: 
I/Adreno-EGL( 6951): Local Patches: 
I/Adreno-EGL( 6951): Reconstruct Branch: 
,D/eas_req ( 7055): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7078 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7055): JNI_OnLoad()
,I/HubEmail( 7055): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7055): registerNatives()
I/HubEmail( 7055): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7055): registerNativeMethods()
I/HubEmail( 7055): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7055): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  853): Killing 6863:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/WVCdm   (  283): CdmEngine::OpenSession
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_6863/cgroup.procs: No such file or directory
W/Settings( 7055): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7078): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7078): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7078): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7078): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 7078): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7078): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7078): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7078): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7107 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7078): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7078): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7078): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7078): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7078): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7078): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  853): Killing 6895:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7107): onCreate
,W/AppUp4:DB( 7107):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7107):  setFingerPrint start
I/AppUp4:DB( 7107):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7107):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7107):  SDK version = 0
,I/AppUp4:DB( 7107):  beforefinger == newfinger no write in DB
W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_6895/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7107): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7107): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7107): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7107): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7107): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7107): onReceive
I/AppUp4:CustModeStarterReceiver( 7107): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7107): Context : android.app.ReceiverRestrictedContext@2eb6955
D/AppUp4:CustFacade( 7107): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7107): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7107): begin check event
I/AppUp4:CustModeStarterReceiver( 7107): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7107): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7107): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7107): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7107): handleAsyncCustNotification do not startCustService
I/ActivityManager(  853): Killing 6913:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_6913/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = true
D/PhoneState( 3160): setPdpRejectCasuse : false
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7126 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=958180829
D/PhoneMonitor( 7126): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7126): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7126): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  853): Killing 6638:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 7126): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7126): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7126): [parse] Load xml
,V/TelephonyAutoProfiling( 7126): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7126): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7126): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
E/libprocessgroup(  853): failed to kill 1 processes for processgroup 6638
,V/DownloadManager( 3189): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058173859 min interval config: 0 actual interval: 34677
,V/DownloadManager( 3189): DownloadService onCreate
I/NotificationManager( 3189): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7151 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/DownloadManager( 3189): in removeSpuriousFiles
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3189): DownloadService onStartCommand
V/DownloadManager( 3189): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@31065334 on behalf of 3189
I/DownloadManager( 3189): in trimDatabase
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@1b43755d on behalf of 3189
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@c697ed2 on behalf of 3189
,I/ActivityManager(  853): Killing 6701:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_6701/cgroup.procs: No such file or directory
D/WeatherAncestor( 2727): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:8
,D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/WeatherAncestor( 2727): connectivity changed - connection : true
D/Weather_cast( 2727): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2727): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:8
D/WeatherService( 2727): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7179 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
V/DownloadManager( 3189): DownloadService onDestroy
D/Weather.Utils( 2727): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2727): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2727): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7179): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7179): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7179): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7179): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7179): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7179): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7179): MmsConfig.loadFromResources
E/Babel_SMS( 7179): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7179): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7179): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7179): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7179): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7179): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7179): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7179): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7179): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7179): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7179): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7179): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7179): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7179): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7179): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7179): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7179): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7179): found sensor: Motion Accel, handle=46
,W/Settings( 7179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7179): startup - clean
I/art     ( 7179): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/Babel   ( 7179): deleted: false for 0
,I/art     ( 7179): CheckpointMarkThreadRoots callback created = 0xb042d490
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{338b1967 type 0 when 1455058203825 com.google.android.gms} when 1455058203825
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7213 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7219 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{65f77bd type 0 when 1455058207280 com.android.vending} when 1455058207280
,W/AudioCapabilities( 7179): Unsupported mime audio/x-lg-flac
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/AudioCapabilities( 7179): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7179): Unsupported mime audio/g726
W/AudioCapabilities( 7179): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7179): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7179): Unsupported mime video/mjpg
W/VideoCapabilities( 7179): Unsupported mime video/theora
W/AudioCapabilities( 7179): Unsupported mime audio/evrc
,W/AudioCapabilities( 7179): Unsupported mime audio/qcelp
W/VideoCapabilities( 7179): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7179): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7179): Unsupported mime audio/qcelp
W/AudioCapabilities( 7179): Unsupported mime audio/evrc
,W/VideoCapabilities( 7179): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7179): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7179): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7179): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7179): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7179): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7179): onServiceConnected
W/Babel   ( 7179): Attempted to change video mute state without an active call.
I/NotificationManager( 7179): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7179): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7179): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7179): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7179): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7213): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/System.out( 7179): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7213): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,D/Finsky  ( 7219): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/ContextImpl( 7213): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7213): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7213):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7213):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7213): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7179): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 7213): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7213): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7213): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Finsky  ( 7219): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7219): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7219): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7219): com.android.vending: cancel(-1050172287) by com.android.vending
,I/art     ( 6340): Explicit concurrent mark sweep GC freed 2023(87KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 401us total 29.539ms
,D/Ads     ( 7219): Skipping gmscore version check
,D/Finsky  ( 7219): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7219): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@64f6ea0 on behalf of 7219
D/Finsky  ( 7219): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7219): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WebViewFactory( 7213): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  853): Process com.google.android.music:main (pid 7016) has died
,I/art     (  853): Explicit concurrent mark sweep GC freed 21026(981KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.683ms total 157.793ms
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/LibraryLoader( 7213): Time to load native libraries: 2 ms (timestamps 3303-3305)
I/LibraryLoader( 7213): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7213): Binding Chromium to main looper Looper (main, tid 1) {343cb61e}
,I/LibraryLoader( 7213): Expected native library version number "",actual native library version number ""
I/chromium( 7213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7213): Initializing chromium process, singleProcess=true
,W/art     ( 7213): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7213): ApplicationContext is null in ApplicationStatus
W/chromium( 7213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7213): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7213): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7213): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7213): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7213): Remote Branch: 
I/Adreno-EGL( 7213): Local Patches: 
I/Adreno-EGL( 7213): Reconstruct Branch: 
D/Finsky  ( 7219): [945] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7219): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,V/AudioPolicyService(  283): registerClient() client 0xb3a46f60, uid 10079
,W/AudioManagerAndroid( 7213): Requires BLUETOOTH permission
I/NSApplication( 7213): Starting up...
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7317 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6969:com.lge.qremote/u0a106 (adj 15): empty #11
,I/ActivityManager(  853): Killing 6729:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_6969/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_6729/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7344 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6996:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 27.127ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.914ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.676ms
,W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_6996/cgroup.procs: No such file or directory
,W/ResourcesManager( 7344): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Killing 7055:com.lge.email/u0a21 (adj 15): empty #11
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 114377770742; DSPS: 3846705; Offset : -3016478785
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7369 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/libprocessgroup(  853): failed to open /acct/uid_10021/pid_7055/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/CheckinRequestBuilder( 5480): Classify the device as Phone.
,I/DigitalAppWidgetProvider( 7369): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  853): Killing 7078:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7078/cgroup.procs: No such file or directory
D/WeatherAncestor( 2727): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:50:11
,D/UpdateThreadPoolManager( 2727): 2 : This is isUpdating : false
D/Weather_cast( 2727): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2727): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:50:11
D/WeatherService( 2727): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  853): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7388 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2727): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2727): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2727): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5480): propertyValue:false
W/ResourcesManager( 7388): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7388): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1ccd63e3
,D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CalendarProvider2( 7388): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7388): Created com.android.providers.calendar.CalendarAlarmManager@21763c0c(com.android.providers.calendar.CalendarProvider2@1ccd63e3)
D/CalendarProviderBroadcastReceiver( 7388): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7388): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7388): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7388): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7388): [getOrCreateCalendarAlarmManager]
D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7409 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/CheckinTask( 5480): Sending checkin request (9813 bytes)
,D/CalendarProvider2( 7388): [IntentService] Release Lock
D/CalendarProvider2( 7388): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  853): Killing 7107:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 7409): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_7107/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15bf7be6:true
,D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
D/BluetoothAdapterService(122752248)( 2084): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11d780e
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7437 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7409): Create singleton instance
,D/UEI.SmartControl( 7437): Quickset Services start...
,I/UEI.SmartControl( 7437): Manufacture = LGE
I/AudioManager( 7409): getMode name:com.lge.qremote
D/UEI.SmartControl( 7437): File observer start...
E/UEI.SmartControl( 7437): IR Port is disabled: false
D/UEI.SmartControl( 7437): Starting file observer...
D/UEI.SmartControl( 7437): Extracting JNI libs...
D/UEI.SmartControl( 7437): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7409): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7437): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7437): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7437): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/CheckinRequestBuilder( 5480): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5480): Failed to find provider info for com.google.android.wearable.settings
I/UEI.SmartControl( 7437): --- Selecting new region: 2
I/UEI.SmartControl( 7437): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7437): Platform has CIR...
D/UEI.SmartControl( 7437): NO CIR support, need to check package...
I/UEI.SmartControl( 7437): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7437): QS Service created
I/MusicWidget( 2683): mDelayedStopHandler : unbind
,E/UEI.SmartControl( 7437): QS start get config
,I/MusicBrowser( 2749): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2749): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2749): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
,D/MusicBrowser( 2749): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2749): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/UEI.SmartControl( 7437): Loading JNI Libs...
D/UEI.SmartControl( 7437):  configuring local db...
,I/ActivityManager(  853): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7463 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicBrowser( 2749): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  853):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@119da428com.lge.music.MediaPlaybackService$6@27134541
D/MusicBrowser( 2749): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@f4645d1
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2749): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2749): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
,I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2749): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2749): reset
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/MediaPlayer[Native]( 2749): setListener
,V/MediaPlayer[Native]( 2749): disconnect
V/MediaPlayer[Native]( 2749): destructor
V/AudioFlinger(  283): releasing 19 from 2749 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2749): disconnect
D/MusicBrowser( 2749): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2749): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2749): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2749): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2749): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
,V/MusicBrowser( 2749): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2749): [SmartShareManagerClient] unregisterListener: 328497894
W/SmartShareClient( 2749): [SmartShareManagerClient] unregisterListener invalid listener: 328497894
I/SmartShareClient( 2749): [SmartShareManagerClient] terminate service: 2749/MediaPlaybackService/99113791
E/HomeCloudIF( 2749): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2749): [SmartShareManagerClient] unbindService context:android.app.Application@78e9827
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/CloudHub( 2749): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2749): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2749): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2749): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2749): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  853): Killing 7126:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/CloudHub( 2749): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
,D/UEI.SmartControl( 7437):  ---- Has DB8: true
,D/UEI.SmartControl( 7437): QS start statue = true Error code = 0
D/UEI.SmartControl( 7437): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7437): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7126/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7437): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7437): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7437): IrrcClient ++ 
D/irrcClient( 7437): getIrrcService ++ 
D/irrcClient( 7437): getIrrcService -- 
D/irrcClient( 7437): IrrcClient -- 
W/irrc_jni( 7437): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7437): Services init done
I/UEI.SmartControl( 7437): Device manager: loading config....
D/UEI.SmartControl( 7437): QS Service init finished
D/UEI.SmartControl( 7437): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7437): Config is loaded...
I/CheckinRequestBuilder( 5480): Classify the device as Phone.
I/CheckinTask( 5480): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5480): Checking schedule, now: 1455058212706 next: 1455585461701
I/CheckinService( 5480): active receiver: disabled
D/UEI.SmartControl( 7437): QS Service version code: 1073
,D/UEI.SmartControl( 7437): Service requested: Control
D/UEI.SmartControl( 7437): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7437): Internal service binding...
D/UEI.SmartControl( 7437): -----IControl: 11
,D/UEI.SmartControl( 7437): Caller: com.lge.qremote
D/UEI.SmartControl( 7437): ------------ IControl registerCallback...
I/UEI.SmartControl( 7437): Registering callback...
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 7437): -----IControl: 19
D/UEI.SmartControl( 7437): Caller: com.lge.qremote
I/UEI.SmartControl( 7437): Registering Services Ready callback...
I/UEI.SmartControl( 7437): Notify client services are ready...
I/CheckinService( 5480): Checking schedule, now: 1455058212839 next: 1455585461701
I/CheckinService( 5480): active receiver: disabled
,D/UEI.SmartControl( 7437): -----IControl: 8
D/UEI.SmartControl( 7437): Caller: com.lge.qremote
I/ActivityManager(  853): Killing 7213:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/CheckinService( 5480): Recording last checkin time for package unspecified as 1455058212852
,D/UEI.SmartControl( 7437):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7437): Notify AllClients services are ready: 0
I/ActivityManager(  853): Killing 7151:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  853): failed to open /acct/uid_10079/pid_7213/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_7151/cgroup.procs: No such file or directory
I/ActivityManager(  853): Killing 7219:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10036/pid_7219/cgroup.procs: No such file or directory
,I/Gmail   ( 7463): getAccountsCursor
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7463): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  853): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 7463): Observing account changes for notifications
,W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  853): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  853): Killing 7317:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_7317/cgroup.procs: No such file or directory
,E/Gmail   ( 7463): Error finding the version of the Email provider.....
E/Gmail   ( 7463): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7463): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7463): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7463): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7463): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7463): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7463): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7463): We do not support migrating this version of the Email provider.
I/Gmail   ( 7463): getAccountsCursor
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 1789): callingUid 10006, callindPid: 1789
,D/AuthorizationBluetoothService( 1789): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1789): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5480): Restart initialization of location
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  853): Killing 7344:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/NotificationManager( 1789): com.google.android.gms: cancel(0) by com.google.android.gms
W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_7344/cgroup.procs: No such file or directory
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7527 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1789): No location to return for getLastLocation()
W/FusedLocationProvider( 1789): location=null
,I/Gmail   ( 7463): notifyAccountChanged
,I/Gmail   ( 7463): getAccountsCursor
I/Gmail   ( 7463): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7463): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7463): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7463): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     (  853): Explicit concurrent mark sweep GC freed 18884(906KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.400ms total 157.483ms
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7463): getAccountsCursor
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7527): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7527): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7527): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7527): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7527): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 7527): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7527): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7527): Skipping gmscore version check
,V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@13470a59 on behalf of 7527
D/Finsky  ( 7527): [988] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7577 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7527): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/NotificationManager(  853): android: cancelAsUser(2) by android
,D/Finsky  ( 7527): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/libc-netbsd( 7527): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7527): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7527): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7527): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 7577): Register our PhoneStateListener
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7527): propertyValue:false
D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/LocationInitializer( 5480): Restart initialization of location
E/MDM     ( 1789): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/PhoneMonitor( 7577): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7577): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7577): [parse] Load xml
D/AuthorizationBluetoothService( 1789): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/TelephonyAutoProfiling( 7577): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7577): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1789): com.google.android.gms: cancel(0) by com.google.android.gms
D/PhoneMonitor( 7577): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/GCoreFlp( 1789): No location to return for getLastLocation()
,W/FusedLocationProvider( 1789): location=null
I/AudioManager( 7409): getMode name:com.lge.qremote
I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058212852 min interval config: 0 actual interval: 1538
,I/AudioManager( 7409): getMode name:com.lge.qremote
,I/CheckinService( 5480): Checking schedule, now: 1455058214406 next: 1455058242701
I/CheckinService( 5480): active receiver: disabled
I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058212852 min interval config: 0 actual interval: 1563
I/AudioManager( 7409): getMode name:com.lge.qremote
,I/CheckinService( 5480): Checking schedule, now: 1455058214435 next: 1455058242701
I/CheckinService( 5480): active receiver: disabled
I/AudioManager( 7409): getMode name:com.lge.qremote
,W/ContextImpl( 3542): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/SetupWizard( 7577): Connected to Gservices successfully
I/[SystemUI]QPairHandler( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/QCNEJ   ( 1917): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1380): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/AudioManager( 7409): getMode name:com.lge.qremote
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AudioManager( 7409): getMode name:com.lge.qremote
,I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/administrator(  853): Handling package changes for user 0
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7634 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7179): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7179): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7179): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 7634): onCreate
,W/AppUp4:DB( 7634):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7634):  setFingerPrint start
,I/AppUp4:DB( 7634):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
V/JNIHelp ( 7179): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 7634):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7634):  SDK version = 0
I/AppUp4:DB( 7634):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7634): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7634): onReceive
I/AppUp4:CustModeStarterReceiver( 7634): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7634): Context : android.app.ReceiverRestrictedContext@1f6d7b5e
D/AppUp4:CustFacade( 7634): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7634): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7634): begin check event
I/AppUp4:CustModeStarterReceiver( 7634): Event For Nothing, skip.
W/System  ( 7179): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7179): Installed default security provider GmsCore_OpenSSL
I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7655 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  853): Process com.android.vending (pid 7527) has died
,W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2e535908
,D/LCardEmulationManager( 1864): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1864): getDefaultRoute
W/ResourcesManager( 7655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7655): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7655): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7655): Total System Memory = 906309632
I/GalleryUtils( 7655): Application Heap = 96 MB
I/AppConfig( 7655): App Tier : NOT_DEF
,D/SystemHelper( 7655): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7676 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1789): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/LocationProviderProxy(  853): applying state to connected service
W/ResourcesManager( 7676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7676): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7676): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7676): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7676): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7676): BUILD Country: EU
I/SystemConfig( 7676): BUILD Operator: OPEN
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7699 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7369:com.lge.clock/u0a10 (adj 15): empty #11
I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.230ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.426ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.903ms
,W/libprocessgroup(  853): failed to open /acct/uid_10010/pid_7369/cgroup.procs: No such file or directory
I/SystemConfig( 7676): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7676): existFile = false
I/SystemConfig( 7676): canReadFile = false
I/SystemConfig( 7676): systemFeature RCS result false
D/SystemConfig( 7676): refreshRcsSupport() :false
I/LockScreenSettings( 7699): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7699): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7699): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7699): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7699): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7699): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7716 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7388:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_7388/cgroup.procs: No such file or directory
,W/ResourcesManager( 7716): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 2037): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7741 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 2037): UpdateCorporaTask done [took 66 ms] updated apps [took 65 ms] 
I/ActivityManager(  853): Killing 2749:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  283): 2749 died, releasing its sessions
V/AudioFlinger(  283):  pid 1817 @ 0
V/AudioFlinger(  283):  pid 3160 @ 1
V/AudioFlinger(  283):  pid 3160 @ 2
,W/libprocessgroup(  853): failed to open /acct/uid_10028/pid_2749/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  853): Killing 7577:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7577/cgroup.procs: No such file or directory
,D/Finsky  ( 7741): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  853): Explicit concurrent mark sweep GC freed 29949(1467KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.514ms total 178.434ms
,D/Finsky  ( 7741): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7741): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7741): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7741): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@343cb61e on behalf of 7741
D/Finsky  ( 7741): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7741): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7741): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7741): Skipping gmscore version check
D/PackageBroadcastService( 5480): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5480): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5480): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7741): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  853): Killing 7437:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7409): android.os.DeadObjectException
,W/System.err( 7409): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7409): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7409): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7409): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7409): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7409): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7409): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7409): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7409): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7409): android.os.DeadObjectException
W/System.err( 7409): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7409): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7409): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7409): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7409): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7409): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7409): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7409): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7409): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_7437/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7790 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7790): Quickset Services start...
,I/UEI.SmartControl( 7790): Manufacture = LGE
,D/UEI.SmartControl( 7790): File observer start...
E/UEI.SmartControl( 7790): IR Port is disabled: false
D/UEI.SmartControl( 7790): Starting file observer...
D/UEI.SmartControl( 7790): Extracting JNI libs...
D/UEI.SmartControl( 7790): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7790): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7790): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7790): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7790): --- Selecting new region: 2
,I/UEI.SmartControl( 7790): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7790): Platform has CIR...
D/UEI.SmartControl( 7790): NO CIR support, need to check package...
I/UEI.SmartControl( 7790): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7790): QS Service created
E/UEI.SmartControl( 7790): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7790): Loading JNI Libs...
,D/UEI.SmartControl( 7790):  configuring local db...
D/UEI.SmartControl( 7790):  ---- Has DB8: true
,D/UEI.SmartControl( 7790): QS start statue = true Error code = 0
D/UEI.SmartControl( 7790): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7790): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7790): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7790): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7790): IrrcClient ++ 
D/irrcClient( 7790): getIrrcService ++ 
,D/irrcClient( 7790): getIrrcService -- 
D/irrcClient( 7790): IrrcClient -- 
W/irrc_jni( 7790): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7790): Services init done
I/UEI.SmartControl( 7790): Device manager: loading config....
D/UEI.SmartControl( 7790): QS Service init finished
D/UEI.SmartControl( 7790): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7790): QS Service version code: 1073
D/UEI.SmartControl( 7790): Config is loaded...
D/UEI.SmartControl( 7790): Service requested: Control
I/ActivityManager(  853): Killing 7463:com.google.android.gm/u0a53 (adj 15): empty #11
D/UEI.SmartControl( 7790): -----IControl: 11
D/UEI.SmartControl( 7790): Caller: com.lge.qremote
D/UEI.SmartControl( 7790): ------------ IControl registerCallback...
I/UEI.SmartControl( 7790): Registering callback...
D/UEI.SmartControl( 7790): -----IControl: 19
D/UEI.SmartControl( 7790): Caller: com.lge.qremote
I/UEI.SmartControl( 7790): Registering Services Ready callback...
,D/UEI.SmartControl( 7790):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7790): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7790): -----IControl: 8
D/UEI.SmartControl( 7790): Caller: com.lge.qremote
D/UEI.SmartControl( 7790): Internal service binding...
,W/libprocessgroup(  853): failed to open /acct/uid_10053/pid_7463/cgroup.procs: No such file or directory
I/AudioManager( 7409): getMode name:com.lge.qremote
,I/AudioManager( 7409): getMode name:com.lge.qremote
,I/AudioManager( 7409): getMode name:com.lge.qremote
,I/Icing   ( 5480): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5480): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  853): Killing 7634:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_7634/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Killing 7179:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_7179/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7790): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1881): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
,I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 302, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/charger_monitor(  470): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
D/WifiController(  853): battery changed pluggedType: 2
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 134378588807; DSPS: 4502091; Offset : -3016453942
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{12f5329 type 2 when 145570 com.google.android.gms} when 145570
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{273316ae type 0 when 1455058242701 com.google.android.gms} when 1455058242701
I/CheckinService( 5480): Checkin interval check for package: unspecified last checkin: 1455058212852 min interval config: 0 actual interval: 29954
,I/CheckinService( 5480): Checking schedule, now: 1455058242834 next: 1455058242701
,I/CheckinService( 5480): active receiver: enabled
,I/CheckinService( 5480): Preparing to send checkin request
I/EventLogService( 5480): Accumulating logs since 1455058204652
,I/CheckinRequestBuilder( 5480): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5480): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1789): Explicit concurrent mark sweep GC freed 34267(2MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 13MB/22MB, paused 1.062ms total 99.290ms
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1789): Vacuum at: now=1455058243077 tag=VacuumService
,D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=1346199403
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Adreno-EGL( 6951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6951): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6951): Remote Branch: 
I/Adreno-EGL( 6951): Local Patches: 
I/Adreno-EGL( 6951): Reconstruct Branch: 
,I/Adreno-EGL( 6951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6951): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6951): Remote Branch: 
I/Adreno-EGL( 6951): Local Patches: 
I/Adreno-EGL( 6951): Reconstruct Branch: 
,I/Adreno-EGL( 6951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6951): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6951): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6951): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6951): Remote Branch: 
I/Adreno-EGL( 6951): Local Patches: 
I/Adreno-EGL( 6951): Reconstruct Branch: 
,I/WVCdm   (  283): CdmEngine::OpenSession
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27686 ms ago)
,D/qdlights(  853): set_light_backlight: 252
,D/qdlights(  853): set_light_backlight: 249
D/qdlights(  853): set_light_backlight: 245
,D/qdlights(  853): set_light_backlight: 242
,D/qdlights(  853): set_light_backlight: 239
,D/qdlights(  853): set_light_backlight: 235
,D/qdlights(  853): set_light_backlight: 232
,D/qdlights(  853): set_light_backlight: 229
,D/qdlights(  853): set_light_backlight: 225
,D/qdlights(  853): set_light_backlight: 222
,D/qdlights(  853): set_light_backlight: 219
,D/qdlights(  853): set_light_backlight: 215
,D/qdlights(  853): set_light_backlight: 212
,D/qdlights(  853): set_light_backlight: 209
,D/qdlights(  853): set_light_backlight: 205
,D/qdlights(  853): set_light_backlight: 202
,D/qdlights(  853): set_light_backlight: 199
,D/qdlights(  853): set_light_backlight: 195
,D/qdlights(  853): set_light_backlight: 192
,D/qdlights(  853): set_light_backlight: 189
,D/qdlights(  853): set_light_backlight: 185
,D/qdlights(  853): set_light_backlight: 182
,D/qdlights(  853): set_light_backlight: 179
,D/qdlights(  853): set_light_backlight: 175
,D/qdlights(  853): set_light_backlight: 172
,D/qdlights(  853): set_light_backlight: 169
,D/qdlights(  853): set_light_backlight: 165
,D/qdlights(  853): set_light_backlight: 162
,D/qdlights(  853): set_light_backlight: 159
,D/qdlights(  853): set_light_backlight: 155
,D/qdlights(  853): set_light_backlight: 152
,D/qdlights(  853): set_light_backlight: 149
,D/qdlights(  853): set_light_backlight: 145
,I/WVCdm   (  283): CdmEngine::CloseSession
,D/qdlights(  853): set_light_backlight: 142
D/qdlights(  853): set_light_backlight: 139
,D/qdlights(  853): set_light_backlight: 135
,D/qdlights(  853): set_light_backlight: 132
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=1943535952
,D/qdlights(  853): set_light_backlight: 129
D/qdlights(  853): set_light_backlight: 125
,D/qdlights(  853): set_light_backlight: 122
,D/qdlights(  853): set_light_backlight: 119
,D/qdlights(  853): set_light_backlight: 115
,D/qdlights(  853): set_light_backlight: 112
,D/qdlights(  853): set_light_backlight: 109
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/qdlights(  853): set_light_backlight: 105
D/qdlights(  853): set_light_backlight: 102
,D/qdlights(  853): set_light_backlight: 99
,D/qdlights(  853): set_light_backlight: 95
,D/qdlights(  853): set_light_backlight: 92
,D/qdlights(  853): set_light_backlight: 89
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  853): set_light_backlight: 85
,D/qdlights(  853): set_light_backlight: 82
,D/qdlights(  853): set_light_backlight: 79
,D/qdlights(  853): set_light_backlight: 75
,D/qdlights(  853): set_light_backlight: 72
,D/qdlights(  853): set_light_backlight: 69
,D/qdlights(  853): set_light_backlight: 65
,D/qdlights(  853): set_light_backlight: 62
,D/qdlights(  853): set_light_backlight: 59
,D/qdlights(  853): set_light_backlight: 55
,D/qdlights(  853): set_light_backlight: 52
,D/qdlights(  853): set_light_backlight: 49
,D/qdlights(  853): set_light_backlight: 45
,D/qdlights(  853): set_light_backlight: 42
,D/qdlights(  853): set_light_backlight: 39
,D/qdlights(  853): set_light_backlight: 35
,D/qdlights(  853): set_light_backlight: 32
,D/qdlights(  853): set_light_backlight: 29
,D/qdlights(  853): set_light_backlight: 25
,D/qdlights(  853): set_light_backlight: 22
,D/qdlights(  853): set_light_backlight: 19
,D/qdlights(  853): set_light_backlight: 15
,D/qdlights(  853): set_light_backlight: 12
,D/qdlights(  853): set_light_backlight: 10
,I/WVCdm   (  283): CdmEngine::CloseSession
I/WVCdm   (  283): L3 Terminate.
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5480): Classify the device as Phone.
,D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5480): propertyValue:false
D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5480): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5480): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5480): Sending checkin request (9816 bytes)
,I/CheckinRequestBuilder( 5480): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5480): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5480): Classify the device as Phone.
,I/CheckinTask( 5480): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5480): Checking schedule, now: 1455058249142 next: 1455585498136
I/CheckinService( 5480): active receiver: disabled
,D/CheckinService( 5480): Recording last checkin time for package unspecified as 1455058249166
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7870 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7870): Register our PhoneStateListener
,V/SetupWizard( 7870): Connected to Gservices successfully
,I/ActivityManager(  853): Killing 7655:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 7870): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7870): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7870): [parse] Load xml
V/TelephonyAutoProfiling( 7870): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7870): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7870): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_7655/cgroup.procs: No such file or directory
D/GCM     ( 1789): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 154379186039; DSPS: 5157471; Offset : -3016467140
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34680 ms ago)
I/PowerManagerService(  853): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34692 ms ago)
W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  853): Sleeping (uid 1000)...
D/LPWGController(  853): [updateScreenState] screen on = false
D/LPWGController(  853): disable proximity sensor
D/LPWGController(  853): enable proximity sensor
I/SensorManager(  853): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2da006e6] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  853): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
,I/sensors_hal_Ctx(  853): activate: handle is 48, enable
V/sensors_hal_Ctx(  853): activate sensors is 1400000000000
D/sensors_hal_Thresh(  853): enable: handle=48
I/sensors_hal_SAM(  853): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  853): waitForResponse: timeout=1000
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  853): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  853): enable: Received response: 0
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34732 ms ago)
I/Adreno-EGL(  853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  853): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  853): Build Date: 03/02/15 Mon
I/Adreno-EGL(  853): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  853): Remote Branch: 
I/Adreno-EGL(  853): Local Patches: 
I/Adreno-EGL(  853): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1043 us)
,I/Sensors (  437): sns_pwr.c(273):acquiring wakelock
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
,I/sensors_hal_Ctx(  853): activate: handle is 46, disable
V/sensors_hal_Ctx(  853): activate sensors is 1000000000000
D/sensors_hal_LP2(  853): enable: handle=46
D/sensors_hal_LP2(  853): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  853): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  853): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  853): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  853): Display changed displayId=0
,D/DSDPConnection( 1817): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  853): Excessive delay in setPowerMode(): 194ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  853): Got set_interactive hint
,D/KeyguardViewMediator( 1380): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1337): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1337): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1337): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1380): notifyScreenOffLocked
,D/WifiServerServiceExt(  853): sendKtScanInterval  mRtspPlay : false
,D/KeyguardViewMediator( 1380): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1380): handleNotifyScreenOff
I/WifiServerServiceExt(  853): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 853
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
,V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/ScreenTurnOffBySensor( 1380): unregisterProximitySensor
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/StatusBarWindowView( 1380): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.SCREEN_ON
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/SplitWindow(  853): check instance of lgWin Window{c87f07d u0 SearchPanel}
,I/QCNEJ   ( 1917): |CORE| sendScreenState: state:true
I/LEDService( 1881): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1881): stopPatternFlashing()
D/qdlights( 1881): set_light_notifications: 0,0,0,0,3
I/LEDService( 1881): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1881): set_light_notifications: 0,0,0,0,3
D/InputDispatcher(  853): Window went away: Window{3e28fcfb u0 SearchPanel}
I/LEDService( 1881): updateLightsLocked : turn off led
D/qdlights( 1881): set_light_notifications: 0,0,0,0,3
I/[SystemUI]Clock( 1380): onReceive = android.intent.action.SCREEN_ON
D/LEDHandler( 1881): RESTART MSG
I/LgeClockWidgetControlView( 1380): time changed, timezoneChanged : false
,I/Cliptray Service( 1881): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1881): lockStatus = 0
D/LNfcService( 1864): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1864): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1864): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1864): isRequireNfcCRouting() return true
D/LNfcService( 1864): isHCERoutingtoHost() return : true
D/NfcService( 1864): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1864): mEnableLPD: true
D/NfcService( 1864): mEnableReader: false
D/NfcService( 1864): mEnableHostRouting: true
D/NfcService( 1864): newParams.techmask= mTechMask: default
D/NfcService( 1864): mEnableLPD: true
D/NfcService( 1864): mEnableReader: false
D/NfcService( 1864): mEnableHostRouting: true
D/NfcService( 1864): screenState= 3
D/NfcService( 1864): Discovery configuration equal, not updating.
D/Ulp_jni (  853): JNI:system_update. Event-0
,V/PhoneApp( 1817): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2727): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:50:52
,I/[SystemUI]QPairHandler( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
,D/WeatherService( 2727): 2 : ACTION screen on
I/QCNEJ   ( 1917): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,D/WeatherService( 2727): 2 : shouldTimeTickRegistered : false
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/Weather_cast( 2727): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2727): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:50:52
,D/administrator(  853): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7914 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1380): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager( 7914): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_ON
V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3f73e794
,D/AppCleanupService( 3969): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 853
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  853): CMD_SCREEN_OFF 
D/WifiController(  853): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.SCREEN_OFF
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1789): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/art     (  853): Explicit concurrent mark sweep GC freed 47025(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 5.268ms total 213.662ms
,I/QCNEJ   ( 1917): |CORE| sendScreenState: state:false
I/LEDService( 1881): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1881): stopPatternFlashing()
D/qdlights( 1881): set_light_notifications: 0,0,0,0,3
I/LEDService( 1881): getCurrentHighestLGLedRecord : size = 1
D/VolumeVibrator( 1881): clear
D/qdlights( 1881): set_light_notifications: 0,0,0,0,3
I/LEDService( 1881): updateLightsLocked : turn on led
E/LEDService( 1881): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1881): Can't handle this request of patternId:0
D/LEDHandler( 1881): RESTART MSG
I/Cliptray Service( 1881): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LocationProviderProxy(  853): applying state to connected service
I/Sensors (  437): sns_pwr.c(301):releasing wakelock
,D/LCardEmulationManager( 1864): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1864): getDefaultRoute
D/LNfcService( 1864): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1864): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1955): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1817): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2727): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:50:53
D/WeatherService( 2727): 2 : ACTION screen off
D/WeatherService( 2727): 2 : TimeTick Receiver Unregister
D/WeatherService( 2727): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:50:53
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_OFF
D/AppCleanupService( 3969): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3969): AppUsageStatsSaveTask
I/Babel_SMS( 7914): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7914): MmsConfig.loadMmsSettings
E/NxpNfcJni( 1864): getReconnectState = 0x0
,D/LCardEmulationManager( 1864): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1864): getDefaultRoute
D/LNfcService( 1864): isRequireNfcCRouting() return true
D/LNfcService( 1864): isHCERoutingtoHost() return : true
D/NfcService( 1864): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1864): mEnableLPD: true
D/NfcService( 1864): mEnableReader: false
D/NfcService( 1864): mEnableHostRouting: true
D/NfcService( 1864): newParams.techmask= mTechMask: 0
D/NfcService( 1864): mEnableLPD: true
D/NfcService( 1864): mEnableReader: false
D/NfcService( 1864): mEnableHostRouting: true
D/NfcService( 1864): screenState= 1
I/Babel_SMS( 7914): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7914): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7914): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7914): MmsConfig.loadFromResources
E/Babel_SMS( 7914): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7914): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7914): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7914): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 7914): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7914): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7914): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7914): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7914): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7914): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7914): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7914): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7914): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7914): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7914): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7914): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7914): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7914): found sensor: Motion Accel, handle=46
E/NxpNfcJni( 1864): getReconnectState = 0x0
W/Settings( 7914): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7914): startup - clean
,I/art     ( 7914): CheckpointMarkThreadRoots callback created = 0xaaf39ca0
,I/Babel   ( 7914): deleted: false for 0
,I/art     ( 7914): CheckpointMarkThreadRoots callback created = 0xaaf39c80
,W/AudioCapabilities( 7914): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7914): Unsupported mime audio/adpcm
W/AudioCapabilities( 7914): Unsupported mime audio/g726
W/AudioCapabilities( 7914): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7914): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7914): Unsupported mime video/mjpg
W/VideoCapabilities( 7914): Unsupported mime video/theora
W/AudioCapabilities( 7914): Unsupported mime audio/evrc
W/AudioCapabilities( 7914): Unsupported mime audio/qcelp
W/VideoCapabilities( 7914): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7958 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 7914): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7914): Unsupported mime audio/qcelp
W/AudioCapabilities( 7914): Unsupported mime audio/evrc
W/VideoCapabilities( 7914): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7914): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7914): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7914): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 7958): onCreate
W/AppUp4:DB( 7958):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 7914): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7914): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 7958):  setFingerPrint start
I/AppUp4:DB( 7958):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7958):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7958):  SDK version = 0
I/AppUp4:DB( 7958):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7958): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7958): onReceive
I/AppUp4:CustModeStarterReceiver( 7958): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7958): Context : android.app.ReceiverRestrictedContext@1f6d7b5e
D/AppUp4:CustFacade( 7958): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7958): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7958): begin check event
I/AppUp4:CustModeStarterReceiver( 7958): Event For Nothing, skip.
I/ActivityManager(  853): Killing 7676:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10018/pid_7676/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7984 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7914): onServiceConnected
W/Babel   ( 7914): Attempted to change video mute state without an active call.
I/NotificationManager( 7914): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7914): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7914): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7984): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7984): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7984): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7914): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 7984): Total System Memory = 906309632
,I/GalleryUtils( 7984): Application Heap = 96 MB
I/AppConfig( 7984): App Tier : NOT_DEF
W/System  ( 7914): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7914): Installed default security provider GmsCore_OpenSSL
D/SystemHelper( 7984): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationManager( 7914): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8006 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7699:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_7699/cgroup.procs: No such file or directory
,W/ResourcesManager( 8006): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8006): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8006): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 8006): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 8006): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 8006): BUILD Country: EU
I/SystemConfig( 8006): BUILD Operator: OPEN
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8025 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7716:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_7716/cgroup.procs: No such file or directory
,I/SystemConfig( 8006): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8006): existFile = false
I/SystemConfig( 8006): canReadFile = false
I/SystemConfig( 8006): systemFeature RCS result false
D/SystemConfig( 8006): refreshRcsSupport() :false
I/LockScreenSettings( 8025): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 8025): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 8025): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 8025): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 8025): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 8025): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8048 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7741:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10036/pid_7741/cgroup.procs: No such file or directory
,W/ResourcesManager( 8048): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 2037): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 2037): UpdateCorporaTask done [took 41 ms] updated apps [took 41 ms] 
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8073 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 7790:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/art     (  311): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 302us total 26.803ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.242ms
,W/System.err( 7409): android.os.DeadObjectException
W/System.err( 7409): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7409): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 7409): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 7409): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7409): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 7409): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7409): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7409): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7409): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7409): android.os.DeadObjectException
W/System.err( 7409): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7409): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7409): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7409): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7409): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7409): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7409): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7409): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 7409): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7409): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7409): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.515ms
,W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_7790/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8099 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 8099): Quickset Services start...
,I/UEI.SmartControl( 8099): Manufacture = LGE
D/UEI.SmartControl( 8099): File observer start...
E/UEI.SmartControl( 8099): IR Port is disabled: false
D/UEI.SmartControl( 8099): Starting file observer...
D/UEI.SmartControl( 8099): Extracting JNI libs...
D/UEI.SmartControl( 8099): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 8073): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 8099): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8099): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8099): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/UEI.SmartControl( 8099): --- Selecting new region: 2
I/UEI.SmartControl( 8099): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 8099): Platform has CIR...
,D/UEI.SmartControl( 8099): NO CIR support, need to check package...
I/UEI.SmartControl( 8099): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 8099): QS Service created
E/UEI.SmartControl( 8099): QS start get config
,D/UEI.SmartControl( 8099): Loading JNI Libs...
D/UEI.SmartControl( 8099):  configuring local db...
,D/Finsky  ( 8073): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 8073): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8073): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 8073): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3189): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3189): created cursor android.database.sqlite.SQLiteCursor@368adeff on behalf of 8073
D/Finsky  ( 8073): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8073): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8073): Skipping gmscore version check
,D/Finsky  ( 8073): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5480): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5480): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 8073): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 5480): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 8099):  ---- Has DB8: true
,D/UEI.SmartControl( 8099): QS start statue = true Error code = 0
D/UEI.SmartControl( 8099): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8099): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8099): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8099): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8099): IrrcClient ++ 
D/irrcClient( 8099): getIrrcService ++ 
D/irrcClient( 8099): getIrrcService -- 
D/irrcClient( 8099): IrrcClient -- 
W/irrc_jni( 8099): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8099): Services init done
,I/UEI.SmartControl( 8099): Device manager: loading config....
D/UEI.SmartControl( 8099): QS Service init finished
D/UEI.SmartControl( 8099): QS Service version name: 0.1.73
D/UEI.SmartControl( 8099): Config is loaded...
D/UEI.SmartControl( 8099): QS Service version code: 1073
D/UEI.SmartControl( 8099): Service requested: Control
D/UEI.SmartControl( 8099): -----IControl: 11
I/ActivityManager(  853): Killing 7409:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 8099): Caller: com.lge.qremote
D/UEI.SmartControl( 8099): ------------ IControl registerCallback...
,I/UEI.SmartControl( 8099): Registering callback...
,W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_7409/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8099): Internal service binding...
,D/UEI.SmartControl( 8099):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8099): Notify AllClients services are ready: 0
I/Icing   ( 5480): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5480): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  853): Killing 7870:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7870/cgroup.procs: No such file or directory
,D/KeyguardViewMediator( 1380): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{e883b33 type 2 when 160622 com.android.systemui} when 160622
,D/PhoneUtils( 1817): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1817): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1817): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1817): getCallState : 0
D/PhoneUtils( 1817): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1817): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1817): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1380): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1380): doKeyguard: not showing because lockscreen is off
I/ActivityManager(  853): Killing 6951:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_6951/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 8099): Internal timer expired: 1
,D/UEI.SmartControl( 8099): Service.onUnbind: IControl
D/UEI.SmartControl( 8099): Service.onDestroy
D/UEI.SmartControl( 8099): Shutdown IRRCPlayer... 
W/irrc_jni( 8099): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8099): ~IrrcClient ++ 
D/irrcClient( 8099): ~IrrcClient -- 
W/irrc_jni( 8099): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 8099): Blaster closed
D/UEI.SmartControl( 8099): Blaster closed
D/UEI.SmartControl( 8099): Shut down QS...
,D/UEI.SmartControl( 8099): Stopped file observer...
I/UEI.SmartControl( 8099): QS lib stop result = true
,D/UEI.SmartControl( 8099): QS shutdown complete
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 174379932594; DSPS: 5812855; Offset : -3016453163
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=412782811, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2e7ceef0 type 2 when 181856 android} when 181856
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=412782811 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1789): disconnect managed GoogleApiClient
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{199f0c69 type 2 when 186540 com.google.android.gms} when 186540
,I/PhenotypeConfigurator( 1789): Scheduling Phenotype for one-off execution 1593 seconds from now (1455058283924)
,D/GetConfigurationSnapshotOperation( 1789): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1789): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1789): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1789): propertyValue:false
D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1789): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1789): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/PowerService( 1881): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  470): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1789): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 194380571493; DSPS: 6468236; Offset : -3016455550
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 214381258569; DSPS: 7123619; Offset : -3016469883
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 234381918249; DSPS: 7779000; Offset : -3016450968
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1881): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/charger_monitor(  470): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
,D/charger_monitor(  470): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1881): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1917): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1917): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1881): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1881): Battery Level Remaining: 100%
D/LEDHandler( 1881): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/HeadsetStateMachine( 2084): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 254382589647; DSPS: 8434382; Offset : -3016450984
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 274383271151; DSPS: 9089765; Offset : -3016471201
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 294383942966; DSPS: 9745147; Offset : -3016470981
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 5317): --= Surplus to requirements =--
I/jxcore-log( 5317): 
I/jxcore-log( 5317): ****TEST TOOK:  ms ****
I/jxcore-log( 5317): 
I/jxcore-log( 5317): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5317): 
,D/AndroidRuntime( 8220): 
D/AndroidRuntime( 8220): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8220): CheckJNI is OFF
,D/AndroidRuntime( 8220): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  853): Killing 5317:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  853): WIN DEATH: Window{1df4eba2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  853): Focus left window: Window{1df4eba2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  853): Window went away: Window{1df4eba2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  853): Skipping PackageSetting{32f5913e com.example.hello/10317} due to missing metadata
,I/ActivityManager(  853):   Force finishing activity ActivityRecord{1e87e119 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  853): Display changed displayId=0
,D/DSDPConnection( 1817): Display #0 changed.
W/ActivityManager(  853): Spurious death for ProcessRecord{156e1d9 5317:com.test.thalitest/u0a316}, curProc for 5317: null
,I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  853):   Force finishing activity ActivityRecord{1e87e119 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  853): Duplicate finish request for ActivityRecord{1e87e119 u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1380): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1955): [Launcher.java:5203:onStart()]onStart
,I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1917): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1789): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3542): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3542): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3542): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3542): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3542): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3542): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3542): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3542): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3542): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3542): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3542): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3542): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 2037): Explicit concurrent mark sweep GC freed 27780(1714KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/20MB, paused 7.973ms total 122.160ms
,I/[LGHome]EVENT( 1955): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8253 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 5480): Explicit concurrent mark sweep GC freed 31644(1971KB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/17MB, paused 768us total 174.898ms
,W/SQLiteConnectionPool( 5480): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[LGHome]EVENT( 1955): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1380): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1955): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1380): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1380): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1955): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1955): [Launcher.java:929:onResume()]onResume end
I/Activity( 1955): Activity.onPostResume() called 
D/KeyguardModel( 1380): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1380): createShortcutInfo...
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/[LGHome]EVENT( 1955): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1955): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1955): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,D/KeyguardModel( 1380): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1380): createShortcutInfo...
,W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1380): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1380): createShortcutInfo...
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1380): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1380): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1380): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1380): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/art     (  853): Explicit concurrent mark sweep GC freed 41224(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 11.481ms total 248.168ms
D/KeyguardModel( 1380): handleShortcutListChanged...
I/art     (  853): WaitForGcToComplete blocked for 84.834ms for cause Explicit
D/KeyguardModel( 1380): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1380): createShortcutInfo...
,D/KeyguardModel( 1380): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1380): createShortcutInfo...
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1380): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1380): createShortcutInfo...
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1380): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1380): createShortcutInfo...
,I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2269f1c6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2269f1c6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/InputDispatcher(  853): Focus entered window: Window{207271b5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1380): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1380): createShortcutInfo...
D/administrator(  853): Handling package changes for user 0
,D/KeyguardModel( 1380): handleShortcutListChanged...
,I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourcesManager( 8253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8253): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1955): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourcesManager( 8253): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1955): [Launcher.java:5214:onStop()]onStop
,I/[LGHome]EVENT( 1955): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1955): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  853): Got RemoteException sending setActive(false) notification to pid 5317 uid 10316
,I/LGEmail ( 8253): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8253): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]Launcher.Model( 1955): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/NotificationService(  853): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/PhoneStatusBar( 1380): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1380): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1380):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1380): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/TaskPersister(  853): removeObsoleteFile: deleting file=222_task.xml
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{144703af u0 com.lge.launcher2/.Launcher t221} time:302662
,W/IInputConnectionWrapper( 1955): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1955): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1613): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1955): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1955): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 1955): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
I/PackageChangeReceiver( 8253): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/art     (  853): Explicit concurrent mark sweep GC freed 7581(417KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.448ms total 406.554ms
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/LCardEmulationManager( 1864): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1864): getDefaultRoute
,D/AppUp4:PreloadHelper( 7958): added Exclude : com.test.thalitest
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1955): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8281 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7914:com.google.android.talk/u0a61 (adj 15): empty #11
D/AndroidRuntime( 8220): Shutting down VM
,W/libprocessgroup(  853): failed to open /acct/uid_10061/pid_7914/cgroup.procs: No such file or directory
,W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1955): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1955): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1955): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1955): getTextAfterCursor on inactive InputConnection
I/[LGHome]EVENT( 1955): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8281): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8281): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8281): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8281): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1955): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1955): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1955): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1955): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SharedPreferencesImpl( 1955): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
,I/Timeline( 1955): Timeline: Activity_idle id: android.os.BinderProxy@395c5dda time:303320
E/SQLiteDatabase( 8281): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8281): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8281): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8281): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8281): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8281): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8281): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8281): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8281): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8281): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8281): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8281): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8281): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8281): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8281): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8281): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)

```
