#### Test 58135655e9e7eb8_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/[BNRAppListMgrReceiver]( 5511): android.intent.action.PACKAGE_ADDED : com.test.thalitest
W/MainApplication( 5511): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
--------- beginning of system
I/ActivityManager(  849): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5533 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 4982:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10006/pid_4982/cgroup.procs: No such file or directory
W/ActivityManager(  849): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
D/AndroidRuntime( 5550): 
D/AndroidRuntime( 5550): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5550): CheckJNI is OFF
D/AlertService( 3832): Beginning updateAlertNotification
I/ActivityManager(  849): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5567 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5550): Calling main entry com.android.commands.am.Am
I/ActivityManager(  849): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     (  849): Explicit concurrent mark sweep GC freed 16352(896KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.055ms total 177.289ms
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{25f03ae3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{25f03ae3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  849): AppWindowTokenEx init.. 
D/ContextHelper(  849): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  849): Focus left window: Window{1e308901 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5550): Shutting down VM
D/SplitWindow(  849): check instance of lgWin Window{df8855 u0 Starting com.test.thalitest}
I/ActivityManager(  849): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5594 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
W/ResourcesManager( 5567): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1875): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1875): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1875): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1875): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1875): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1875): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1875): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1875): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1875): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1875): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1875): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1875): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/CalendarProvider2( 5567): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@219088c
I/ActivityManager(  849): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5612 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@793060e
V/AudioRecord( 1936): stop()
I/WindowStateAnimator(  849): Starting window displayed
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
I/SystemUI[Framework](  849): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 16
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  849): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  849): setLGSystemUiVisibility(0x0)
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3846000
D/CalendarProvider2( 5567): [getOrCreateCalendarAlarmManager]
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/StatusBarManagerServiceEx(  849): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30cc762e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/CalendarProvider2( 5567): Created com.android.providers.calendar.CalendarAlarmManager@3c150051(com.android.providers.calendar.CalendarProvider2@219088c)
,I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 11000000
D/BarTransitions( 1372): draw background and invalidate : color = f0e0e0e
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
D/AlertService( 3832): No fired or scheduled alerts
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/NotificationManager( 3832): com.android.calendar: cancel(0) by com.android.calendar
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  282): setParameters(): io 16, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3846000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/NotificationManager( 3832): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(11) by com.android.calendar
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
I/NotificationManager( 3832): com.android.calendar: cancel(12) by com.android.calendar
V/AudioFlinger(  282): releasing 15 from 1936 for -1
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282): purging stale effects
V/AudioPolicyManager(  282): releaseInput() 16
V/AudioPolicyManager(  282): closeInput(16)
I/NotificationManager( 3832): com.android.calendar: cancel(13) by com.android.calendar
V/AudioFlinger(  282): closeInput() 16
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  849): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1984): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3233): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2749): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb3846000 exiting
I/HotwordRecognitionRnr( 1936): Hotword detection finished
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1936, calling pid 282
I/NotificationManager( 3832): com.android.calendar: cancel(14) by com.android.calendar
I/ActivityManager(  849): Activity reported stop, but no longer stopping: ActivityRecord{ec2cb0 u0 com.lge.launcher2/.Launcher t221}
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/NotificationManager( 3832): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(18) by com.android.calendar
W/ResourcesManager( 5612): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5612): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 3832): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3832): com.android.calendar: cancel(20) by com.android.calendar
D/ContextHelper( 5594): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/MultiDex( 5612): VM with version 2.1.0 has multidex support
I/MultiDex( 5612): install
I/MultiDex( 5612): VM has multidex support, MultiDex support library is disabled.
D/AlertService( 3832): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  849): Killing 5360:com.lge.email/u0a21 (adj 15): empty #11
I/GAv4    ( 5533): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5533):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5533):   adb logcat -s GAv4
W/libprocessgroup(  849): failed to open /acct/uid_10021/pid_5360/cgroup.procs: No such file or directory
W/GAv4    ( 5533): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/AlarmScheduler( 3832): No events found starting within 1 week.
I/WebViewFactory( 5594): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/JNIHelp ( 5612): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/GAv4    ( 5533): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5533): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5533): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/LibraryLoader( 5594): Time to load native libraries: 10 ms (timestamps 224-234)
I/LibraryLoader( 5594): Expected native library version number "",actual native library version number ""
W/ActivityThread( 5612): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5612): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ddf18ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5612): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5612): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5612): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WebViewChromiumFactoryProvider( 5594): Binding Chromium to main looper Looper (main, tid 1) {3c150051}
I/LibraryLoader( 5594): Expected native library version number "",actual native library version number ""
I/chromium( 5594): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5594): Initializing chromium process, singleProcess=true
W/art     ( 5594): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5594): ApplicationContext is null in ApplicationStatus
I/art     ( 5612): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5612): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  849): Killing 4319:com.google.android.gms/u0a6 (adj 15): empty #11
W/chromium( 5594): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5594): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5594): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5594): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5594): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5594): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5594): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5594): Remote Branch: 
I/Adreno-EGL( 5594): Local Patches: 
I/Adreno-EGL( 5594): Reconstruct Branch: 
W/libprocessgroup(  849): failed to open /acct/uid_10006/pid_4319/cgroup.procs: No such file or directory
V/AudioPolicyService(  282): registerClient() client 0xb4027080, uid 10316
D/BluetoothManagerService(  849): Message: 20
D/BluetoothManagerService(  849): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc4b37d:true
,D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
D/NativeLibraryUtils( 5612): Install completed successfully. count=14 extracted=0
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5533): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5666 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5533): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5533): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 393us total 26.174ms
I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.298ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 24.309ms
,I/art     ( 5533): CheckpointMarkThreadRoots callback created = 0xb050fa40
,W/art     ( 5594): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5594): onDetachedFromWindow called when already detached. Ignoring
I/NotificationManager( 5533): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{8249c22 type 2 when 80708 android} when 80708
W/ResourcesManager( 5666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 5594): CordovaWebView is running on device made by: LGE
,V/JNIHelp ( 5533): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5533): CheckpointMarkThreadRoots callback created = 0xb050fa10
W/art     ( 5594): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5594): Attempt to remove local handle scope entry from IRT, ignoring
W/System  ( 5533): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5533): Installed default security provider GmsCore_OpenSSL
,I/Activity( 5594): Activity.onPostResume() called 
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/OpenGLRenderer( 5594): Render dirty regions requested: true
I/OpenGLRenderer( 5594): Initialized EGL, version 1.4
D/OpenGLRenderer( 5594): Enabling debug mode 0
,D/Atlas   ( 5594): Validating map...
,D/SplitWindow(  849): check instance of lgWin Window{b84c721 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5594): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  849): Killing 5391:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10009/pid_5391/cgroup.procs: No such file or directory
,D/InputDispatcher(  849): Focus entered window: Window{b84c721 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  849): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  849): Displayed com.test.thalitest/.MainActivity: +1s320ms
I/Timeline(  849): Timeline: Activity_windows_visible id: ActivityRecord{7cc6ce0 u0 com.test.thalitest/.MainActivity t222} time:81021
I/Timeline( 5594): Timeline: Activity_idle id: android.os.BinderProxy@eccd754 time:81035
,W/BindingManager( 5594): Cannot call determinedVisibility() - never saw a connection for the pid: 5594
,D/JsMessageQueue( 5594): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  849): Killing 5411:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_5411/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5712 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
,D/jxcore_app_log( 5594): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622895104
,I/chromium( 5594): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Finsky  ( 5712): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 5594): CheckpointMarkThreadRoots callback created = 0xb04ebd50
I/art     ( 5594): CheckpointMarkThreadRoots callback created = 0xb04ebd20
,D/Finsky  ( 5712): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5712): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5712): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5712): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@2f2edf69 on behalf of 5712
,I/NotificationManager( 5712): com.android.vending: cancel(1003285959) by com.android.vending
,D/Finsky  ( 5712): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5712): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5712): Skipping gmscore version check
,I/ActivityManager(  849): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5753 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5712): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5712): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5712): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  849): Killing 5428:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10023/pid_5428/cgroup.procs: No such file or directory
,W/ResourcesManager( 5753): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5753): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5753): VM with version 2.1.0 has multidex support
,I/MultiDex( 5753): install
I/MultiDex( 5753): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  849): Process com.lge.bnr (pid 5511) has died
,V/JNIHelp ( 5753): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5753): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5753): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c1c4649: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5753): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5753): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5753): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5753): Reading stored module config
D/PackageBroadcastService( 5753): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5753): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5753): Loading module APK com.google.android.play.games
D/NativeLibraryUtils( 5753): Install completed successfully. count=14 extracted=0
,I/art     ( 5753): CheckpointMarkThreadRoots callback created = 0xb042d3e0
,I/art     ( 5753): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,D/ChimeraCfgMgr( 5753): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5753): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  849): Process com.android.contacts (pid 5454) has died
,D/ChimeraCfgMgr( 5753): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5753): Submit a task: k
,W/jxcore-log( 5594): Initializing JXcore engine
W/jxcore-log( 5594): JXcore engine is ready
I/ActivityManager(  849): Process com.lge.lockscreensettings (pid 5477) has died
,D/ChimeraCfgMgr( 5753): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5753): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5753): Processing package: com.test.thalitest
W/BaseAppContext( 5753): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 5753): cleanUpNonGplusAccounts done.
,D/GassUtils( 5753): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5753): Found info for package com.test.thalitest in db.
I/Icing   ( 5753): Storage manager: low false usage 1.75MB avail 2.38GB capacity 4.06GB
,I/art     ( 5753): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5753): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Thread-672( 5731): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5117]" dev="sockfs" ino=5117 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5731): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-672( 5731): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8325]" dev="sockfs" ino=8325 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5731): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5731): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5731): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24011]" dev="sockfs" ino=24011 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
E/BaseAppContext( 5753): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5753): Using Auth Proxy for data requests.
W/jxcore-log( 5594): Starting JXcore engine
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
I/art     ( 3996): Explicit concurrent mark sweep GC freed 3380(130KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 846us total 35.718ms
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/MDM     ( 1731): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/BaseAppContext( 5753): Using Auth Proxy for data requests.
,D/LocationInitializer( 5753): Restart initialization of location
,W/BaseAppContext( 5753): Using Auth Proxy for data requests.
W/BaseAppContext( 5753): Using Auth Proxy for data requests.
W/BaseAppContext( 5753): Using Auth Proxy for data requests.
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/lowmemorykiller(  241): Error writing /proc/5494/oom_score_adj; errno=22
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  849): Process com.lge.eula (pid 5494) has died
,I/BackgroundMemoryTrimmer( 1936): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
,D/ChimeraCfgMgr( 5753): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5753): Module APK com.google.android.play.games already loaded
W/jxcore-log( 5594): Platform android
W/jxcore-log( 5594): 
W/jxcore-log( 5594): Process ARCH arm
W/jxcore-log( 5594): 
,W/BaseAppContext( 5753): Using Auth Proxy for data requests.
I/ActivityManager(  849): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5812 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  849): Explicit concurrent mark sweep GC freed 21649(1022KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.434ms total 152.874ms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,W/IcingInternalCorpora( 5753): getNumBytesRead when not calculated.
,I/art     ( 5753): Background sticky concurrent mark sweep GC freed 16448(1505KB) AllocSpace objects, 14(224KB) LOS objects, 9% free, 12MB/14MB, paused 13.734ms total 141.015ms
I/jxcore-log( 5594): JXcore Cordova bridge is ready!
I/jxcore-log( 5594): 
W/jxcore-log( 5594): JXcore engine is started
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5753): updateResources: need to parse f{com.google.android.gms}
,I/Gmail   ( 5812): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5753): Background sticky concurrent mark sweep GC freed 6652(514KB) AllocSpace objects, 5(80KB) LOS objects, 7% free, 13MB/14MB, paused 6.582ms total 39.705ms
,W/GAV2    ( 5812): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/jxcore-log( 5594): Toggling radios to true
I/jxcore-log( 5594): 
D/BluetoothAdapter( 5594): enable(): BT is already enabled..!
,D/WifiServiceImplEx(  849): setWifiEnabled: true pid=5594, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  849): setWifiEnabled: true pid=5594, uid=10316
D/WifiServiceImplEx(  849): disconnect pid=5594, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  849): reconnect pid=5594, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5594): Radios toggled
I/jxcore-log( 5594): 
I/jxcore-log( 5594): My device name is: LGE-LG-D722
I/jxcore-log( 5594): 
W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/wpa_supplicant( 2783): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2783): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  849): WifiStateMachine: Leaving Connected state
E/Gmail   ( 5812): Error finding the version of the Email provider.....
E/Gmail   ( 5812): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5812): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5812): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5812): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5812): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5812): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5812): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5812): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5812): getAccountsCursor
D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DhcpStateMachine(  849): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  849): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  849): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): Read error: ssl=0xaaf4e400: I/O error during system call, Connection timed out
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaf4e400: I/O error during system call, Broken pipe
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  849): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20(  849): hidePasspointNotification off =false
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): Forcing reevaluation
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiStateMachine(  849): Start Disconnecting Watchdog 1
D/WifiHS20(  849): hidePasspointNotification off =false
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/LGWifiP2pService(  849): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  849): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:35.736 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:35.751 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
W/ActivityManager(  849): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  849): RTC_WAKEUP set : Alarm{2f98e8eb type 0 when 1454935005637 com.android.providers.contacts} when 1454935005637
V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{2bd4f648 type 2 when 60228 com.google.android.talk} when 60228
,V/AlarmManager(  849): RTC_WAKEUP set : Alarm{13ec6a06 type 0 when 1455021455764 com.google.android.googlequicksearchbox} when 1455021455764
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
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
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/ConnectivityService(  849): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  849): disableDataServiceNotify
D/DSQN    (  849): stop dsqn bin
D/InitAlarmsService( 3832): Clearing and rescheduling alarms.
D/DhcpStateMachine(  849): StoppedState
D/ConnectivityService(  849): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/DhcpStateMachine(  849): StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  849): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  849): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  849): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ActivityManager(  849): Process com.google.android.apps.docs (pid 5533) has died
,D/WifiHS20(  849): hidePasspointNotification off =false
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:35.925 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/ActivityManager(  849): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/WifiNetworkAgent(  849): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  849): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  849): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  849): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  849): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  849): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1829): |CORE| No family connected
D/NetworkManagementService(  849): Removing idletimer
W/QCNEJ   ( 1829): |CORE| No family connected
I/QCNEJ   ( 1829): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  849): MasterInitialState.processMessage what=3
D/Tethering(  849): MasterInitialState.processMessage what=3
,E/ConnectivityService(  849): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/QCNEJ   ( 1829): |CORE| sendDefaultNwMsg: default = -1
D/CalendarProvider2( 5567): Scheduling check of next Alarm
,D/WifiHS20(  849): hidePasspointNotification off =false
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:35.962 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:35.966 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/CalendarProvider2( 5567): SCHEDULE_ALARM_REMOVE
W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5812): Observing account changes for notifications
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateDISCONNECTED
D/WIFI    (  849): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  849):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateSCANNING
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  849): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5876 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/InstanceID/Rpc( 5753): Found 10006
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/Gmail   ( 5812): notifyAccountChanged
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/Gmail   ( 5812): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/Gmail   ( 5812): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5812): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5812): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5812): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5753): Internal init done: storage state 0
,I/NotificationManager( 5753): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 5753): Post-init done
,I/Gmail   ( 5812): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 5876): Register our PhoneStateListener
,D/PhoneMonitor( 5876): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/TelephonyAutoProfiling( 5876): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5876): [parse] Load xml
V/TelephonyAutoProfiling( 5876): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5876): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5876): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  849): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5903 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5903): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{17584ff2 type 2 when 85984 com.google.android.gms} when 85984
,I/wpa_supplicant( 2783): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
D/LocSvc_java(  849): onReceive
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:36.913 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:36.918 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/wpa_supplicant( 2783): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:36.952 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:36.956 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null,
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,I/wpa_supplicant( 2783): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2783): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  849): setVHTCapabilityType  : false
,I/WifiServerServiceExt(  849): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  849): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  849): setSecurityType  : 2
I/CalendarProvider2( 5567): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:37.023 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/ContentResolver( 5567): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:37.03 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/Babel_SMS( 5903): MmsConfig: mnc/mcc: 0/0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/Babel_SMS( 5903): MmsConfig.loadMmsSettings
D/ConnectivityService(  849): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  849): Got NetworkAgent Messenger
D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  849): NetworkAgent connected
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Babel_SMS( 5903): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5903): MmsConfig.loadFromDatabase
E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  849): Start Dhcp Watchdog 2
D/DhcpStateMachine(  849): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  849): WaitBeforeStartState
E/Babel_SMS( 5903): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5903): MmsConfig.loadFromResources
D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/Babel_SMS( 5903): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5903): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5903): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5903): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5903): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5903): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5903): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5903): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5903): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5903): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5903): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5903): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5903): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5903): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5903): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5903): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5903): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5903): found sensor: Motion Accel, handle=46
,E/WifiStateMachine(  849): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  849): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  849): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c641d9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  849): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c641d9 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  849): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  849): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  849): DHCP Start wake lock is acquired.
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 5903): CheckpointMarkThreadRoots callback created = 0xb042d8a0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  849): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/ActivityManager(  849): Process com.android.calendar (pid 3832) has died
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateCOMPLETED
D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  849): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  849): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  849): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  849): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  849): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  849): ignoring duplicate network state non-change
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:37.21 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  849): Adding iface wlan0 to network 101
,W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  849): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  849): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:37.226 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  849): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:37.23 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:37.235 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/art     ( 5903): CheckpointMarkThreadRoots callback created = 0xb042d880
,E/ConnectivityService(  849): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  849): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  849): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  849): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/Settings( 5903): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  849): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  849): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  849): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  849): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  849): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  849):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  849):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  849): currentScore = 0, newScore = 20
I/Babel_Crash( 5903): startup - clean
D/ConnectivityService(  849):    accepting network in place of null
D/ConnectivityService(  849): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  849): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  849):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/ConnectivityService(  849): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  849): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  849): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  849): [e] list.add(nai) empty : false size: 1
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
W/QCNEJ   ( 1829): |CORE| No family connected
I/QCNEJ   ( 1829): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  849): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): [LWD] wait 500ms before dns check
D/Tethering(  849): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1829): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  849): validation of new default Network = false
D/ConnectivityService(  849): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  849): enableDataServiceNotify 
D/DSQN    (  849): start dsqn bin
V/NetworkPolicy(  849): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  849): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
I/DSQN    ( 5944): DSQN samuel.seo ver 141203
E/DSQN    ( 5944): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5944): created command queue thread
I/DSQN    ( 5944): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5944): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/Babel   ( 5903): deleted: false for 0
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 5753): Checkin interval check for package: unspecified last checkin: 1455021448703 min interval config: 0 actual interval: 8640
,I/Icing   ( 5753): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/CheckinService( 5753): Disabling old GoogleServicesFramework version
,D/DhcpStateMachine(  849): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  849): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  849): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5950): version 5.5.6 starting
E/dhcpcd  ( 5950): get_duid: Read-only file system
I/art     ( 5753): Background sticky concurrent mark sweep GC freed 6201(451KB) AllocSpace objects, 5(80KB) LOS objects, 4% free, 13MB/14MB, paused 5.419ms total 61.082ms
,I/dhcpcd  ( 5950): wlan0: rebinding lease of 192.168.1.134
,W/AudioCapabilities( 5903): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5903): Unsupported mime audio/adpcm
W/AudioCapabilities( 5903): Unsupported mime audio/g726
W/AudioCapabilities( 5903): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5903): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5903): Unsupported mime video/mjpg
,W/VideoCapabilities( 5903): Unsupported mime video/theora
D/Icing   ( 5753): Loaded CLD2 Version V2.0 - 20141016
,W/AudioCapabilities( 5903): Unsupported mime audio/evrc
W/AudioCapabilities( 5903): Unsupported mime audio/qcelp
I/CheckinService( 5753): Checking schedule, now: 1455021457582 next: 1455021478664
,I/CheckinService( 5753): active receiver: disabled
W/VideoCapabilities( 5903): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5903): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5903): Unsupported mime audio/qcelp
W/AudioCapabilities( 5903): Unsupported mime audio/evrc
W/VideoCapabilities( 5903): Unsupported mime video/mp4v-esdp
,I/Icing   ( 5753): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  849): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5958 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5237): getMode name:com.lge.qremote
,I/AudioManager( 5237): getMode name:com.lge.qremote
,I/VideoCapabilities( 5903): Unsupported profile 4 for video/mp4v-es
I/AudioManager( 5237): getMode name:com.lge.qremote
,W/VideoCapabilities( 5903): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5903): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5903): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5903): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5903): onServiceConnected
W/Babel   ( 5903): Attempted to change video mute state without an active call.
,I/NotificationManager( 5903): com.google.android.talk: cancel(10436) by com.google.android.talk
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): [LWD] DNSResolver start dns
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5958): Quickset Services start...
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/UEI.SmartControl( 5958): Manufacture = LGE
,D/UEI.SmartControl( 5958): File observer start...
E/UEI.SmartControl( 5958): IR Port is disabled: false
D/UEI.SmartControl( 5958): Starting file observer...
D/UEI.SmartControl( 5958): Extracting JNI libs...
I/AudioManager( 5237): getMode name:com.lge.qremote
D/UEI.SmartControl( 5958): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5237): getMode name:com.lge.qremote
,E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  849): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): Checking http://clients3.google.com/generate_204 on "NG700"
D/LocationInitializer( 5753): Restart initialization of location
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5944): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5944): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5944): dsqn report finish
D/DSQN    (  849): DSQM DsqnNotification wlan0  1
,D/DSQN    (  849): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:37:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455021457883], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455021457863]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  849): Validated
D/ConnectivityService(  849): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  849):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  849): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  849): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  849): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  849):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/UEI.SmartControl( 5958): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5958): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5958): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     (  849): Explicit concurrent mark sweep GC freed 55319(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.576ms total 201.070ms
,I/UEI.SmartControl( 5958): --- Selecting new region: 2
I/UEI.SmartControl( 5958): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5958): Platform has CIR...
D/UEI.SmartControl( 5958): NO CIR support, need to check package...
I/UEI.SmartControl( 5958): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5958): QS Service created
I/ActivityManager(  849): Process com.google.android.gms.unstable (pid 5612) has died
,D/WifiDataContinuityService(  849): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  849): set CMD_CAPTIVE_CHECK_COMPLETED
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5237): getMode name:com.lge.qremote
,E/UEI.SmartControl( 5958): QS start get config
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 5958): Loading JNI Libs...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 5958):  configuring local db...
D/ConnectivityService(  849): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5987 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  849): Process com.google.android.apps.plus (pid 5666) has died
,I/BackgroundMemoryTrimmer( 1936): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
I/NotificationManager( 5903): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5903): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5903): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 5987): onCreate
,W/AppUp4:DB( 5987):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5987):  setFingerPrint start
I/AppUp4:DB( 5987):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/UEI.SmartControl( 5958):  ---- Has DB8: true
I/AppUp4:DB( 5987):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5987):  SDK version = 0
I/AppUp4:DB( 5987):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5987): AppBoxApplication onCreate()
D/UEI.SmartControl( 5958): QS start statue = true Error code = 0
D/UEI.SmartControl( 5958): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5958): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
V/JNIHelp ( 5903): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/UEI.SmartControl( 5958): IRRCDataComm has AudioManager!!!!.
I/AppUp4:CustModeStarterReceiver( 5987): onReceive
I/AppUp4:CustModeStarterReceiver( 5987): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5987): Context : android.app.ReceiverRestrictedContext@315a02db
D/AppUp4:CustFacade( 5987): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5987): isSimDevice : true
W/irrc_jni( 5958): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5958): IrrcClient ++ 
D/irrcClient( 5958): getIrrcService ++ 
,D/AppUp4:CustModeStarterReceiver( 5987): begin check event
D/irrcClient( 5958): getIrrcService -- 
D/irrcClient( 5958): IrrcClient -- 
W/irrc_jni( 5958): IRRCPlayer_nativeInit -- 
I/AppUp4:CustModeStarterReceiver( 5987): Event For Nothing, skip.
D/UEI.SmartControl( 5958): Services init done
,I/UEI.SmartControl( 5958): Device manager: loading config....
D/UEI.SmartControl( 5958): Config is loaded...
,I/ActivityManager(  849): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6010 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5958): QS Service init finished
D/UEI.SmartControl( 5958):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5958): Notify AllClients services are ready: 0
W/System  ( 5903): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5903): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 5958): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5958): QS Service version code: 1073
D/UEI.SmartControl( 5958): Service requested: Control
D/UEI.SmartControl( 5958): Service.onTrimMemory: 10
E/UEI.SmartControl( 5958): Setup service releasing memory...
D/UEI.SmartControl( 5958): -----IControl: 11
,D/UEI.SmartControl( 5958): Caller: com.lge.qremote
D/UEI.SmartControl( 5958): ------------ IControl registerCallback...
I/UEI.SmartControl( 5958): Registering callback...
D/UEI.SmartControl( 5958): -----IControl: 19
D/UEI.SmartControl( 5958): Caller: com.lge.qremote
I/UEI.SmartControl( 5958): Registering Services Ready callback...
I/UEI.SmartControl( 5958): Notify client services are ready...
D/UEI.SmartControl( 5958): -----IControl: 8
,D/UEI.SmartControl( 5958): Caller: com.lge.qremote
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/dhcpcd  ( 5950): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/QCNEJ   ( 1829): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/ResourcesManager( 6010): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6010): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6010): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/InputReader(  849): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/dhcpcd  ( 5950): wlan0: leased 192.168.1.134 for 86400 seconds
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/art     ( 5958): Explicit concurrent mark sweep GC freed 10551(754KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 572us total 138.690ms
D/UEI.SmartControl( 5958): Internal service binding...
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1829): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:38.91 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  849): identical MTU - not setting
D/Nat464Xlat(  849): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  849): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  849): enableDataServiceNotify 
D/DSQN    (  849): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
D/DSQN    (  849): dsqn is running restart
,D/administrator(  849): Handling package changes for user 0
D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DSQN    ( 6038): DSQN samuel.seo ver 141203
E/DSQN    ( 6038): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6038): created command queue thread
I/DSQN    ( 6038): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6038): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  849): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  849): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  849): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  849): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  849): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  849): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  849): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  849): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  849): RunningState
I/AppConfig( 6010): Total System Memory = 906309632
I/GalleryUtils( 6010): Application Heap = 96 MB
,I/AppConfig( 6010): App Tier : NOT_DEF
,D/SystemHelper( 6010): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationService(  849): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  849): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  849): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  849): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LocSvc_java(  849): onReceive
D/LocSvc_java(  849): got connectivity action
,D/LocSvc_java(  849): broadcast - no network connections
D/LocSvc_java(  849): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  849): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  849): onReceive
D/LocSvc_java(  849): got connectivity action
D/LocSvc_java(  849): broadcast - no network connections
D/LocSvc_java(  849): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  849): Sending msg: 4 arg1:0 arg2:1
V/BackupManagerService(  849): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  849): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32050fc2
D/LocSvc_java(  849): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  849): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  849): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  849): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  849): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  849): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  849): Process com.android.vending (pid 5712) has died
,W/ResourcesManager(  849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  849): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6053 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,W/ResourcesManager( 6053): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6053): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType(  849): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/GpsLocationProvider(  849): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  849): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocationProviderProxy(  849): applying state to connected service
D/GpsLocationProvider(  849): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  849): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemConfig( 6053): BUILD Country: EU
I/SystemConfig( 6053): BUILD Operator: OPEN
,I/SystemConfig( 6053): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6053): existFile = false
I/SystemConfig( 6053): canReadFile = false
I/SystemConfig( 6053): systemFeature RCS result false
D/SystemConfig( 6053): refreshRcsSupport() :false
I/ActivityManager(  849): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6073 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 6073): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6073): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6073): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6073): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6073): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6073): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6093 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 308us total 25.752ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.896ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.097ms
,I/QCNEJ   ( 1829): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:37:40.104 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/WifiInternetCheck(  849): Single check msg out of sync, ignoring.
,D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  849): onReceive
D/LocSvc_java(  849): got connectivity action
D/LocSvc_java(  849): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  849): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  849): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  849): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  849): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  849): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  849): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  849): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6125 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAV2    ( 5812): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  849): Killing 5812:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 169 ms] updated apps [took 169 ms] 
W/libprocessgroup(  849): failed to open /acct/uid_10053/pid_5812/cgroup.procs: No such file or directory
,I/GAv4-SVC( 5753): Google Analytics 8.4.89 is starting up.
V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{2cbab134 type 2 when 90152 com.android.providers.calendar} when 90152
,I/NotificationManager( 1936): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  849): Process com.lge.qremote (pid 5237) has died
,D/Finsky  ( 6125): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,D/Finsky  ( 6125): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6125): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6125): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6125): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@133d4dee on behalf of 6125
,D/Finsky  ( 6125): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6125): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6125): Skipping gmscore version check
,D/Finsky  ( 6125): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5753): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  849): propertyValue:false
,D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  849): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  849): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  849): propertyValue:false
I/ActivityManager(  849): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6177 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/DSQN    ( 6038): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6038): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    (  849): DSQM DsqnNotification wlan0  1
D/DSQN    (  849): start to monitor internet connection
I/DSQN    ( 6038): dsqn report finish
I/PackageBroadcastService( 5753): Null package name or gms related package.  Ignoreing.
V/WifiInternetCheck(  849): isHttpConnectionAvailable - We got a valid response : 204
,I/Icing   ( 5753): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6125): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 6177): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  849): Message: 20
,D/BluetoothManagerService(  849): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18221c9:true
D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
V/LGMDMManager( 6177): Create singleton instance
,I/AudioManager( 6177): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5958): -----IControl: 11
,D/UEI.SmartControl( 5958): Caller: com.lge.qremote
D/UEI.SmartControl( 5958): ------------ IControl registerCallback...
I/UEI.SmartControl( 5958): Registering callback...
D/UEI.SmartControl( 5958): -----IControl: 19
D/UEI.SmartControl( 5958): Caller: com.lge.qremote
I/UEI.SmartControl( 5958): Registering Services Ready callback...
I/UEI.SmartControl( 5958): Notify client services are ready...
I/AudioManager( 6177): getMode name:com.lge.qremote
D/UEI.SmartControl( 5958): -----IControl: 8
,D/UEI.SmartControl( 5958): Caller: com.lge.qremote
V/SetupWizard( 5876): Connected to Gservices successfully
,I/ActivityManager(  849): Killing 5567:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10014/pid_5567/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/LocationInitializer( 5753): Restart initialization of location
E/MDM     ( 1731): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
E/MDM     ( 1731): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5753): Restart initialization of location
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 31517(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 2.731ms total 111.163ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  849): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6221 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 3996): Explicit concurrent mark sweep GC freed 3269(130KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 408us total 29.933ms
,I/Gmail   ( 6221): getAccountsCursor
,I/Icing   ( 5753): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5753): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     (  849): Explicit concurrent mark sweep GC freed 53206(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.236ms total 222.104ms
,W/ActivityManager(  849): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6221): Observing account changes for notifications
W/GAV2    ( 6221): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6221): Error finding the version of the Email provider.....
E/Gmail   ( 6221): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6221): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6221): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6221): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6221): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6221): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6221): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6221): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6221): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  849): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6264 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 5987:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_5987/cgroup.procs: No such file or directory
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6264): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Gmail   ( 6221): notifyAccountChanged
,I/IndexDatabaseHelper( 6264): Using schema version: 115
I/IndexDatabaseHelper( 6264): Index is fine
I/Gmail   ( 6221): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6221): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 5958): Internal timer expired: 1
I/Gmail   ( 6221): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6221): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6221): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6221): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  849): Killing 6010:com.android.gallery3d/u0a23 (adj 15): empty #11
,V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
W/libprocessgroup(  849): failed to open /acct/uid_10023/pid_6010/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  849): Killing 6053:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10018/pid_6053/cgroup.procs: No such file or directory
,V/AlarmManager(  849): RTC_WAKEUP set : Alarm{251261db type 0 when 1455021464084 com.android.vending} when 1455021464084
,D/Finsky  ( 6125): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  849): android: cancelAsUser(2) by android
,I/PCSuite ( 6295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
I/PCSuite ( 6295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
I/PCSuite ( 6295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 5903): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5903): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 6125): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6125): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6125): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6125): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/PCSuite ( 6295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6125): propertyValue:false
,D/libc-netbsd( 6125): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6125): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5594): 
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/libc-netbsd( 6125): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6125): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6264): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
,I/ActivityManager(  849): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6341 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  849): android: cancelAsUser(2) by android
,W/ResourcesManager( 6341): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/qtaguid ( 6125): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6125): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6125): untagSocket(41) failed with errno -22
D/Finsky  ( 6125): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/CalendarApplication( 6341): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6341): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6341): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3fdccfea, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@315a02db, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@942178, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3c150051, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@ab000b6, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2febf1b7, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@35a5dd24, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@ed8508d, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@14b37242, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1e43f253, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@15f5a790, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1c066889, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@58a708e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@261160af, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3735acbc, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@31e40445, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@9c1079a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@329d58cb, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@360ed8a8, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@4459fc1, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@18980366, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@10a6b6a7, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@eccd754, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@15cb76fd, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@a90eff2, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2ffe1643, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@14ca14c0, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@38dd85f9, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@cba193e, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@22e1d39f, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@349bbcec, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@246788b5, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3cba8b4a, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@371a0abb, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2cfdbbd8, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1854fb31, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@399e1216, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@4d49797, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2a7ebd84, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@dcd196d, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@356139a2, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@f411633, l
D/GeneralP,referenceUtils( 6341): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6341): [init]
,I/Config  ( 6341): LGCalendar ver.4.40.17
I/Config  ( 6341): start check model
I/Config  ( 6341): start check native_ca
I/Config  ( 6341): Config Operator=OPEN, Country=EU
D/Config  ( 6341): [setDefaultValuesToPref]
D/Config  ( 6341): [parseProfiles]
D/ProfilesParser( 6341): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6341): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6341): [updateProfiletoCountryInfo]
D/GeneralPreference( 6341): [checkAndMigrateOldPreference]
I/ActivityManager(  849): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6361 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlertReceiver( 6341): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/NotificationManager(  849): android: cancelAsUser(2) by android
,W/ResourcesManager( 6361): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6361): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6361): VM with version 2.1.0 has multidex support
,I/MultiDex( 6361): install
I/MultiDex( 6361): VM has multidex support, MultiDex support library is disabled.
I/qtaguid ( 6125): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6125): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6125): untagSocket(41) failed with errno -22
V/JNIHelp ( 6361): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6361): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6361): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ddf18ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6361): Installed default security provider GmsCore_OpenSSL
I/InitNotificationRingtoneService( 6341): Start InitializeAlertRingtoneService.onHandleIntent
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/HolidayIntentService( 6341): onHandleIntent
I/AlertUtils( 6341): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/HolidayDataLoader( 6341): readJsonAsset : holiday.json
I/ActivityManager(  849): Process com.lge.lockscreensettings (pid 6073) has died
,V/AlarmManager(  849): RTC_WAKEUP set : Alarm{52a006d type 0 when 1455021465280 com.google.android.googlequicksearchbox} when 1455021465280
I/NotificationManager( 6361): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6361): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/AlertService( 6341): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6341): [updateWidgets] 
,D/MonthWidgetProvider( 6341): [onReceive]
D/CalendarWidgetProvider( 6341): [onReceive]
D/CalendarWidgetProvider( 6341): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6341): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6341): [onReceive]
D/CalendarWidgetProvider( 6341): [onReceive]
D/CalendarWidgetProvider( 6341): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CalendarTypeController( 6341): [onCreate] mContext.getPackageName() = com.android.calendar
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
D/ChimeraCfgMgr( 6361): Reading stored module config
,I/art     ( 3257): Explicit concurrent mark sweep GC freed 5385(304KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 499us total 52.236ms
,E/HolidayIntentService( 6341): onHandleIntent:holiday data empty
,I/ActivityManager(  849): Process com.google.android.apps.plus (pid 6093) has died
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
D/UEI.SmartControl( 5958): Service.onTrimMemory: 60
E/UEI.SmartControl( 5958): Setup service releasing memory...
I/BackgroundMemoryTrimmer( 1936): Trimming objects from memory, since app is in the background.
D/ChimeraCfgMgr( 6361): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/UEI.SmartControl( 5958): Service.onTrimMemory: 60
E/UEI.SmartControl( 5958): Setup service releasing memory...
,V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/AlertUtils( 6341): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/UEI.SmartControl( 5958): Service.onTrimMemory: 60
E/UEI.SmartControl( 5958): Setup service releasing memory...
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
,I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/PCSuite ( 6295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/PCSuite ( 6295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
D/UEI.SmartControl( 5958): Service.onTrimMemory: 60
,E/UEI.SmartControl( 5958): Setup service releasing memory...
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
V/WiFiOffLoadBroadcast( 6264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/WiFiOffLoadBroadcast( 6264): MCCMNC not supported: null
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/PCSuite ( 6295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/AlertUtils( 6341): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6341): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/art     ( 6125): CheckpointMarkThreadRoots callback created = 0xaafa5160
I/AlertUtils( 6341): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6341): End InitializeAlertRingtoneService.onHandleIntent
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     ( 6125): CheckpointMarkThreadRoots callback created = 0xaafa5130
,I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6395 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/NativeLibraryUtils( 6361): Install completed successfully. count=14 extracted=0
I/NotificationManager( 5903): com.google.android.talk: cancel(8) by com.google.android.talk
,D/CAR.SERVICE( 6361): Connecting to CarCallService...
,I/art     ( 6361): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6361): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5594): 
,I/AppUp4:AppBoxCP( 6395): onCreate
W/AppUp4:DB( 6395):  [AppBoxDatabaseHelper] construct
,D/CAR.SERVICE( 6361): com.google.android.projection.gearhead isn't installed.
I/AppUp4:DB( 6395):  setFingerPrint start
I/AppUp4:DB( 6395):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6395):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6395):  SDK version = 0
I/AppUp4:DB( 6395):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6395): AppBoxApplication onCreate()
D/CAR.TEL.Service( 6361): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6361): Creating a new PhoneAdapter instance
D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 95035460020; DSPS: 3205603; Offset : -2796655177
W/ActivityManager(  849): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6361): setListener: com.google.android.gms.car.dn@38305376
W/ActivityManager(  849): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6361): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6361): Starting CarCallService with initial phone null
I/AppUp4:CustModeStarterReceiver( 6395): onReceive
I/AppUp4:CustModeStarterReceiver( 6395): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6395): Context : android.app.ReceiverRestrictedContext@315a02db
D/AppUp4:CustFacade( 6395): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6395): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6395): begin check event
I/AppUp4:CustModeStarterReceiver( 6395): Event For Nothing, skip.
I/NotificationManager( 6361): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  849): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6421 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5594): 
I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5594): 
,D/CAR.SERVICE( 6361): Package validated; name: com.android.vending
,I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5594): 
,I/ActivityManager(  849): Process com.google.android.gm (pid 6221) has died
W/ResourcesManager( 6421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6421): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6421): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/NotificationManager( 6125): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6125): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5594): 
,I/AppConfig( 6421): Total System Memory = 906309632
,I/GalleryUtils( 6421): Application Heap = 96 MB
I/AppConfig( 6421): App Tier : NOT_DEF
D/SystemHelper( 6421): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  849): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6442 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/ResourcesManager( 6442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6442): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6442): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6442): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6442): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6442): BUILD Country: EU
I/SystemConfig( 6442): BUILD Operator: OPEN
,I/art     (  849): Explicit concurrent mark sweep GC freed 20502(970KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.512ms total 148.429ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  849): android: cancelAsUser(2) by android
,I/ActivityManager(  849): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6462 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 411us total 23.703ms
,I/SystemConfig( 6442): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6442): existFile = false
I/SystemConfig( 6442): canReadFile = false
I/SystemConfig( 6442): systemFeature RCS result false
D/SystemConfig( 6442): refreshRcsSupport() :false
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 24.573ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 24.449ms
I/LockScreenSettings( 6462): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6462): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6462): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6462): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6462): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6462): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6479 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/qtaguid ( 6125): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6125): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6125): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6125): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 6125): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  849): RTC_WAKEUP set : Alarm{3410f0e4 type 0 when 1455021467379 com.android.vending} when 1455021467379
D/DeviceConnectionService( 1731): client connected with version: 8296000
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
D/Finsky  ( 6125): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6125): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  849): Killing 5958:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6177): android.os.DeadObjectException
,W/System.err( 6177): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6177): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6177): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6177): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6177): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6177): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6177): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6177): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6177): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6177): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6177): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6177): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6177): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6177): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6177): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6177): android.os.DeadObjectException
W/System.err( 6177): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6177): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6177): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6177): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6177): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6177): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6177): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6177): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6177): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6177): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6177): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6177): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6177): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6177): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6177): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ActivityManager(  849): Killing 6264:com.android.settings/1000 (adj 15): empty #12
,W/libprocessgroup(  849): failed to open /acct/uid_10089/pid_5958/cgroup.procs: No such file or directory
W/ActivityManager(  849): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_6264/cgroup.procs: No such file or directory
I/ActivityManager(  849): Killing 6295:com.lge.sync/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6508 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_6295/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Killing 6177:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 6508): Quickset Services start...
I/UEI.SmartControl( 6508): Manufacture = LGE
D/UEI.SmartControl( 6508): File observer start...
,E/UEI.SmartControl( 6508): IR Port is disabled: false
D/UEI.SmartControl( 6508): Starting file observer...
D/UEI.SmartControl( 6508): Extracting JNI libs...
D/UEI.SmartControl( 6508): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6508): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6508): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6508): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/libprocessgroup(  849): failed to open /acct/uid_10106/pid_6177/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UEI.SmartControl( 6508): --- Selecting new region: 2
,I/UEI.SmartControl( 6508): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6508): Platform has CIR...
D/UEI.SmartControl( 6508): NO CIR support, need to check package...
I/UEI.SmartControl( 6508): Model: LG-D722 uses JNI
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 40 ms] updated apps [took 40 ms] 
D/PackageBroadcastService( 5753): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/UEI.SmartControl( 6508): QS Service created
I/ActivityManager(  849): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6541 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5753): Null package name or gms related package.  Ignoreing.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5753): updateResources: need to parse f{com.google.android.gms}
E/UEI.SmartControl( 6508): QS start get config
,W/ResourcesManager( 6541): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6508): Loading JNI Libs...
,D/UEI.SmartControl( 6508):  configuring local db...
D/BluetoothManagerService(  849): Message: 20
D/BluetoothManagerService(  849): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24ed37f1:true
,D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
,D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
V/LGMDMManager( 6541): Create singleton instance
,I/AudioManager( 6541): getMode name:com.lge.qremote
,I/ActivityManager(  849): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6564 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6508):  ---- Has DB8: true
,D/UEI.SmartControl( 6508): QS start statue = true Error code = 0
D/UEI.SmartControl( 6508): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6508): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6508): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6508): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6508): IrrcClient ++ 
D/irrcClient( 6508): getIrrcService ++ 
D/irrcClient( 6508): getIrrcService -- 
D/irrcClient( 6508): IrrcClient -- 
W/irrc_jni( 6508): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6508): Services init done
I/UEI.SmartControl( 6508): Device manager: loading config....
D/UEI.SmartControl( 6508): QS Service init finished
,D/UEI.SmartControl( 6508): QS Service version name: 0.1.73
D/UEI.SmartControl( 6508): QS Service version code: 1073
D/UEI.SmartControl( 6508): Config is loaded...
D/UEI.SmartControl( 6508): Service requested: Control
D/UEI.SmartControl( 6508): Service.onUnbind: IControl
D/UEI.SmartControl( 6508): Service.onDestroy
D/UEI.SmartControl( 6508): Shutdown IRRCPlayer... 
W/irrc_jni( 6508): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6508): ~IrrcClient ++ 
D/irrcClient( 6508): ~IrrcClient -- 
W/irrc_jni( 6508): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6508): Blaster closed
D/UEI.SmartControl( 6508): Blaster closed
D/UEI.SmartControl( 6508): Shut down QS...
D/UEI.SmartControl( 6508): Stopped file observer...
,I/UEI.SmartControl( 6508): QS lib stop result = true
D/UEI.SmartControl( 6508): QS shutdown complete
D/UEI.SmartControl( 6508): QS Service created
I/UEI.SmartControl( 6508): Notify AllClients services are ready: 11
,E/UEI.SmartControl( 6508): QS start get config
,D/UEI.SmartControl( 6508):  configuring local db...
,I/MusicStore( 6564): Database version: 120
,D/UEI.SmartControl( 6508):  ---- Has DB8: true
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6564): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 6508): QS start statue = true Error code = 0
D/UEI.SmartControl( 6508): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6508): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6508): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6508): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6508): IrrcClient ++ 
D/irrcClient( 6508): getIrrcService ++ 
D/irrcClient( 6508): getIrrcService -- 
D/irrcClient( 6508): IrrcClient -- 
W/irrc_jni( 6508): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6508): Services init done
,D/UEI.SmartControl( 6508): QS Service init finished
D/UEI.SmartControl( 6508): QS Service version name: 0.1.73
D/UEI.SmartControl( 6508): QS Service version code: 1073
D/UEI.SmartControl( 6508): Service requested: Control
D/UEI.SmartControl( 6508): -----IControl: 11
D/UEI.SmartControl( 6508): File observer start...
I/UEI.SmartControl( 6508): Device manager: loading config....
E/UEI.SmartControl( 6508): IR Port is disabled: false
D/UEI.SmartControl( 6508): Starting file observer...
D/UEI.SmartControl( 6508): Caller: com.lge.qremote
D/UEI.SmartControl( 6508): ------------ IControl registerCallback...
I/UEI.SmartControl( 6508): Registering callback...
D/UEI.SmartControl( 6508): -----IControl: 19
D/UEI.SmartControl( 6508): Caller: com.lge.qremote
I/UEI.SmartControl( 6508): Registering Services Ready callback...
E/ActivityThread( 6508): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@ed8508d that was originally bound here
E/ActivityThread( 6508): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@ed8508d that was originally bound here
E/ActivityThread( 6508): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6508): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6508): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6508): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6508): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6508): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6508): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6508): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6508): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6508): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6508): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6508): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6508): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6508): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6508): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6508): Internal service binding...
,D/UEI.SmartControl( 6508): Config is loaded...
D/UEI.SmartControl( 6508):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6508): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6508): -----IControl: 8
D/UEI.SmartControl( 6508): Caller: com.lge.qremote
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6564): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6564): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6564): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6564): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6564): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6564): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6564): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2230deb2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6564): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6564): GMSCore installation verified
I/ConfigStore( 6564): Config Database version: 1
,I/MediaRouter( 6564): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6564): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6564): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  849): Killing 5876:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/Icing   ( 5753): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
W/libprocessgroup(  849): failed to open /acct/uid_10038/pid_5876/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6564): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  849): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6605 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Icing   ( 5753): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/GHttpClientFactory( 6564): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/UEI.SmartControl( 6508): Internal timer expired: 2
I/GoogleURLConnFactory( 6564): Using platform SSLCertificateSocketFactory
W/System.err( 6508): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ed8508d
,W/System.err( 6508): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
,W/System.err( 6508): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6508): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6508): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6508): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6508): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 6508): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6508): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ed8508d
I/ActivityManager(  849): Killing 6421:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ResourcesManager( 6605): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6605): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6605): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  849): Killing 6395:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  849): failed to open /acct/uid_10023/pid_6421/cgroup.procs: No such file or directory
W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_6395/cgroup.procs: No such file or directory
,I/NotificationManager( 6564): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6605): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6605): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  849): Process com.google.android.gms:car (pid 6361) has died
,W/ActivityManager(  849): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
D/eas_req ( 6605): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/AlertService( 6341): Beginning updateAlertNotification
,I/ActivityManager(  849): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6637 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6646 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/HubEmail( 6605): JNI_OnLoad()
I/HubEmail( 6605): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6605): registerNatives()
I/HubEmail( 6605): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6605): registerNativeMethods()
I/HubEmail( 6605): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6605): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6605): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 6646): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/LGDMClient( 6637): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6637): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6637): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6637): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/CalendarProvider2( 6646): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@219088c
,D/LGDMClient( 6637): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6637): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6685 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/CalendarProvider2( 6646): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6646): Created com.android.providers.calendar.CalendarAlarmManager@3c150051(com.android.providers.calendar.CalendarProvider2@219088c)
,W/ContextImpl( 6637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6637): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6637): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6637): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6637): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6637): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  849): Killing 5903:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10061/pid_5903/cgroup.procs: No such file or directory
I/ActivityManager(  849): Killing 6442:com.android.contacts/u0a18 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6685): onCreate
,W/AppUp4:DB( 6685):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6685):  setFingerPrint start
I/AppUp4:DB( 6685):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6685):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6685):  SDK version = 0
I/AppUp4:DB( 6685):  beforefinger == newfinger no write in DB
W/libprocessgroup(  849): failed to open /acct/uid_10018/pid_6442/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6685): AppBoxApplication onCreate()
D/AlertService( 6341): No fired or scheduled alerts
I/NotificationManager( 6341): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(4) by com.android.calendar
,I/NotificationManager( 6341): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(12) by com.android.calendar
I/NetworkStateForAutoUpdateMonitor( 6685): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6685): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NotificationManager( 6341): com.android.calendar: cancel(13) by com.android.calendar
I/NetworkStateForAutoUpdateMonitor( 6685): [onReceive] connect :true
I/NotificationManager( 6341): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(15) by com.android.calendar
I/NetworkStateForAutoUpdateMonitor( 6685): [onReceive] request level :IDLE....
I/NotificationManager( 6341): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(18) by com.android.calendar
I/AppUp4:CustModeStarterReceiver( 6685): onReceive
I/AppUp4:CustModeStarterReceiver( 6685): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,I/NotificationManager( 6341): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6341): com.android.calendar: cancel(20) by com.android.calendar
D/AppUp4:CustFacade( 6685): Context : android.app.ReceiverRestrictedContext@ab000b6
D/AppUp4:CustFacade( 6685): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6685): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6685): begin check event
I/AppUp4:CustModeStarterReceiver( 6685): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6685): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6685): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6685): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6685): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  849): Killing 6462:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/AlertService( 6341): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,W/libprocessgroup(  849): failed to open /acct/uid_10069/pid_6462/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Killing 6479:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/LgeMiscReceiver( 3233): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3233): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3233): networkInfo.isConnected() = false
,W/libprocessgroup(  849): failed to open /acct/uid_10086/pid_6479/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6712 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/AlarmScheduler( 6341): No events found starting within 1 week.
,I/ActivityManager(  849): Killing 6341:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10013/pid_6341/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6712): Register our PhoneStateListener
,I/art     (  849): Explicit concurrent mark sweep GC freed 16246(760KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.134ms total 143.506ms
,D/MobileConnectivityChangeReceiver( 6712): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6712): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  849): Killing 6125:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10036/pid_6125/cgroup.procs: No such file or directory
,V/DownloadManager( 3257): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 5753): Checkin interval check for package: unspecified last checkin: 1455021448703 min interval config: 0 actual interval: 23169
V/DownloadManager( 3257): DownloadService onCreate
,I/NotificationManager( 3257): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/PhoneMonitor( 6712): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/DownloadManager( 3257): in removeSpuriousFiles
,V/TelephonyAutoProfiling( 6712): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6712): [parse] Load xml
V/DownloadManager( 3257): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@57e391c on behalf of 3257
,I/ActivityManager(  849): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6750 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3257): DownloadService onStartCommand
I/CheckinService( 5753): Checking schedule, now: 1455021471920 next: 1455021478664
I/CheckinService( 5753): active receiver: disabled
V/TelephonyAutoProfiling( 6712): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6712): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3257): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 3257): in trimDatabase
V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 6712): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@1eb45afa on behalf of 3257
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@1ddf18ab on behalf of 3257
,V/DownloadManager( 3257): DownloadService onDestroy
,I/ActivityManager(  849): Killing 6541:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10106/pid_6541/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2731): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:52
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherAncestor( 2731): connectivity changed - connection : true
,D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2731): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:52
D/WeatherService( 2731): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  849): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6767 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  849): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.378ms
,D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 23.099ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.020ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6767): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6767): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6767): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6767): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6767): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6767): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6767): MmsConfig.loadFromResources
E/Babel_SMS( 6767): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6767): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6767): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6767): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6767): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6767): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6767): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6767): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6767): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6767): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6767): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6767): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6767): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6767): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6767): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6767): found sensor: LGE Absolute Motion Detector Sensor, handle=33
,D/SensorManager( 6767): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6767): found sensor: Motion Accel, handle=46
I/art     ( 6767): CheckpointMarkThreadRoots callback created = 0xaaf3d590
,W/Settings( 6767): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6767): startup - clean
I/Babel   ( 6767): deleted: false for 0
,I/art     ( 6767): CheckpointMarkThreadRoots callback created = 0xaaf3d570
,I/ActivityManager(  849): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6795 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6767): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6767): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6767): Unsupported mime audio/g726
,W/AudioCapabilities( 6767): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6767): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6767): Unsupported mime video/mjpg
W/VideoCapabilities( 6767): Unsupported mime video/theora
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
W/AudioCapabilities( 6767): Unsupported mime audio/evrc
W/AudioCapabilities( 6767): Unsupported mime audio/qcelp
W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6767): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6767): Unsupported mime audio/qcelp
W/AudioCapabilities( 6767): Unsupported mime audio/evrc
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/VideoCapabilities( 6767): Unsupported mime video/mp4v-esdp
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  849): battery changed pluggedType: 2
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
D/charger_monitor(  476): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/VideoCapabilities( 6767): Unsupported profile 4 for video/mp4v-es
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  849): battery changed pluggedType: 2
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/UEI.SmartControl( 6508): file observer is disposed!
,W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6767): onServiceConnected
,W/Babel   ( 6767): Attempted to change video mute state without an active call.
I/NotificationManager( 6767): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6767): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6767): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6767): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6767): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6767): propertyValue:false
I/Babel   ( 6767): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  849): Killing 6508:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10089/pid_6508/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6795): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6795):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6795):   adb logcat -s GAv4
,W/GAv4    ( 6795): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6795): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6795): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6795): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6795): Time to load native libraries: 6 ms (timestamps 3277-3283)
,I/LibraryLoader( 6795): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6795): Binding Chromium to main looper Looper (main, tid 1) {27bb829b}
,I/LibraryLoader( 6795): Expected native library version number "",actual native library version number ""
I/chromium( 6795): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6795): Initializing chromium process, singleProcess=true
,W/art     ( 6795): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6795): ApplicationContext is null in ApplicationStatus
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/chromium( 6795): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6795): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6795): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6795): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6795): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6795): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6795): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6795): Remote Branch: 
I/Adreno-EGL( 6795): Local Patches: 
I/Adreno-EGL( 6795): Reconstruct Branch: 
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
V/AudioPolicyService(  282): registerClient() client 0xb57eb0e0, uid 10079
,W/AudioManagerAndroid( 6795): Requires BLUETOOTH permission
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/NSApplication( 6795): Starting up...
I/ActivityManager(  849): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6864 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6564:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10081/pid_6564/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5594): 
,I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6892 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 6605:com.lge.email/u0a21 (adj 15): empty #11
I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5594): 
,I/jxcore-log( 5594): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5594): 
W/libprocessgroup(  849): failed to open /acct/uid_10021/pid_6605/cgroup.procs: No such file or directory
,W/ResourcesManager( 6892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5753): SYNC; picasa accounts
,D/NetworkLogImpl( 5753): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5753): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  849): Killing 6646:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/iu.UploadsManager( 5753): num queued entries: 0
I/iu.UploadsManager( 5753): num updated entries: 0
,I/iu.SyncManager( 5753): NEXT; no task
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  849): failed to open /acct/uid_10014/pid_6646/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6928 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6928): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6928): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6928): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6928): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 5594): Test app app.js loaded
I/jxcore-log( 5594): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5594): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5011608 added. We now have 1 listener(s)
,D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
V/JNIHelp ( 6928): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/jxcore-log( 5594): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5594): 
I/chromium( 5594): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ActivityThread( 6928): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6928): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2230deb2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6928): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6928): GMSCore installation verified
I/ConfigStore( 6928): Config Database version: 1
,I/MediaRouter( 6928): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6928): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6928): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NetworkMonitor( 6928): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  849): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6971 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6928): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6928): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  849): Killing 6637:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_6637/cgroup.procs: No such file or directory
,I/NotificationManager( 6928): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 6971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6971): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6971): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 6971): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6971): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6971): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  849): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7001 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6971): JNI_OnLoad()
I/HubEmail( 6971): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6971): registerNatives()
I/HubEmail( 6971): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6971): registerNativeMethods()
I/HubEmail( 6971): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6971): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  849): Killing 6685:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_6685/cgroup.procs: No such file or directory
W/Settings( 6971): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7001): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7001): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7001): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7001): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7001): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7001): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7001): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7001): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7025 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 7001): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7001): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7001): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7001): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7001): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7001): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  849): Killing 6712:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10038/pid_6712/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7025): onCreate
,W/AppUp4:DB( 7025):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7025):  setFingerPrint start
I/AppUp4:DB( 7025):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7025):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7025):  SDK version = 0
I/AppUp4:DB( 7025):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7025): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7025): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7025): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7025): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7025): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7025): onReceive
I/AppUp4:CustModeStarterReceiver( 7025): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7025): Context : android.app.ReceiverRestrictedContext@ab000b6
D/AppUp4:CustFacade( 7025): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7025): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7025): begin check event
I/AppUp4:CustModeStarterReceiver( 7025): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 7025): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7025): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7025): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7025): handleAsyncCustNotification do not startCustService
I/ActivityManager(  849): Killing 6750:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10051/pid_6750/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3233): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3233): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3233): networkInfo.isConnected() = false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  849): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7044 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/CheckinService( 5753): Done disabling old GoogleServicesFramework version
,D/PhoneMonitor( 7044): Register our PhoneStateListener
D/MobileConnectivityChangeReceiver( 7044): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7044): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  849): Killing 6767:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10061/pid_6767/cgroup.procs: No such file or directory
,V/DownloadManager( 3257): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3257): DownloadService onCreate
I/NotificationManager( 3257): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3257): in removeSpuriousFiles
V/DownloadManager( 3257): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  849): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7066 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/PhoneMonitor( 7044): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7044): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7044): [parse] Load xml
V/TelephonyAutoProfiling( 7044): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7044): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7044): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     (  849): Explicit concurrent mark sweep GC freed 20346(995KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.456ms total 176.981ms
,V/DownloadManager( 3257): DownloadService onStartCommand
V/DownloadManager( 3257): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@d749487 on behalf of 3257
I/DownloadManager( 3257): in trimDatabase
V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/CheckinService( 5753): Checkin interval check for package: unspecified last checkin: 1455021448703 min interval config: 0 actual interval: 29039
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@274e8fb4 on behalf of 3257
,V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@57437dd on behalf of 3257
I/CheckinService( 5753): Checking schedule, now: 1455021477771 next: 1455021478664
I/CheckinService( 5753): active receiver: disabled
,V/DownloadManager( 3257): DownloadService onDestroy
,I/ActivityManager(  849): Killing 6795:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10079/pid_6795/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2731): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:57
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherAncestor( 2731): connectivity changed - connection : true
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2731): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:57
D/WeatherService( 2731): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  849): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7090 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  849): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7090): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7090): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7090): MmsConfig.loadMmsSettings
I/Babel_SMS( 7090): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7090): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7090): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7090): MmsConfig.loadFromResources
E/Babel_SMS( 7090): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7090): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7090): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7090): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7090): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7090): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7090): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7090): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7090): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7090): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7090): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7090): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7090): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7090): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7090): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7090): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7090): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7090): found sensor: Motion Accel, handle=46
,W/Settings( 7090): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 7090): CheckpointMarkThreadRoots callback created = 0xb042d8c0
I/Babel_Crash( 7090): startup - clean
I/Babel   ( 7090): deleted: false for 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 7090): CheckpointMarkThreadRoots callback created = 0xb042d8a0
I/ActivityManager(  849): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7126 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.156ms
,W/AudioCapabilities( 7090): Unsupported mime audio/x-lg-flac
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.409ms
W/AudioCapabilities( 7090): Unsupported mime audio/adpcm
W/AudioCapabilities( 7090): Unsupported mime audio/g726
,W/AudioCapabilities( 7090): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7090): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7090): Unsupported mime video/mjpg
W/VideoCapabilities( 7090): Unsupported mime video/theora
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.864ms
,W/AudioCapabilities( 7090): Unsupported mime audio/evrc
,W/AudioCapabilities( 7090): Unsupported mime audio/qcelp
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7090): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7090): Unsupported mime audio/qcelp
W/AudioCapabilities( 7090): Unsupported mime audio/evrc
W/VideoCapabilities( 7090): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7090): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7090): onServiceConnected
,W/Babel   ( 7090): Attempted to change video mute state without an active call.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/libc-netbsd( 7090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager( 7090): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7090): propertyValue:false
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7126): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7126):   adb logcat -s GAv4
W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0,
W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7090): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  849): Killing 6864:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  849): failed to open /acct/uid_10048/pid_6864/cgroup.procs: No such file or directory
,I/WebViewFactory( 7126): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7126): Time to load native libraries: 1 ms (timestamps 8126-8127)
I/LibraryLoader( 7126): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7126): Binding Chromium to main looper Looper (main, tid 1) {27bb829b}
I/LibraryLoader( 7126): Expected native library version number "",actual native library version number ""
I/chromium( 7126): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7126): Initializing chromium process, singleProcess=true
,W/art     ( 7126): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7126): ApplicationContext is null in ApplicationStatus
W/chromium( 7126): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb57eb140, uid 10079
,W/AudioManagerAndroid( 7126): Requires BLUETOOTH permission
I/NSApplication( 7126): Starting up...
I/ActivityManager(  849): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7197 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6892:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10086/pid_6892/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7216 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 6928:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10081/pid_6928/cgroup.procs: No such file or directory
,W/ResourcesManager( 7216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  849): Killing 6971:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10021/pid_6971/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7240 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7240): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7240): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7240): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
D/WeatherService( 2731): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:38:0
D/WeatherService( 2731): 2 : TimeTick Intent And Screen On
W/ContextImpl( 7240): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/WeatherService( 2731): 2 : SDK version : 21
W/ActivityManager(  849): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2731): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherService( 2731): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2731): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2731): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2731): 2 : Fixed theme : optimus
,D/WeatherReflect( 2731): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
W/ResourcesManager( 7240): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7240): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/lim     ( 2731): 2 : time = 13:38
,I/WeatherReflect( 2731): Model Name : LG-D722
D/WeatherTheme( 2731): 2 : Different view - status_min_formatted : 37 != 38
D/WeatherTheme( 2731): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2731): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2731): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]Clock( 1372): called onTimeUpdated()
,V/JNIHelp ( 7240): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Weather4x2_optimus( 2731): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2731): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2731): forecast size is 0
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2731): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2731): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2731): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2731): url is : null
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2731): 2 : update view, appWidgetId: 2
D/WeatherService( 2731): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:38:0
,W/ActivityThread( 7240): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7240): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2230deb2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7240): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7240): GMSCore installation verified
,I/ConfigStore( 7240): Config Database version: 1
,I/MediaRouter( 7240): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7240): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7240): type=WIFI subType= reason=null isConnected=true
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/NetworkMonitor( 7240): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  849): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7276 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/GHttpClientFactory( 7240): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7240): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  849): Killing 7001:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7276): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7276): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7276): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_7001/cgroup.procs: No such file or directory
,I/NotificationManager( 7240): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7276): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7276): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7276): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  849): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7304 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7276): JNI_OnLoad()
I/HubEmail( 7276): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7276): registerNatives()
I/HubEmail( 7276): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7276): registerNativeMethods()
I/HubEmail( 7276): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7276): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7276): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  849): Killing 7025:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_7025/cgroup.procs: No such file or directory
,D/LGDMClient( 7304): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7304): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7304): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7304): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7304): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7304): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7328 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7304): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7304): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7304): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7304): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7304): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  849): Killing 7044:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10038/pid_7044/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7328): onCreate
W/AppUp4:DB( 7328):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7328):  setFingerPrint start
I/AppUp4:DB( 7328):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7328):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7328):  SDK version = 0
I/AppUp4:DB( 7328):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7328): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7328): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7328): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7328): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7328): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7328): onReceive
I/AppUp4:CustModeStarterReceiver( 7328): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7328): Context : android.app.ReceiverRestrictedContext@ab000b6
D/AppUp4:CustFacade( 7328): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7328): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7328): begin check event
I/AppUp4:CustModeStarterReceiver( 7328): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7328): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7328): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7328): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7328): handleAsyncCustNotification do not startCustService
I/ActivityManager(  849): Killing 7066:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10051/pid_7066/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3233): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3233): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3233): networkInfo.isConnected() = true
,D/PhoneState( 3233): setPdpRejectCasuse : false
,I/ActivityManager(  849): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7347 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7347): Register our PhoneStateListener
,V/AlarmManager(  849): RTC_WAKEUP set : Alarm{23f30715 type 0 when 1455021478664 com.google.android.gms} when 1455021478664
I/ActivityManager(  849): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7364 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  849): RTC_WAKEUP set : Alarm{4c95b8 type 0 when 1455021481249 com.android.vending} when 1455021481249
,D/MobileConnectivityChangeReceiver( 7347): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7347): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  849): Killing 7090:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7347): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7347): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7347): [parse] Load xml
V/TelephonyAutoProfiling( 7347): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7347): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7347): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  849): failed to open /acct/uid_10061/pid_7090/cgroup.procs: No such file or directory
,V/DownloadManager( 3257): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3257): DownloadService onCreate
,I/NotificationManager( 3257): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3257): in removeSpuriousFiles
V/DownloadManager( 3257): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@dfbf223 on behalf of 3257
I/DownloadManager( 3257): in trimDatabase
V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@200174d9 on behalf of 3257
I/ActivityManager(  849): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7386 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3257): DownloadService onStartCommand
V/DownloadManager( 3257): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@38118d7f on behalf of 3257
,I/art     (  849): Explicit concurrent mark sweep GC freed 19662(975KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.160ms total 141.129ms
,I/CheckinService( 5753): Checkin interval check for package: unspecified last checkin: 1455021448703 min interval config: 0 actual interval: 32879
V/DownloadManager( 3257): DownloadService onDestroy
,I/CheckinService( 5753): Checking schedule, now: 1455021481599 next: 1455021478664
I/CheckinService( 5753): active receiver: enabled
,I/CheckinService( 5753): Preparing to send checkin request
I/EventLogService( 5753): Accumulating logs since 1455021439934
,D/WeatherAncestor( 2731): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:1
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherAncestor( 2731): connectivity changed - connection : true
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2731): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:1
D/WeatherService( 2731): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  849): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7409 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  849): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/Finsky  ( 7364): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 7409): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5753): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5753): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 7364): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7364): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7364): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7364): com.android.vending: cancel(-1050172287) by com.android.vending
,I/Babel_SMS( 7409): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7409): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7409): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7409): MmsConfig.loadFromDatabase
I/art     ( 3996): Explicit concurrent mark sweep GC freed 2173(80KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 701us total 83.358ms
D/Ads     ( 7364): Skipping gmscore version check
,D/Finsky  ( 7364): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7364): [1] Libraries$2.run: Finished loading 1 libraries.
,E/Babel_SMS( 7409): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7409): MmsConfig.loadFromResources
E/Babel_SMS( 7409): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7409): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7409): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7409): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7409): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7409): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7409): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7409): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7409): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7409): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7409): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7409): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7409): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7409): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7409): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7409): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7409): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7409): found sensor: Motion Accel, handle=46
,I/art     ( 7409): CheckpointMarkThreadRoots callback created = 0xaaf3d4d0
,I/art     ( 7409): CheckpointMarkThreadRoots callback created = 0xaaf3d4a0
,D/Finsky  ( 7364): [940] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7364): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  849): Process com.google.android.apps.magazines (pid 7126) has died
,V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@2a8b8595 on behalf of 7364
W/Settings( 7409): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7409): startup - clean
D/Finsky  ( 7364): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7364): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel   ( 7409): deleted: false for 0
I/ActivityManager(  849): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7466 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 22.761ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.421ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.333ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AudioCapabilities( 7409): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7409): Unsupported mime audio/adpcm
W/AudioCapabilities( 7409): Unsupported mime audio/g726
W/AudioCapabilities( 7409): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7409): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7409): Unsupported mime video/mjpg
,W/VideoCapabilities( 7409): Unsupported mime video/theora
W/AudioCapabilities( 7409): Unsupported mime audio/evrc
,W/AudioCapabilities( 7409): Unsupported mime audio/qcelp
W/VideoCapabilities( 7409): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7409): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7409): Unsupported mime audio/qcelp
W/AudioCapabilities( 7409): Unsupported mime audio/evrc
,W/VideoCapabilities( 7409): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7409): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7409): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7409): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7409): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7409): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  849): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7486 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/vclib   ( 7409): onServiceConnected
W/Babel   ( 7409): Attempted to change video mute state without an active call.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7466): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7466): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/NotificationManager( 7409): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7409): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7409): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7409): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7409): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7409): propertyValue:false
,I/GAv4    ( 7466): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7466):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7466):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7466): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,W/ResourcesManager( 7486): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7486): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 7466): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7466): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7409): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  849): Killing 7197:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7466): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7466): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/MultiDex( 7486): VM with version 2.1.0 has multidex support
I/MultiDex( 7486): install
I/MultiDex( 7486): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  849): failed to open /acct/uid_10048/pid_7197/cgroup.procs: No such file or directory
,V/JNIHelp ( 7486): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7486): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7486): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ddf18ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7486): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7486): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7486): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7486): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7486): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/WebViewFactory( 7466): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/WVCdm   (  282): Instantiating CDM.
I/WVCdm   (  282): CdmEngine::OpenSession
,I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
D/NativeLibraryUtils( 7486): Install completed successfully. count=14 extracted=0
I/LibraryLoader( 7466): Time to load native libraries: 2 ms (timestamps 2392-2394)
I/LibraryLoader( 7466): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7466): Binding Chromium to main looper Looper (main, tid 1) {27bb829b}
I/LibraryLoader( 7466): Expected native library version number "",actual native library version number ""
I/chromium( 7466): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
I/BrowserStartupController( 7466): Initializing chromium process, singleProcess=true
,W/art     ( 7466): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7466): ApplicationContext is null in ApplicationStatus
W/chromium( 7466): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7466): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7466): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7466): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7466): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7466): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7466): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7466): Remote Branch: 
I/Adreno-EGL( 7466): Local Patches: 
I/Adreno-EGL( 7466): Reconstruct Branch: 
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=989128951
V/AudioPolicyService(  282): registerClient() client 0xb551cd40, uid 10079
,W/AudioManagerAndroid( 7466): Requires BLUETOOTH permission
I/NSApplication( 7466): Starting up...
,I/ActivityManager(  849): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7556 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 7216:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10086/pid_7216/cgroup.procs: No such file or directory
,I/art     ( 7486): CheckpointMarkThreadRoots callback created = 0xb04d3dc0
,I/art     ( 7486): CheckpointMarkThreadRoots callback created = 0xb04d3db0
I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7575 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 7240:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10081/pid_7240/cgroup.procs: No such file or directory
,I/dex2oat ( 7580): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ResourcesManager( 7575): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/dex2oat ( 7580): dex2oat took 101.072ms (threads: 4)
,I/Adreno-EGL( 7486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7486): Remote Branch: 
I/Adreno-EGL( 7486): Local Patches: 
I/Adreno-EGL( 7486): Reconstruct Branch: 
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/ActivityManager(  849): Killing 7276:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10021/pid_7276/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7609 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 7609): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7609): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@219088c
,D/CalendarProvider2( 7609): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7609): Created com.android.providers.calendar.CalendarAlarmManager@3c150051(com.android.providers.calendar.CalendarProvider2@219088c)
D/CalendarProviderBroadcastReceiver( 7609): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7609): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7609): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7609): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7609): [getOrCreateCalendarAlarmManager]
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  849): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7631 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/CalendarProvider2( 7609): [IntentService] Release Lock
,D/CalendarProvider2( 7609): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  849): Killing 7304:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_7304/cgroup.procs: No such file or directory
,W/ResourcesManager( 7631): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  849): Message: 20
D/BluetoothManagerService(  849): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19c35343:true
,D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
D/BluetoothAdapterService(249057421)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@329d58cb
I/ActivityManager(  849): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7649 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7631): Create singleton instance
,I/AudioManager( 7631): getMode name:com.lge.qremote
D/UEI.SmartControl( 7649): Quickset Services start...
,I/UEI.SmartControl( 7649): Manufacture = LGE
I/AudioManager( 7631): getMode name:com.lge.qremote
D/UEI.SmartControl( 7649): File observer start...
,E/UEI.SmartControl( 7649): IR Port is disabled: false
D/UEI.SmartControl( 7649): Starting file observer...
D/UEI.SmartControl( 7649): Extracting JNI libs...
D/UEI.SmartControl( 7649): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  849): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7673 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7649): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7649): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7649): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7649): --- Selecting new region: 2
,I/UEI.SmartControl( 7649): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7649): Platform has CIR...
,D/UEI.SmartControl( 7649): NO CIR support, need to check package...
I/UEI.SmartControl( 7649): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7649): QS Service created
E/UEI.SmartControl( 7649): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7649): Loading JNI Libs...
,D/UEI.SmartControl( 7649):  configuring local db...
W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
I/art     (  849): Explicit concurrent mark sweep GC freed 23722(1106KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.238ms total 157.871ms
D/WVCdm   (  282): PrepareKeyRequest: nonce=2585854303
D/UEI.SmartControl( 7649):  ---- Has DB8: true
,D/UEI.SmartControl( 7649): QS start statue = true Error code = 0
D/UEI.SmartControl( 7649): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7649): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/Gmail   ( 7673): getAccountsCursor
,D/UEI.SmartControl( 7649): IRRCDataComm has AudioManager!!!!.
W/GAV2    ( 7673): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/irrc_jni( 7649): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7649): IrrcClient ++ 
D/irrcClient( 7649): getIrrcService ++ 
D/irrcClient( 7649): getIrrcService -- 
D/irrcClient( 7649): IrrcClient -- 
W/irrc_jni( 7649): IRRCPlayer_nativeInit -- 
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7649): Services init done
I/UEI.SmartControl( 7649): Device manager: loading config....
D/UEI.SmartControl( 7649): QS Service init finished
D/UEI.SmartControl( 7649): Config is loaded...
D/UEI.SmartControl( 7649): QS Service version name: 0.1.73
D/UEI.SmartControl( 7649): QS Service version code: 1073
,D/UEI.SmartControl( 7649): Service requested: Control
D/UEI.SmartControl( 7649): Internal service binding...
D/UEI.SmartControl( 7649): -----IControl: 11
D/UEI.SmartControl( 7649): Caller: com.lge.qremote
D/UEI.SmartControl( 7649): ------------ IControl registerCallback...
I/UEI.SmartControl( 7649): Registering callback...
D/UEI.SmartControl( 7649): -----IControl: 19
D/UEI.SmartControl( 7649): Caller: com.lge.qremote
I/UEI.SmartControl( 7649): Registering Services Ready callback...
I/UEI.SmartControl( 7649): Notify client services are ready...
,D/UEI.SmartControl( 7649): -----IControl: 8
D/UEI.SmartControl( 7649): Caller: com.lge.qremote
I/ActivityManager(  849): Killing 7328:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 7649):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7649): Notify AllClients services are ready: 0
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_7328/cgroup.procs: No such file or directory
D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 115043095012; DSPS: 3861213; Offset : -2796649892
W/ActivityManager(  849): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  849): Killing 7347:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/Gmail   ( 7673): Observing account changes for notifications
W/libprocessgroup(  849): failed to open /acct/uid_10038/pid_7347/cgroup.procs: No such file or directory
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 7673): Error finding the version of the Email provider.....
E/Gmail   ( 7673): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7673): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7673): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7673): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7673): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7673): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7673): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7673): getAccountsCursor
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  849): Killing 7386:com.lge.drmservice/u0a51 (adj 15): empty #11
,E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/libprocessgroup(  849): failed to open /acct/uid_10051/pid_7386/cgroup.procs: No such file or directory
,D/LocationInitializer( 5753): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,I/AudioManager( 7631): getMode name:com.lge.qremote
,D/Finsky  ( 7364): [945] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/AudioManager( 7631): getMode name:com.lge.qremote
,I/ActivityManager(  849): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7741 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7673): notifyAccountChanged
I/NotificationManager(  849): android: cancelAsUser(2) by android
,I/Gmail   ( 7673): getAccountsCursor
I/Gmail   ( 7673): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7673): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7673): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7673): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd( 7364): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7364): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7364): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7364): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 7741): Register our PhoneStateListener
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 7741): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7741): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7741): [parse] Load xml
V/TelephonyAutoProfiling( 7741): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7741): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,D/PhoneMonitor( 7741): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/System.out( 7364): propertyValue:false
I/CheckinService( 5753): Checkin interval check for package: unspecified last checkin: 1455021448703 min interval config: 0 actual interval: 37895
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5753): Checkin interval check for package: unspecified last checkin: 1455021448703 min interval config: 0 actual interval: 37910
,E/MDM     ( 1731): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5753): Restart initialization of location
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/MusicWidget( 2662): mDelayedStopHandler : unbind
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,I/AudioManager( 7631): getMode name:com.lge.qremote
I/Gmail   ( 7673): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicBrowser( 2749): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/AudioManager( 7631): getMode name:com.lge.qremote
I/MusicBrowser( 2749): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2749): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
W/ContextImpl( 3638): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/AudioManager( 7631): getMode name:com.lge.qremote
,D/MusicBrowser( 2749): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2749): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2749): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2749): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  849):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@eccd754com.lge.music.MediaPlaybackService$6@15cb76fd
D/MusicBrowser( 2749): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/AudioManager( 7631): getMode name:com.lge.qremote
I/MusicBrowser( 2749): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@14b37242
,I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/AudioManager( 7631): getMode name:com.lge.qremote
I/MusicBrowser( 2749): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2749): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2749): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2749): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2749): reset
I/AudioManager( 7631): getMode name:com.lge.qremote
V/MediaPlayer[Native]( 2749): setListener
V/MediaPlayer[Native]( 2749): disconnect
V/MediaPlayer[Native]( 2749): destructor
,V/AudioFlinger(  282): releasing 18 from 2749 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2749): disconnect
D/MusicBrowser( 2749): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2749): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2749): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2749): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2749): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2749): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2749): [SmartShareManagerClient] unregisterListener: 177270770
W/SmartShareClient( 2749): [SmartShareManagerClient] unregisterListener invalid listener: 177270770
I/SmartShareClient( 2749): [SmartShareManagerClient] terminate service: 2749/MediaPlaybackService/9707896
E/HomeCloudIF( 2749): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2749): [SmartShareManagerClient] unbindService context:android.app.Application@2ffe1643
V/CloudHub( 2749): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2749): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2749): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2749): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2749): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  849): Killing 7466:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CloudHub( 2749): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
W/libprocessgroup(  849): failed to open /acct/uid_10079/pid_7466/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Killing 7556:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10048/pid_7556/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
,I/Adreno-EGL( 7486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7486): Remote Branch: 
I/Adreno-EGL( 7486): Local Patches: 
I/Adreno-EGL( 7486): Reconstruct Branch: 
,I/Adreno-EGL( 7486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7486): Remote Branch: 
I/Adreno-EGL( 7486): Local Patches: 
I/Adreno-EGL( 7486): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5753): Classify the device as Phone.
,D/libc-netbsd( 5753): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5753): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5753): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5753): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5753): propertyValue:false
D/libc-netbsd( 5753): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5753): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5753): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5753): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5753): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5753): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5753): Sending checkin request (9766 bytes)
,I/CheckinRequestBuilder( 5753): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5753): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5753): Classify the device as Phone.
,I/CheckinTask( 5753): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5753): Checking schedule, now: 1455021489462 next: 1455548738452
I/CheckinService( 5753): active receiver: disabled
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
I/CheckinService( 5753): Checking schedule, now: 1455021489500 next: 1455548738452
I/CheckinService( 5753): active receiver: disabled
,D/CheckinService( 5753): Recording last checkin time for package unspecified as 1455021489509
V/SetupWizard( 7741): Connected to Gservices successfully
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7649): Internal timer expired: 1
,I/GAV2    ( 7673): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  849): Killing 7609:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  849): Killing 7575:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  849): failed to open /acct/uid_10014/pid_7609/cgroup.procs: No such file or directory
,W/libprocessgroup(  849): failed to open /acct/uid_10086/pid_7575/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1829): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  849): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  849): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1784): Background sticky concurrent mark sweep GC freed 90179(5MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 8MB/14MB, paused 1ms total 129.722ms
,I/art     (  849): Explicit concurrent mark sweep GC freed 18168(890KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.401ms total 256.711ms
,I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7842 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationService(  849): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  849): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  849): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  849): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  849): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  849): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@fb6f97a
I/NotificationManager( 7409): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7409): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7409): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 7842): onCreate
W/ResourcesManager(  849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/AppUp4:DB( 7842):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7842):  setFingerPrint start
I/AppUp4:DB( 7842):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
V/JNIHelp ( 7409): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 7842):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7842):  SDK version = 0
I/AppUp4:DB( 7842):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7842): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7842): onReceive
I/AppUp4:CustModeStarterReceiver( 7842): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7842): Context : android.app.ReceiverRestrictedContext@315a02db
D/AppUp4:CustFacade( 7842): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7842): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7842): begin check event
I/AppUp4:CustModeStarterReceiver( 7842): Event For Nothing, skip.
I/ActivityManager(  849): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7862 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/System  ( 7409): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7409): Installed default security provider GmsCore_OpenSSL
,W/ResourceType(  849): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/ResourcesManager( 7862): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7862): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7862): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  849): applying state to connected service
,I/AppConfig( 7862): Total System Memory = 906309632
,I/GalleryUtils( 7862): Application Heap = 96 MB
I/AppConfig( 7862): App Tier : NOT_DEF
D/SystemHelper( 7862): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  849): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7883 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  849): Killing 7364:com.android.vending/u0a36 (adj 15): empty #11
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.480ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.899ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.679ms
,W/libprocessgroup(  849): failed to open /acct/uid_10036/pid_7364/cgroup.procs: No such file or directory
,W/ResourcesManager( 7883): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7883): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7883): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7883): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7883): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7883): BUILD Country: EU
I/SystemConfig( 7883): BUILD Operator: OPEN
,I/SystemConfig( 7883): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7883): existFile = false
I/SystemConfig( 7883): canReadFile = false
I/SystemConfig( 7883): systemFeature RCS result false
D/SystemConfig( 7883): refreshRcsSupport() :false
,I/ActivityManager(  849): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7908 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 2749:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  282): 2749 died, releasing its sessions
V/AudioFlinger(  282):  pid 1749 @ 0
V/AudioFlinger(  282):  pid 3233 @ 1
V/AudioFlinger(  282):  pid 3233 @ 2
,W/libprocessgroup(  849): failed to open /acct/uid_10028/pid_2749/cgroup.procs: No such file or directory
,I/LockScreenSettings( 7908): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7908): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7908): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7908): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7908): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7908): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  849): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7925 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 7673:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10053/pid_7673/cgroup.procs: No such file or directory
,W/ResourcesManager( 7925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,I/ActivityManager(  849): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7950 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 7741:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10038/pid_7741/cgroup.procs: No such file or directory
,D/Finsky  ( 7950): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7950): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7950): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7950): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7950): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3257): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3257): created cursor android.database.sqlite.SQLiteCursor@65976aa on behalf of 7950
,D/Finsky  ( 7950): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7950): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7950): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7950): Skipping gmscore version check
D/PackageBroadcastService( 5753): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5753): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7950): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 5753): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/Icing   ( 5753): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5753): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  849): Killing 7649:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7631): android.os.DeadObjectException
,W/System.err( 7631): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7631): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7631): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7631): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7631): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7631): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7631): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7631): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7631): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7631): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7631): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7631): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7631): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7631): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7631): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7631): android.os.DeadObjectException
W/System.err( 7631): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7631): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7631): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7631): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7631): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7631): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7631): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7631): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7631): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7631): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7631): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7631): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7631): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7631): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7631): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  849): failed to open /acct/uid_10089/pid_7649/cgroup.procs: No such file or directory
W/ActivityManager(  849): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  849): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8011 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
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
D/UEI.SmartControl( 8011): QS version = v2.7.11.1_RC1
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
D/UEI.SmartControl( 8011): Config is loaded...
D/UEI.SmartControl( 8011): QS Service version name: 0.1.73
D/UEI.SmartControl( 8011): QS Service version code: 1073
D/UEI.SmartControl( 8011): Service requested: Control
I/ActivityManager(  849): Killing 7486:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
D/UEI.SmartControl( 8011): -----IControl: 11
,D/UEI.SmartControl( 8011): Caller: com.lge.qremote
D/UEI.SmartControl( 8011): ------------ IControl registerCallback...
I/UEI.SmartControl( 8011): Registering callback...
D/UEI.SmartControl( 8011): -----IControl: 19
D/UEI.SmartControl( 8011): Caller: com.lge.qremote
I/UEI.SmartControl( 8011): Registering Services Ready callback...
I/UEI.SmartControl( 8011): Notify client services are ready...
D/UEI.SmartControl( 8011): -----IControl: 8
D/UEI.SmartControl( 8011): Caller: com.lge.qremote
,D/UEI.SmartControl( 8011):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 8011): Notify AllClients services are ready: 0
W/libprocessgroup(  849): failed to open /acct/uid_10006/pid_7486/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8011): Internal service binding...
,I/AudioManager( 7631): getMode name:com.lge.qremote
I/AudioManager( 7631): getMode name:com.lge.qremote
,I/AudioManager( 7631): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  849): Killing 7409:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10061/pid_7409/cgroup.procs: No such file or directory
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
,D/WifiController(  849): battery changed pluggedType: 2
D/LEDHandler( 1801): Battery Level Remaining: 100%
,D/LEDHandler( 1801): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  476): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 8011): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 135043804380; DSPS: 4516597; Offset : -2796672373
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{3d96acf type 2 when 145626 com.google.android.gms} when 145626
,I/PerfProfileCollectorService( 5753): Turn off PerfProfile Collection
,D/PerfProfileCollectorService( 5753): removeStateFiles() called
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1731): Vacuum at: now=1455021516867 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  849): ALS enabled for SRE
,D/PowerManagerServiceEx(  849): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (31148 ms ago)
,D/qdlights(  849): set_light_backlight: 251
,D/qdlights(  849): set_light_backlight: 248
,D/qdlights(  849): set_light_backlight: 245
,D/qdlights(  849): set_light_backlight: 241
,D/qdlights(  849): set_light_backlight: 238
,D/qdlights(  849): set_light_backlight: 235
,D/qdlights(  849): set_light_backlight: 231
,D/qdlights(  849): set_light_backlight: 228
,D/qdlights(  849): set_light_backlight: 225
,D/qdlights(  849): set_light_backlight: 221
,D/qdlights(  849): set_light_backlight: 218
,D/qdlights(  849): set_light_backlight: 215
,D/qdlights(  849): set_light_backlight: 211
,D/qdlights(  849): set_light_backlight: 208
,D/qdlights(  849): set_light_backlight: 205
,D/qdlights(  849): set_light_backlight: 201
,D/qdlights(  849): set_light_backlight: 198
,D/qdlights(  849): set_light_backlight: 195
,D/qdlights(  849): set_light_backlight: 191
,D/qdlights(  849): set_light_backlight: 188
,D/qdlights(  849): set_light_backlight: 185
,D/qdlights(  849): set_light_backlight: 181
,D/qdlights(  849): set_light_backlight: 178
,D/qdlights(  849): set_light_backlight: 175
,D/qdlights(  849): set_light_backlight: 171
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  849): set_light_backlight: 168
,D/qdlights(  849): set_light_backlight: 165
,D/qdlights(  849): set_light_backlight: 161
,D/qdlights(  849): set_light_backlight: 158
,D/qdlights(  849): set_light_backlight: 155
,D/qdlights(  849): set_light_backlight: 151
,D/qdlights(  849): set_light_backlight: 148
,D/qdlights(  849): set_light_backlight: 145
,D/qdlights(  849): set_light_backlight: 141
,D/qdlights(  849): set_light_backlight: 138
,D/qdlights(  849): set_light_backlight: 135
,D/qdlights(  849): set_light_backlight: 131
,D/qdlights(  849): set_light_backlight: 128
,D/qdlights(  849): set_light_backlight: 125
,D/qdlights(  849): set_light_backlight: 121
,D/qdlights(  849): set_light_backlight: 118
,D/qdlights(  849): set_light_backlight: 115
,D/qdlights(  849): set_light_backlight: 111
,D/qdlights(  849): set_light_backlight: 108
,D/qdlights(  849): set_light_backlight: 105
,D/qdlights(  849): set_light_backlight: 101
,D/qdlights(  849): set_light_backlight: 98
,D/qdlights(  849): set_light_backlight: 95
,D/qdlights(  849): set_light_backlight: 91
,D/qdlights(  849): set_light_backlight: 88
,D/qdlights(  849): set_light_backlight: 85
,D/qdlights(  849): set_light_backlight: 81
,D/qdlights(  849): set_light_backlight: 78
,D/qdlights(  849): set_light_backlight: 75
,D/qdlights(  849): set_light_backlight: 71
,D/qdlights(  849): set_light_backlight: 68
,D/qdlights(  849): set_light_backlight: 65
,D/qdlights(  849): set_light_backlight: 61
,D/qdlights(  849): set_light_backlight: 58
,D/qdlights(  849): set_light_backlight: 55
,D/qdlights(  849): set_light_backlight: 51
,D/qdlights(  849): set_light_backlight: 48
,D/qdlights(  849): set_light_backlight: 45
,D/qdlights(  849): set_light_backlight: 41
,D/qdlights(  849): set_light_backlight: 38
,D/qdlights(  849): set_light_backlight: 35
,D/qdlights(  849): set_light_backlight: 31
,D/qdlights(  849): set_light_backlight: 28
,D/qdlights(  849): set_light_backlight: 25
,D/qdlights(  849): set_light_backlight: 21
,D/qdlights(  849): set_light_backlight: 18
,D/qdlights(  849): set_light_backlight: 15
,D/qdlights(  849): set_light_backlight: 11
,D/qdlights(  849): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 155044477445; DSPS: 5171979; Offset : -2796670773
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  849): ALS enabled for SRE
D/PowerManagerServiceEx(  849): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (38143 ms ago)
I/PowerManagerService(  849): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  849): ALS enabled for SRE
D/PowerManagerServiceEx(  849): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (38156 ms ago)
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  849): Sleeping (uid 1000)...
D/LPWGController(  849): [updateScreenState] screen on = false
D/LPWGController(  849): disable proximity sensor
,D/LPWGController(  849): enable proximity sensor
I/SensorManager(  849): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@782f7d5] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  849): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  849): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  849): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  849): activate: handle is 48, enable
V/sensors_hal_Ctx(  849): activate sensors is 1400000000000
D/sensors_hal_Thresh(  849): enable: handle=48
I/sensors_hal_SAM(  849): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  849): waitForResponse: timeout=1000
V/sensors_hal_SAM(  849): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  849): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  849): enable: Received response: 0
D/PowerManagerServiceEx(  849): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (38194 ms ago)
I/Adreno-EGL(  849): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  849): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  849): Build Date: 03/02/15 Mon
I/Adreno-EGL(  849): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  849): Remote Branch: 
I/Adreno-EGL(  849): Local Patches: 
I/Adreno-EGL(  849): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1046 us)
,I/Sensors (  411): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  849): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  849): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  849): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  849): processInd: handle 48, count=1
V/sensors_hal_Thresh(  849): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  849): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  849): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  849): poll: count: 256
I/sensors_hal_Ctx(  849): poll: released wakelock sensor_ind
D/sensors_hal_Util(  849): waitForResponse: timeout=0
D/LPWGController(  849): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  849): current mode = 1  value = 1 1
I/LPWGController(  849): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  849): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/qdlights(  849): set_light_backlight: 0
,I/SensorManager(  849): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  849): activate: handle is 46, disable
,V/sensors_hal_Ctx(  849): activate sensors is 1000000000000
D/sensors_hal_LP2(  849): enable: handle=46
D/sensors_hal_LP2(  849): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  849): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  849): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  849): Display changed displayId=0
,V/sensors_hal_SAM(  849): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  849): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  849): Excessive delay in setPowerMode(): 234ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  849): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/KeyguardViewMediator( 1372): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1372): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/WifiServerServiceExt(  849): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 849
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
,V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WifiServerServiceExt(  849): set CMD_KT_SCAN_INTERVAL
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/GpsLocationProvider(  849): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1829): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1801): stopPatternFlashing()
D/Cliptray Service( 1801): lockStatus = 0
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
,D/Ulp_jni (  849): JNI:system_update. Event-0
,D/SplitWindow(  849): check instance of lgWin Window{279ecd78 u0 SearchPanel}
,D/InputDispatcher(  849): Window went away: Window{49064f9 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,I/Sensors (  411): sns_pwr.c(301):releasing wakelock
,I/art     (  849): Explicit concurrent mark sweep GC freed 44771(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 4.421ms total 252.389ms
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2731): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:38:50
,D/WeatherService( 2731): 2 : ACTION screen on
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2731): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:38:50
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): ACTION_SCREEN_ON
,D/AppCleanupService( 4130): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 849
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  849): CMD_SCREEN_OFF 
D/WifiController(  849): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  849): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1829): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2731): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:38:50
D/WeatherService( 2731): 2 : ACTION screen off
D/WeatherService( 2731): 2 : TimeTick Receiver Unregister
D/WeatherService( 2731): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:38:50
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  849): ACTION_SCREEN_OFF
D/AppCleanupService( 4130): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4130): AppUsageStatsSaveTask
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
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  476): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  849): battery changed pluggedType: 2
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  849): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{24083c51 type 2 when 164071 com.android.systemui} when 164071
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 175045334885; DSPS: 5827367; Offset : -2796668293
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  849): acquireWakeLockInternal: lock=294161590, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=849
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{1cc78db7 type 2 when 182084 android} when 182084
D/PowerManagerServiceEx(  849): releaseWakeLockInternal: lock=294161590 [*alarm*], flags=0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  476): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  849): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{20af4924 type 2 when 190193 com.google.android.gms} when 190193
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 10962 seconds from now (1455021561319)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
I/art     ( 1731): Explicit concurrent mark sweep GC freed 51569(3MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/22MB, paused 1.975ms total 128.148ms
,D/LocationManagerService(  849): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  849): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  849): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  849): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  849): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 195046009148; DSPS: 6482749; Offset : -2796665183
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 215046677630; DSPS: 7138131; Offset : -2796667827
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 235047418195; DSPS: 7793515; Offset : -2796660022
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  476): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  849): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  849): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  849): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 255048171000; DSPS: 8448900; Offset : -2796670053
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 275048851409; DSPS: 9104282; Offset : -2796660615
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/jxcore-log( 5594): --= Surplus to requirements =--
I/jxcore-log( 5594): 
I/jxcore-log( 5594): ****TEST TOOK:  ms ****
I/jxcore-log( 5594): 
I/jxcore-log( 5594): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5594): 
,D/AndroidRuntime( 8211): 
D/AndroidRuntime( 8211): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8211): CheckJNI is OFF
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/AndroidRuntime( 8211): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  849): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  849): Killing 5594:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  849): WIN DEATH: Window{b84c721 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  849): Focus left window: Window{b84c721 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  849): Window went away: Window{b84c721 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  849): Skipping PackageSetting{31da793b com.example.hello/10317} due to missing metadata
,I/ActivityManager(  849):   Force finishing activity ActivityRecord{7cc6ce0 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  849): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
,W/ActivityManager(  849): Spurious death for ProcessRecord{35094354 5594:com.test.thalitest/u0a316}, curProc for 5594: null
,I/ActivityManager(  849): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  849):   Force finishing activity ActivityRecord{7cc6ce0 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  849): Duplicate finish request for ActivityRecord{7cc6ce0 u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/QCNEJ   ( 1829): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  849): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
,W/System.err( 3638): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3638): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3638): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3638): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3638): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3638): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3638): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3638): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3638): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3638): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3638): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3638): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  849): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8242 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 1936): Explicit concurrent mark sweep GC freed 21652(1357KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/20MB, paused 5.960ms total 124.367ms
I/art     ( 5753): Explicit concurrent mark sweep GC freed 8337(455KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 917us total 138.155ms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
W/ResourcesManager( 1372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1372): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,W/ResourcesManager( 1372): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 1372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1372): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1372): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 8242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8242): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8242): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemUI[Framework](  849): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/InputDispatcher(  849): Focus entered window: Window{1e308901 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  849): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  849): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  849): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30cc762e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/SystemUI[Framework](  849): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  849): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx(  849): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  849): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30cc762e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
,I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     (  849): Explicit concurrent mark sweep GC freed 28842(1852KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 17.135ms total 284.556ms
I/art     (  849): WaitForGcToComplete blocked for 160.245ms for cause Explicit
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
,D/KeyguardModel( 1372): handleShortcutListChanged...
,D/administrator(  849): Handling package changes for user 0
,I/LGEmail ( 8242): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8242): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/InputMethodManagerService(  849): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  849): Got RemoteException sending setActive(false) notification to pid 5594 uid 10316
,D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  849): tsOffsetIs: Apps: 295049514214; DSPS: 9759664; Offset : -2796669403
I/NotificationService(  849): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  849): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  849): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1372): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/TaskPersister(  849): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  849): Explicit concurrent mark sweep GC freed 7109(410KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 8.669ms total 310.328ms
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  849): Timeline: Activity_windows_visible id: ActivityRecord{ec2cb0 u0 com.lge.launcher2/.Launcher t221} time:295126
I/PackageChangeReceiver( 8242): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1584): Unable to connect to the editor to retrieve text... will retry later
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AppUp4:PreloadHelper( 7842): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  849): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8270 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 7862:com.android.gallery3d/u0a23 (adj 15): empty #11
D/AndroidRuntime( 8211): Shutting down VM
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/libprocessgroup(  849): failed to open /acct/uid_10023/pid_7862/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
,W/ResourcesManager(  849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourceType(  849): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8270): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8270): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8270): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8270): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8270): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SQLiteDatabase( 8270): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8270): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8270): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8270): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8270): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8270): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8270): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8270): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8270): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8270): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8270): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8270): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8270): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8270): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8270): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8270): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/SharedPreferencesImpl( 1875): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1875): Timeline: Activity_idle id: android.os.BinderProxy@4c6e267 time:295744
D/AndroidRuntime( 8270): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8270): FATAL EXCEPTION: main
E/AndroidRuntime( 8270): Process: com.android.settings, PID: 8270
E/AndroidRuntime( 8270): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8270): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8270): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8270): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8270): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8270): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8270): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8270): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8270): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8270): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8270): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8270): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8270): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8270): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8270): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8270): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8270): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8270): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 8270): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8270): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8270): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8270): 	... 11 more

```
