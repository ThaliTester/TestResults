#### Test 549702610b97681_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/AppUp4:AppBoxCP( 6034): onCreate
W/AppUp4:DB( 6034):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6034):  setFingerPrint start
I/AppUp4:DB( 6034):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6034):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6034):  SDK version = 0
I/AppUp4:DB( 6034):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6034): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6034): onReceive
I/AppUp4:CustModeStarterReceiver( 6034): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6034): Context : android.app.ReceiverRestrictedContext@1cf40f33
D/AppUp4:CustFacade( 6034): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6034): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6034): begin check event
I/AppUp4:CustModeStarterReceiver( 6034): Event For Nothing, skip.
--------- beginning of system
I/ActivityManager(  972): Killing 5790:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/NotificationService(  972): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/libprocessgroup(  972): failed to open /acct/uid_10023/pid_5790/cgroup.procs: No such file or directory
I/BackupManagerService(  972): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6065 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
V/BackupManagerService(  972): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  972): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@35d2fb1b
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6065): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6065): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
I/AppConfig( 6065): Total System Memory = 906309632
I/GalleryUtils( 6065): Application Heap = 96 MB
I/AppConfig( 6065): App Tier : NOT_DEF
D/SystemHelper( 6065): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 5835): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5835): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5835): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5835): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5835): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/UpdateIcingCorporaServi( 1946): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  972): Killing 5931:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1946): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_5931/cgroup.procs: No such file or directory
D/PackageBroadcastService( 4275): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/LocationProviderProxy(  972): applying state to connected service
I/PackageBroadcastService( 4275): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4275): updateResources: need to parse f{com.google.android.gms}
D/AndroidRuntime( 6063): 
D/AndroidRuntime( 6063): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6063): CheckJNI is OFF
D/AndroidRuntime( 6063): Calling main entry com.android.commands.am.Am
V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{3848dc8a type 2 when 91925 com.android.providers.calendar} when 91925
I/ActivityManager(  972): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6112 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{6f422fb #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{6f422fb #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  972): AppWindowTokenEx init.. 
D/ContextHelper(  972): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/SplitWindow(  972): check instance of lgWin Window{88884c4 u0 Starting com.test.thalitest}
D/InputDispatcher(  972): Focus left window: Window{2acd0ae7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 6063): Shutting down VM
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6129 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
W/ResourcesManager( 6112): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/WindowStateAnimator(  972): Starting window displayed
D/CalendarProvider2( 6112): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@380a7284
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21e46a63,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = f000000
D/BarTransitions( 1373): draw background and invalidate : color = e0d0d0d
I/HotwordDetector( 1946): Closing mic
I/MicrophoneInputStream( 1946): mic_close com.google.android.apps.gsa.speech.audio.u@2ce85f46
V/AudioRecord( 1946): stop()
D/AudioRecord( 1946): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
W/ActivityThread( 1878): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1878): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1878): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1878): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1878): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1878): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1878): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1878): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1878): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1878): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1878): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1878): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/CalendarProvider2( 6112): [getOrCreateCalendarAlarmManager]
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
,V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3844000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e6a0) usecase(7: audio-record)
I/CalendarProvider2( 6112): Created com.android.providers.calendar.CalendarAlarmManager@9610069(com.android.providers.calendar.CalendarProvider2@380a7284)
D/CalendarProviderBroadcastReceiver( 6112): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6112): [IntentService] WakeLock acquire, start IntentSerivce
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/CalendarProvider2( 6112): CalendarProviderIntentService.onCreate()
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
D/CalendarProvider2( 6112): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
D/CalendarProvider2( 6112): [getOrCreateCalendarAlarmManager]
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
I/ActivityManager(  972): Activity reported stop, but no longer stopping: ActivityRecord{af6057d u0 com.lge.launcher2/.Launcher t219}
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3844000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1946): stop()
V/AudioRecord( 1946): stop()
V/AudioRecord( 1946): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1946): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem(  972): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2012): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb3844000 exiting
V/AudioSystem( 1752): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2707): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3160): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e6a0)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e6a0) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): releasing 16 from 1946 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1946, calling pid 282
I/HotwordRecognitionRnr( 1946): Hotword detection finished
I/HotwordRecognitionRnr( 1946): Stopping hotword detection.
D/ContextHelper( 6129): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/CalendarProvider2( 6112): [IntentService] Release Lock
D/CalendarProvider2( 6112): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  972): Killing 5889:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10053/pid_5889/cgroup.procs: No such file or directory
I/WebViewFactory( 6129): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 4275): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/LibraryLoader( 6129): Time to load native libraries: 3 ms (timestamps 2665-2668)
I/LibraryLoader( 6129): Expected native library version number "",actual native library version number ""
D/UEI.SmartControl( 5741): Internal timer expired: 1
V/WebViewChromiumFactoryProvider( 6129): Binding Chromium to main looper Looper (main, tid 1) {9610069}
I/LibraryLoader( 6129): Expected native library version number "",actual native library version number ""
I/chromium( 6129): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6129): Initializing chromium process, singleProcess=true
W/art     ( 6129): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6129): ApplicationContext is null in ApplicationStatus
I/Icing   ( 4275): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  972): Killing 6034:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/chromium( 6129): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6129): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6129): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6129): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6129): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6129): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6129): Remote Branch: 
I/Adreno-EGL( 6129): Local Patches: 
I/Adreno-EGL( 6129): Reconstruct Branch: 
W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6034/cgroup.procs: No such file or directory
V/AudioPolicyService(  282): registerClient() client 0xb551c700, uid 10316
D/BluetoothAdapterService(897595941)( 2012): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3edf2b23
,D/BluetoothManagerService(  972): Message: 20
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19666bde:true
W/art     ( 6129): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6129): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6129): CordovaWebView is running on device made by: LGE
,W/art     ( 6129): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6129): Attempt to remove local handle scope entry from IRT, ignoring
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Activity( 6129): Activity.onPostResume() called 
,D/OpenGLRenderer( 6129): Render dirty regions requested: true
I/OpenGLRenderer( 6129): Initialized EGL, version 1.4
D/OpenGLRenderer( 6129): Enabling debug mode 0
,D/Atlas   ( 6129): Validating map...
,D/SplitWindow(  972): check instance of lgWin Window{1d73888e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6129): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  972): Focus entered window: Window{1d73888e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  972): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +1s179ms
I/Timeline(  972): Timeline: Activity_windows_visible id: ActivityRecord{21bd8f18 u0 com.test.thalitest/.MainActivity t220} time:93330
I/Timeline( 6129): Timeline: Activity_idle id: android.os.BinderProxy@efcb64c time:93359
,W/BindingManager( 6129): Cannot call determinedVisibility() - never saw a connection for the pid: 6129
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  972): Process com.android.contacts (pid 5810) has died
,D/JsMessageQueue( 6129): Set native->JS mode to OnlineEventsBridgeMode
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/jxcore_app_log( 6129): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622784512
D/JX-Cordova( 6129): jxcore cordova android initializing
,I/art     ( 6129): CheckpointMarkThreadRoots callback created = 0x9a9e8410
,I/art     ( 6129): CheckpointMarkThreadRoots callback created = 0x9a9e83e0
,D/AlertService( 5974): Beginning updateAlertNotification
,D/AlertService( 5974): No fired or scheduled alerts
,I/NotificationManager( 5974): com.android.calendar: cancel(0) by com.android.calendar
D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 94980678039; DSPS: 3210591; Offset : -3003466207
,I/NotificationManager( 5974): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 5974): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5974): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5974): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5974): No events found starting within 1 week.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  972): Killing 5974:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10013/pid_5974/cgroup.procs: No such file or directory
,W/ActivityManager(  972): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{318c1b66 type 0 when 1451862232909 com.android.providers.contacts} when 1451862232909
V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{1fe4eea7 type 2 when 61546 com.google.android.talk} when 61546
D/Finsky  ( 5585): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{34006efd type 0 when 1452294289844 com.android.vending} when 1452294289844
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/ResourcesManager( 5685): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5685): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  972): android: cancelAsUser(2) by android
,W/jxcore-log( 6129): Initializing JXcore engine
,W/jxcore-log( 6129): JXcore engine is ready
W/jxcore-log( 6129): Starting JXcore engine
,D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5585): propertyValue:false
D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/.test.thalitest( 6129): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6609]" dev="sockfs" ino=6609 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6129): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6129): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5773]" dev="sockfs" ino=5773 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6129): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6129): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6129): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26587]" dev="sockfs" ino=26587 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/jxcore-log( 6129): Platform android
W/jxcore-log( 6129): 
W/jxcore-log( 6129): Process ARCH arm
W/jxcore-log( 6129): 
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  972): android: cancelAsUser(2) by android
,I/qtaguid ( 5585): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5585): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5585): untagSocket(41) failed with errno -22
D/Finsky  ( 5585): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6245 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  972): android: cancelAsUser(2) by android
,W/ResourcesManager( 6245): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6245): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6245): VM with version 2.1.0 has multidex support
I/MultiDex( 6245): install
I/MultiDex( 6245): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  972): Process com.android.gallery3d (pid 6065) has died
,V/JNIHelp ( 6245): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6245): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6245): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@348f703: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6245): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6245): com.google.android.gms: cancel(10436) by com.google.android.gms
I/qtaguid ( 5585): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5585): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5585): untagSocket(41) failed with errno -22
I/NotificationManager( 6245): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationInitializer( 4275): Restart initialization of location
D/ChimeraCfgMgr( 6245): Reading stored module config
,I/art     (  972): Explicit concurrent mark sweep GC freed 25422(1269KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.229ms total 210.388ms
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/ActivityManager(  972): Process com.lge.lockscreensettings (pid 5835) has died
,I/PhoneApp( 1752): onTrimMemory: 10
I/PhoneApp( 1752): trim memory
,D/UEI.SmartControl( 5741): Service.onTrimMemory: 60
E/UEI.SmartControl( 5741): Setup service releasing memory...
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{330f25e4 type 0 when 1452294291162 com.google.android.googlequicksearchbox} when 1452294291162
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BackgroundMemoryTrimmer( 1946): Trimming objects from memory, since app is in the background.
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,D/ChimeraCfgMgr( 6245): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 5741): Explicit concurrent mark sweep GC freed 152(17KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 17.793ms total 78.724ms
,D/UEI.SmartControl( 5741): Service.onTrimMemory: 80
E/UEI.SmartControl( 5741): Setup service releasing memory...
W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,W/SQLiteConnectionPool( 4275): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/NativeLibraryUtils( 6245): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6245): Connecting to CarCallService...
,I/BackgroundMemoryTrimmer( 1946): Trimming objects from memory, since app is in the background.
I/art     ( 6245): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6245): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6245): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6245): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6245): Creating a new PhoneAdapter instance
,W/ActivityManager(  972): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
I/art     ( 5585): CheckpointMarkThreadRoots callback created = 0xb042d960
D/CAR.TEL.PhoneAdapter( 6245): setListener: com.google.android.gms.car.dn@1424a5ae
W/ActivityManager(  972): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6245): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6245): Starting CarCallService with initial phone null
I/NotificationManager( 6245): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5585): CheckpointMarkThreadRoots callback created = 0xb042d930
I/jxcore-log( 6129): JXcore Cordova bridge is ready!
I/jxcore-log( 6129): 
W/jxcore-log( 6129): JXcore engine is started
,I/Choreographer( 6129): Skipped 212 frames!  The application may be doing too much work on its main thread.
I/chromium( 6129): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/CAR.SERVICE( 6245): Package validated; name: com.android.vending
,I/jxcore-log( 6129): Toggling radios to true
I/jxcore-log( 6129): 
D/BluetoothAdapter( 6129): enable(): BT is already enabled..!
,D/WifiServiceImplEx(  972): setWifiEnabled: true pid=6129, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
V/Finsky  ( 5585): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/WifiService(  972): setWifiEnabled: true pid=6129, uid=10316
I/NotificationManager( 5585): com.android.vending: cancel(10436) by com.android.vending
D/WifiServiceImplEx(  972): disconnect pid=6129, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  972): reconnect pid=6129, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6129): Radios toggled
I/jxcore-log( 6129): 
I/jxcore-log( 6129): My device name is: LGE-LG-D722
I/jxcore-log( 6129): 
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2790): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  972): WifiStateMachine: Leaving Connected state
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  972): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  972): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1734): Read error: ssl=0xb045ac00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb045ac00: I/O error during system call, Broken pipe
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  972): ignoring duplicate network state non-change
D/WifiHS20(  972): hidePasspointNotification off =false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:51.894 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  972): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-10ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Forcing reevaluation
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6294 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/WifiStateMachine(  972): Start Disconnecting Watchdog 1
D/WifiHS20(  972): hidePasspointNotification off =false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  972): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  972): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  972): disableDataServiceNotify
D/DSQN    (  972): stop dsqn bin
,D/WifiHS20(  972): hidePasspointNotification off =false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:52.017 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:52.021 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WifiNetworkAgent(  972): NetworkAgent: NetworkAgent channel lost
,D/WifiHS20(  972): hidePasspointNotification off =false
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  972): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:52.031 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  972): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  972): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  972): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  972): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Disconnected - quitting
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:52.041 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,D/DhcpStateMachine(  972): StoppedState
D/DhcpStateMachine(  972): StoppedState{ when=-88ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  972): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  972): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  972): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1840): |CORE| No family connected
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateDISCONNECTED
D/Tethering(  972): MasterInitialState.processMessage what=3
D/Tethering(  972): MasterInitialState.processMessage what=3
D/WIFI    (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1752): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/NetworkManagementService(  972): Removing idletimer
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  972): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
E/lowmemorykiller(  243): Error writing /proc/5852/oom_score_adj; errno=22
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/ResourcesManager( 6294): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 6294): Using schema version: 115
I/IndexDatabaseHelper( 6294): Index is fine
,I/ActivityManager(  972): Process com.google.android.apps.plus (pid 5852) has died
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
,I/ActivityManager(  972): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6317 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  972): android: cancelAsUser(2) by android
,I/ElegantRequestDirector( 5585): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0xaaf9e200: I/O error during system call, Broken pipe
I/ElegantRequestDirector( 5585): Retrying request
D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  972): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/Finsky  ( 5585): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5585): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{3c436a75 type 0 when 1452294292627 com.android.vending} when 1452294292627
,D/Finsky  ( 5585): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,I/PCSuite ( 6317): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6317): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6317): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/DeviceConnectionService( 1734): client connected with version: 8296000
,D/Finsky  ( 5585): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5585): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/UEI.SmartControl( 5741): Service.onTrimMemory: 80
E/UEI.SmartControl( 5741): Setup service releasing memory...
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/PCSuite ( 6317): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6317): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6317): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/PCSuite ( 6317): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6317): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6317): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/PCSuite ( 6317): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6317): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6317): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
D/Finsky  ( 5585): [680] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  972): android: cancelAsUser(2) by android
,D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5585): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5585): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  972): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2790): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  972): onReceive
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.141 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2790): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.156 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
,V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateASSOCIATED
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WiFiOffLoadBroadcast( 6294): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.183 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2790): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.186 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/WifiServiceExtension(  972): setVHTCapabilityType  : false
I/WifiServerServiceExt(  972): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  972): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  972): setSecurityType  : 2
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.247 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.248 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  972): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  972): Got NetworkAgent Messenger
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  972): NetworkAgent connected
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  972): Start Dhcp Watchdog 2
D/DhcpStateMachine(  972): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  972): WaitBeforeStartState
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateGROUP_HANDSHAKE
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
E/WifiStateMachine(  972): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  972): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  972): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1560c737 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1560c737 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  972): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  972): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  972): DHCP Start wake lock is acquired.
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  972): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  972): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  972): setSupplicantStateCOMPLETED
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  972): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  972): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  972): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  972): ignoring duplicate network state non-change
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.414 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  972): Adding iface wlan0 to network 101
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.421 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
E/WifiStateMachine(  972): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  972): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.436 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  972): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:53.444 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  972): Unexpected mtu value: 0, wlan0
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  972): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  972): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  972): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  972): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  972): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  972): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  972): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  972): currentScore = 0, newScore = 20
D/ConnectivityService(  972):    accepting network in place of null
D/ConnectivityService(  972): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  972): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  972): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  972): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  972): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  972): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/Tethering(  972): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  972): validation of new default Network = false
D/ConnectivityService(  972): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  972): enableDataServiceNotify 
D/DSQN    (  972): start dsqn bin
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/DSQN    ( 6365): DSQN samuel.seo ver 141203
E/DSQN    ( 6365): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6365): created command queue thread
I/DSQN    ( 6365): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6365): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,V/NetworkPolicy(  972): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/PCSuite ( 6317): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6317): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6294): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6294): MCCMNC not supported: null
I/PCSuite ( 6317): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6317): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine(  972): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  972): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  972): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6368): version 5.5.6 starting
E/dhcpcd  ( 6368): get_duid: Read-only file system
,I/dhcpcd  ( 6368): wlan0: rebinding lease of 192.168.1.134
,W/ProcessCpuTracker(  972): Skipping unknown process pid 6363
,W/ProcessCpuTracker(  972): Skipping unknown process pid 6375
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] DNSResolver start dns
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  972): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6365): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6365): restart monitoring
,I/DSQN    ( 6365): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  972): DSQM DsqnNotification wlan0  1
D/DSQN    (  972): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 23:04:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452294294071], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452294294047]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  972): Validated
D/ConnectivityService(  972): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  972): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  972): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1752): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  972): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  972): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  972): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  972): onReceive
D/LocSvc_java(  972): got connectivity action
D/LocSvc_java(  972): broadcast - no network connections
,D/LocSvc_java(  972): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  972): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  972): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  972): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  972): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6384 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ConnectivityService(  972): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService(  972): identical MTU - not setting
D/Nat464Xlat(  972): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  972): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LocSvc_java(  972): onReceive
D/LocSvc_java(  972): got connectivity action
D/LocSvc_java(  972): broadcast - no network connections
D/LocSvc_java(  972): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  972): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  972): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  972): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  972): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  972): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  972): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  972): enableDataServiceNotify 
D/DSQN    (  972): start dsqn bin
D/GpsLocationProvider(  972): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:55.172 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  972): dsqn is running restart
D/GpsLocationProvider(  972): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DSQN    ( 6411): DSQN samuel.seo ver 141203
E/DSQN    ( 6411): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6411): created command queue thread
I/DSQN    ( 6411): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6411): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 6368): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6368): wlan0: leased 192.168.1.134 for 86400 seconds
,I/ActivityManager(  972): Process com.google.process.gapps (pid 4004) has died
,I/MusicStore( 6384): Database version: 120
,I/ActivityManager(  972): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6442 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  972): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  972): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  972): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  972): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  972): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  972): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  972): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  972): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  972): RunningState
,I/GservicesProvider( 6442): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 6442): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6442): GMS http client unavailable, use old client
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6384): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6384): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6384): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@90afa6a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6384): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6384): GMSCore installation verified
,I/ConfigStore( 6384): Config Database version: 1
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-09 00:04:56.306 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/MediaRouter( 6384): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6384): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6384): type=WIFI subType= reason=null isConnected=true
I/NotificationManager( 1946): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  972): Single check msg out of sync, ignoring.
,I/NetworkMonitor( 6384): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6480 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/LocSvc_java(  972): onReceive
D/LocSvc_java(  972): got connectivity action
D/LocSvc_java(  972): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  972): Sending msg: 4 arg1:1 arg2:1
D/GpsLocationProvider(  972): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  972): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  972): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  972): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  972): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/GHttpClientFactory( 6384): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6384): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 6384): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  972): Killing 6112:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,W/ResourcesManager( 6480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6480): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  972): failed to open /acct/uid_10014/pid_6112/cgroup.procs: No such file or directory
,I/NotificationManager( 6384): com.google.android.music: cancel(1061) by com.google.android.music
D/CAR.SERVICE( 6245): mConnectedToCar = false, abort
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/ActivityThread( 6245): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2db931d6 that was originally bound here
E/ActivityThread( 6245): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2db931d6 that was originally bound here
E/ActivityThread( 6245): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6245): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6245): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6245): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6245): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6245): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6245): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6245): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6245): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6245): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6245): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6245): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6245): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6245): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6245): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6245): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6245): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6245): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11c1be29 that was originally bound here
E/ActivityThread( 6245): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11c1be29 that was originally bound here
E/ActivityThread( 6245): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6245): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6245): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6245): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6245): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6245): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6245): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6245): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6245): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6245): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6245): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6245): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6245): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6245): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6245): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6245): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  972): Unbind failed: could not find connection for android.os.BinderProxy@1000229c
I/LGEmail ( 6480): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6480): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6480): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  972): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6508 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
I/HubEmail( 6480): JNI_OnLoad()
I/HubEmail( 6480): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6480): registerNatives()
I/HubEmail( 6480): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6480): registerNativeMethods()
I/HubEmail( 6480): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6480): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  972): Killing 5685:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10061/pid_5685/cgroup.procs: No such file or directory
W/Settings( 6480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LGDMClient( 6508): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6508): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6508): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6508): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6508): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6508): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6532 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 25.814ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.519ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.821ms
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/ContextImpl( 6508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6508): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6508): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6508): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6508): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6508): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  972): Killing 6245:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  972): propertyValue:false
,D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  972): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  972): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  972): propertyValue:false
I/DSQN    ( 6411): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6411): restart monitoring
,D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6411): dsqn report finish
D/DSQN    (  972): DSQM DsqnNotification wlan0  1
D/DSQN    (  972): start to monitor internet connection
I/AppUp4:AppBoxCP( 6532): onCreate
W/AppUp4:DB( 6532):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6532):  setFingerPrint start
,I/AppUp4:DB( 6532):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6532):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6532):  SDK version = 0
I/AppUp4:DB( 6532):  beforefinger == newfinger no write in DB
W/libprocessgroup(  972): failed to open /acct/uid_10006/pid_6245/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6532): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6532): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6532): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6532): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6532): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6532): onReceive
,I/AppUp4:CustModeStarterReceiver( 6532): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6532): Context : android.app.ReceiverRestrictedContext@6a35aee
D/AppUp4:CustFacade( 6532): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6532): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6532): begin check event
I/AppUp4:CustModeStarterReceiver( 6532): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6532): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6532): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6532): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6532): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  972): Killing 5585:com.android.vending/u0a36 (adj 15): empty #11
V/WifiInternetCheck(  972): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  972): failed to open /acct/uid_10036/pid_5585/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = false
I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6559 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6559): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6559): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6559): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  972): Killing 6294:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6294/cgroup.procs: No such file or directory
,I/CheckinService( 4275): Checkin interval check for package: unspecified last checkin: 1452294274343 min interval config: 0 actual interval: 24075
,D/PhoneMonitor( 6559): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6559): [loadFeatureFromXml] *** start feature loading from xml
V/DownloadManager( 3231): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/TelephonyAutoProfiling( 6559): [parse] Load xml
V/DownloadManager( 3231): DownloadService onCreate
,I/ActivityManager(  972): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6588 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/TelephonyAutoProfiling( 6559): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6559): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 3231): in removeSpuriousFiles
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3231): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@2b7800fe on behalf of 3231
I/DownloadManager( 3231): in trimDatabase
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@14da005f on behalf of 3231
V/DownloadManager( 3231): DownloadService onStartCommand
V/DownloadManager( 3231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6559): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@2bcf2f0a on behalf of 3231
I/CheckinService( 4275): Checking schedule, now: 1452294298542 next: 1452294304305
I/CheckinService( 4275): active receiver: disabled
,V/DownloadManager( 3231): DownloadService onDestroy
,I/ActivityManager(  972): Killing 5741:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5154): android.os.DeadObjectException
,W/System.err( 5154): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5154): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5154): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5154): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5154): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5154): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5154): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5154): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5154): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5154): android.os.DeadObjectException
W/System.err( 5154): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5154): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5154): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5154): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5154): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5154): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5154): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5154): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5154): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  972): failed to kill 1 processes for processgroup 5741
,E/lowmemorykiller(  243): Error writing /proc/5741/oom_score_adj; errno=22
D/WeatherAncestor( 2701): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:58
,I/art     (  972): Explicit concurrent mark sweep GC freed 79068(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.948ms total 197.189ms
,W/ActivityManager(  972): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  972): android.os.DeadObjectException
W/ActivityManager(  972): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  972): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  972): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  972): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  972): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  972): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  972): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  972): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  972): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  972): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  972): android.os.DeadObjectException
W/ActivityManager(  972): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  972): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  972): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  972): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  972): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  972): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  972): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  972): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  972): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  972): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  972): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{1c2563da type 2 when 105304 com.google.android.gms} when 105304
D/UpdateThreadPoolManager( 2701): 2 : This is isUpdating : false
D/WeatherAncestor( 2701): connectivity changed - connection : true
D/Weather_cast( 2701): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2701): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:59
D/WeatherService( 2701): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6625 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6631 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2701): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2701): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2701): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6625): Quickset Services start...
I/UEI.SmartControl( 6625): Manufacture = LGE
,D/UEI.SmartControl( 6625): File observer start...
E/UEI.SmartControl( 6625): IR Port is disabled: false
D/UEI.SmartControl( 6625): Starting file observer...
D/UEI.SmartControl( 6625): Extracting JNI libs...
D/UEI.SmartControl( 6625): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6631): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/UEI.SmartControl( 6625): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6625): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6625): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6625): --- Selecting new region: 2
I/UEI.SmartControl( 6625): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6625): Platform has CIR...
D/UEI.SmartControl( 6625): NO CIR support, need to check package...
I/UEI.SmartControl( 6625): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6625): QS Service created
,E/UEI.SmartControl( 6625): QS start get config
D/UEI.SmartControl( 6625): Loading JNI Libs...
D/UEI.SmartControl( 6625):  configuring local db...
,I/Babel_SMS( 6631): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6631): MmsConfig.loadMmsSettings
I/Babel_SMS( 6631): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 6631): MmsConfig.loadFromDatabase
I/art     ( 6631): CheckpointMarkThreadRoots callback created = 0xb042d560
,I/art     ( 6631): CheckpointMarkThreadRoots callback created = 0xb042d540
,E/Babel_SMS( 6631): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6631): MmsConfig.loadFromResources
E/Babel_SMS( 6631): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6631): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6631): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6631): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6631): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6631): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6631): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6631): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6631): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6631): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6631): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6631): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6631): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6631): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6631): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6631): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6631): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6631): found sensor: Motion Accel, handle=46
W/Settings( 6631): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6631): startup - clean
,I/Babel   ( 6631): deleted: false for 0
D/UEI.SmartControl( 6625):  ---- Has DB8: true
,D/UEI.SmartControl( 6625): QS start statue = true Error code = 0
D/UEI.SmartControl( 6625): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6625): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/UEI.SmartControl( 6625): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6625): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6625): IrrcClient ++ 
D/irrcClient( 6625): getIrrcService ++ 
D/irrcClient( 6625): getIrrcService -- 
D/irrcClient( 6625): IrrcClient -- 
W/irrc_jni( 6625): IRRCPlayer_nativeInit -- 
,I/UEI.SmartControl( 6625): Device manager: loading config....
D/UEI.SmartControl( 6625): Services init done
D/UEI.SmartControl( 6625): Config is loaded...
,I/ActivityManager(  972): Process com.google.android.music:main (pid 6384) has died
,D/UEI.SmartControl( 6625):  ----- QS SDK is ready!!!
D/WeatherService( 2701): 2 : TimeTick Intent has been received, Time(hour:min:sec) 0:5:0
D/WeatherService( 2701): 2 : TimeTick Intent And Screen On
D/WeatherService( 2701): 2 : SDK version : 21
D/UEI.SmartControl( 6625): QS Service init finished
W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2701): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2701): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2701): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2701): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2701): 2 : This is isUpdating : false
D/WeatherService( 2701): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2701): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2701): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2701): 2 : Fixed theme : optimus
D/WeatherReflect( 2701): 2 : Map key string is -2
,D/lim     ( 2701): 2 : time = 00:05
I/WeatherReflect( 2701): Model Name : LG-D722
D/WeatherTheme( 2701): 2 : Different view - status_min_formatted : 04 != 05
D/WeatherTheme( 2701): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2701): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/UEI.SmartControl( 6625): Notify AllClients services are ready: 0
,D/Theme   ( 2701): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2701): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/UEI.SmartControl( 6625): QS Service version name: 0.1.73
D/UEI.SmartControl( 6625): QS Service version code: 1073
D/UEI.SmartControl( 6625): Service requested: Control
I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6683 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Weather4x2_optimus( 2701): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2701): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2701): forecast size is 0
D/Theme   ( 2701): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2701): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2701): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2701): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2701): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2701): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2701): setTouchIntent, appWidgetId: 2
D/UEI.SmartControl( 6625): -----IControl: 11
D/Theme_WeatherAncestor_optimus( 2701): url is : null
D/UEI.SmartControl( 6625): Internal service binding...
,D/UEI.SmartControl( 6625): Caller: com.lge.qremote
D/UEI.SmartControl( 6625): ------------ IControl registerCallback...
I/UEI.SmartControl( 6625): Registering callback...
D/Theme   ( 2701): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2701): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/UEI.SmartControl( 6625): -----IControl: 19
D/WeatherAncestor( 2701): 2 : update view, appWidgetId: 2
D/UEI.SmartControl( 6625): Caller: com.lge.qremote
I/UEI.SmartControl( 6625): Registering Services Ready callback...
I/UEI.SmartControl( 6625): Notify client services are ready...
D/WeatherService( 2701): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 0:5:0
D/UEI.SmartControl( 6625): -----IControl: 8
D/UEI.SmartControl( 6625): Caller: com.lge.qremote
,W/AudioCapabilities( 6631): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6631): Unsupported mime audio/adpcm
W/AudioCapabilities( 6631): Unsupported mime audio/g726
W/AudioCapabilities( 6631): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6631): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6631): Unsupported mime video/mjpg
W/VideoCapabilities( 6631): Unsupported mime video/theora
,W/AudioCapabilities( 6631): Unsupported mime audio/evrc
W/AudioCapabilities( 6631): Unsupported mime audio/qcelp
W/VideoCapabilities( 6631): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6631): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6631): Unsupported mime audio/qcelp
W/AudioCapabilities( 6631): Unsupported mime audio/evrc
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/VideoCapabilities( 6631): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6631): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6631): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6631): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6631): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6631): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6631): onServiceConnected
,W/Babel   ( 6631): Attempted to change video mute state without an active call.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/libc-netbsd( 6631): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6631): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6631): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6631): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,I/NotificationManager( 6631): com.google.android.talk: cancel(10436) by com.google.android.talk
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 6631): propertyValue:false
I/Babel   ( 6631): connection state changed from UNKNOWN to CONNECTED
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  972): Process com.lge.email (pid 6480) has died
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6683): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6683):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6683):   adb logcat -s GAv4
,W/GAv4    ( 6683): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6683): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6683): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6683): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6683): Time to load native libraries: 2 ms (timestamps 7370-7372)
I/LibraryLoader( 6683): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6683): Binding Chromium to main looper Looper (main, tid 1) {1265a6f3}
I/LibraryLoader( 6683): Expected native library version number "",actual native library version number ""
I/chromium( 6683): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6683): Initializing chromium process, singleProcess=true
W/art     ( 6683): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6683): ApplicationContext is null in ApplicationStatus
W/chromium( 6683): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6683): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6683): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6683): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6683): Remote Branch: 
I/Adreno-EGL( 6683): Local Patches: 
I/Adreno-EGL( 6683): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb551c640, uid 10079
W/AudioManagerAndroid( 6683): Requires BLUETOOTH permission
,I/NSApplication( 6683): Starting up...
I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6746 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 6317:com.lge.sync/1000 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6317/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6768 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5154:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10106/pid_5154/cgroup.procs: No such file or directory
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{218bcf8d type 0 when 1452294301852 com.google.android.googlequicksearchbox} when 1452294301852
,W/ResourcesManager( 6768): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  972): Killing 6508:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6508/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6805 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6805): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6805): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6805): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6805): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6805): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6805): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6805): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ActivityThread( 6805): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6805): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@90afa6a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6805): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6805): GMSCore installation verified
,I/ConfigStore( 6805): Config Database version: 1
,I/MediaRouter( 6805): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6805): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6805): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6805): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6840 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6805): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6805): Using platform SSLCertificateSocketFactory
I/ActivityManager(  972): Killing 6532:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6840): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6840): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6532/cgroup.procs: No such file or directory
,I/NotificationManager( 6805): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6840): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6840): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6840): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/art     ( 6631): Suspending all threads took: 9.930ms
,I/ActivityManager(  972): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6883 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6840): JNI_OnLoad()
I/HubEmail( 6840): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6840): registerNatives()
I/HubEmail( 6840): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6840): registerNativeMethods()
I/HubEmail( 6840): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6840): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  972): Killing 6559:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_6559/cgroup.procs: No such file or directory
,W/Settings( 6840): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6883): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6883): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6883): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6883): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6883): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6909 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.555ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.536ms
,E/LGDMClient( 6883): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6883): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 20.774ms
D/LGDMClient( 6883): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6883): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6883): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  972): Killing 6588:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10051/pid_6588/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6909): onCreate
W/AppUp4:DB( 6909):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6909):  setFingerPrint start
I/AppUp4:DB( 6909):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6909):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6909):  SDK version = 0
,I/AppUp4:DB( 6909):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6909): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6909): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6909): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6909): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6909): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6909): onReceive
I/AppUp4:CustModeStarterReceiver( 6909): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6909): Context : android.app.ReceiverRestrictedContext@6a35aee
D/AppUp4:CustFacade( 6909): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6909): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6909): begin check event
I/AppUp4:CustModeStarterReceiver( 6909): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6909): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6909): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6909): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6909): handleAsyncCustNotification do not startCustService
I/jxcore-log( 6129): Test app app.js loaded
I/jxcore-log( 6129): 
I/ActivityManager(  972): Killing 6625:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/chromium( 6129): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  972): failed to open /acct/uid_10089/pid_6625/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = false
,I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6934 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6934): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6934): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6934): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  972): Killing 6631:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6934): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6934): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6934): [parse] Load xml
V/TelephonyAutoProfiling( 6934): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6934): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6934): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  972): failed to open /acct/uid_10061/pid_6631/cgroup.procs: No such file or directory
V/DownloadManager( 3231): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3231): DownloadService onCreate
I/DownloadManager( 3231): in removeSpuriousFiles
I/NotificationManager( 3231): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3231): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@6766598 on behalf of 3231
I/DownloadManager( 3231): in trimDatabase
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@2db931d6 on behalf of 3231
I/ActivityManager(  972): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6962 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3231): DownloadService onStartCommand
V/DownloadManager( 3231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@32384344 on behalf of 3231
I/CheckinService( 4275): Checkin interval check for package: unspecified last checkin: 1452294274343 min interval config: 0 actual interval: 31077
,I/CheckinService( 4275): Checking schedule, now: 1452294305430 next: 1452294304305
I/CheckinService( 4275): active receiver: enabled
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinService( 4275): Preparing to send checkin request
I/EventLogService( 4275): Accumulating logs since 1452294265983
I/art     (  972): Explicit concurrent mark sweep GC freed 19512(1055KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.232ms total 188.482ms
,V/DownloadManager( 3231): DownloadService onDestroy
,I/CheckinRequestBuilder( 4275): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4275): Failed to find provider info for com.google.android.wearable.settings
D/WeatherAncestor( 2701): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:5:5
D/UpdateThreadPoolManager( 2701): 2 : This is isUpdating : false
D/WeatherAncestor( 2701): connectivity changed - connection : true
D/Weather_cast( 2701): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2701): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:5:5
D/WeatherService( 2701): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6981 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2701): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2701): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2701): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6981): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  972): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6999 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6999): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6999): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Babel_SMS( 6981): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6981): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6981): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6981): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6981): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6981): MmsConfig.loadFromResources
E/Babel_SMS( 6981): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6981): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/MultiDex( 6999): VM with version 2.1.0 has multidex support
I/MultiDex( 6999): install
I/MultiDex( 6999): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6999): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SensorManager( 6981): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6981): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6981): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6981): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6981): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6981): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6981): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6981): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6981): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6981): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6981): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6981): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6981): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6981): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6981): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6981): found sensor: Motion Accel, handle=46
I/art     ( 6981): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/art     ( 6981): CheckpointMarkThreadRoots callback created = 0xb042d860
,W/Settings( 6981): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6981): startup - clean
W/ActivityThread( 6999): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6999): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@348f703: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6999): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6999): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6999): com.google.android.gms: cancel(39789) by com.google.android.gms
I/Babel   ( 6981): deleted: false for 0
,I/art     ( 6999): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6999): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6999): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  972): Process com.google.android.apps.magazines (pid 6683) has died
,I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7035 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6981): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6981): Unsupported mime audio/adpcm
W/AudioCapabilities( 6981): Unsupported mime audio/g726
W/AudioCapabilities( 6981): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6981): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6981): Unsupported mime video/mjpg
I/ActivityManager(  972): Process com.google.android.apps.plus (pid 6768) has died
W/VideoCapabilities( 6981): Unsupported mime video/theora
,D/WVCdm   (  282): Instantiating CDM.
,W/AudioCapabilities( 6981): Unsupported mime audio/evrc
I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/AudioCapabilities( 6981): Unsupported mime audio/qcelp
W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,W/AudioCapabilities( 6981): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6981): Unsupported mime audio/qcelp
W/AudioCapabilities( 6981): Unsupported mime audio/evrc
W/VideoCapabilities( 6981): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6981): Unsupported profile 4 for video/mp4v-es
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
,D/WVCdm   (  282): PrepareKeyRequest: nonce=1588973790
W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6981): onServiceConnected
,W/Babel   ( 6981): Attempted to change video mute state without an active call.
D/libc-netbsd( 6981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6981): propertyValue:false
I/NotificationManager( 6981): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/GAv4    ( 7035): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7035):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7035):   adb logcat -s GAv4
W/GAv4    ( 7035): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/Babel   ( 6981): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 7035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7035): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7035): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{29b0d037 type 0 when 1452294304305 com.google.android.gms} when 1452294304305
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
I/art     ( 6999): CheckpointMarkThreadRoots callback created = 0xb04caef0
,I/ActivityManager(  972): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7085 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  972): RTC_WAKEUP set : Alarm{214399a4 type 0 when 1452294307262 com.android.vending} when 1452294307262
,I/art     ( 6999): CheckpointMarkThreadRoots callback created = 0xb04caee0
,I/dex2oat ( 7091): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 7035): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7035): Time to load native libraries: 4 ms (timestamps 3830-3834)
I/LibraryLoader( 7035): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7035): Binding Chromium to main looper Looper (main, tid 1) {1265a6f3}
I/LibraryLoader( 7035): Expected native library version number "",actual native library version number ""
I/chromium( 7035): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7035): Initializing chromium process, singleProcess=true
W/art     ( 7035): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7035): ApplicationContext is null in ApplicationStatus
I/dex2oat ( 7091): dex2oat took 210.205ms (threads: 4)
,W/chromium( 7035): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/Adreno-EGL( 6999): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6999): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6999): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6999): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6999): Remote Branch: 
I/Adreno-EGL( 6999): Local Patches: 
I/Adreno-EGL( 6999): Reconstruct Branch: 
I/ActivityManager(  972): Process com.google.android.music:main (pid 6805) has died
,E/libEGL  ( 7035): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7035): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7035): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7035): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7035): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7035): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7035): Remote Branch: 
I/Adreno-EGL( 7035): Local Patches: 
I/Adreno-EGL( 7035): Reconstruct Branch: 
D/Finsky  ( 7085): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/AudioPolicyService(  282): registerClient() client 0xb4027160, uid 10079
I/NSApplication( 7035): Starting up...
,W/AudioManagerAndroid( 7035): Requires BLUETOOTH permission
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7136 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7085): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ResourcesManager( 7136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Settings( 7085): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7085): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7085): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 7085): Skipping gmscore version check
,D/Finsky  ( 7085): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7085): [1] Libraries$2.run: Finished loading 1 libraries.
I/WVCdm   (  282): CdmEngine::OpenSession
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@1e6e9562 on behalf of 7085
,D/Finsky  ( 7085): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7085): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  972): Process com.lge.email (pid 6840) has died
,D/Finsky  ( 7085): [875] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7085): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7179 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  972): tsOffsetIs: Apps: 114981421155; DSPS: 3865975; Offset : -3003454784
I/MusicStore( 7179): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7179): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7179): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7179): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7179): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7179): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WVCdm   (  282): CdmEngine::CloseSession
,V/JNIHelp ( 7179): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3425993353
W/ActivityThread( 7179): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7179): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@90afa6a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7179): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7179): GMSCore installation verified
,I/ConfigStore( 7179): Config Database version: 1
,I/MediaRouter( 7179): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  972): Process com.lge.appbox.client (pid 6909) has died
,V/MusicLeanback( 7179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7179): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7179): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7212 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7179): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7179): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7212): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7212): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7212): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     (  972): Explicit concurrent mark sweep GC freed 20212(941KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.974ms total 152.116ms
,I/ActivityManager(  972): Process com.google.android.setupwizard (pid 6934) has died
,I/NotificationManager( 7179): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7212): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7212): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  972): Process com.google.android.talk (pid 6981) has died
,D/eas_req ( 7212): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 6883): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6883): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6883): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 6883): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6883): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 7212): JNI_OnLoad()
I/HubEmail( 7212): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7212): registerNatives()
I/HubEmail( 7212): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7212): registerNativeMethods()
I/HubEmail( 7212): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7212): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7238 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7212): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 6883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6883): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6883): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6883): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6883): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6883): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 7238): onCreate
W/AppUp4:DB( 7238):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7238):  setFingerPrint start
I/AppUp4:DB( 7238):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7238):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7238):  SDK version = 0
I/AppUp4:DB( 7238):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7238): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7238): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7238): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7238): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7238): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7238): onReceive
I/AppUp4:CustModeStarterReceiver( 7238): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7238): Context : android.app.ReceiverRestrictedContext@6a35aee
,D/AppUp4:CustFacade( 7238): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7238): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7238): begin check event
I/AppUp4:CustModeStarterReceiver( 7238): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7238): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7238): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7238): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7238): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3160): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3160): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3160): networkInfo.isConnected() = true
,D/PhoneState( 3160): setPdpRejectCasuse : false
I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7257 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 26.898ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.841ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.039ms
,D/PhoneMonitor( 7257): Register our PhoneStateListener
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/MobileConnectivityChangeReceiver( 7257): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7257): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  972): Killing 6962:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 7257): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7257): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7257): [parse] Load xml
V/TelephonyAutoProfiling( 7257): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7257): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7257): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  972): failed to open /acct/uid_10051/pid_6962/cgroup.procs: No such file or directory
,V/DownloadManager( 3231): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3231): DownloadService onCreate
I/DownloadManager( 3231): in removeSpuriousFiles
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3231): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@1265a6f3 on behalf of 3231
I/DownloadManager( 3231): in trimDatabase
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@21184fb0 on behalf of 3231
,I/ActivityManager(  972): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7280 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3231): DownloadService onStartCommand
,V/DownloadManager( 3231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@10a9bf4f on behalf of 3231
I/CheckinService( 4275): Checkin interval check for package: unspecified last checkin: 1452294274343 min interval config: 0 actual interval: 36355
,V/DownloadManager( 3231): DownloadService onDestroy
,I/ActivityManager(  972): Killing 7035:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10079/pid_7035/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2701): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:5:11
D/UpdateThreadPoolManager( 2701): 2 : This is isUpdating : false
D/WeatherAncestor( 2701): connectivity changed - connection : true
D/Weather_cast( 2701): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2701): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:5:11
D/WeatherService( 2701): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7300 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2701): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2701): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2701): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7300): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
I/Adreno-EGL( 6999): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6999): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6999): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6999): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6999): Remote Branch: 
I/Adreno-EGL( 6999): Local Patches: 
I/Adreno-EGL( 6999): Reconstruct Branch: 
I/Adreno-EGL( 6999): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6999): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6999): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6999): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6999): Remote Branch: 
I/Adreno-EGL( 6999): Local Patches: 
I/Adreno-EGL( 6999): Reconstruct Branch: 
,I/Babel_SMS( 7300): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7300): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7300): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7300): MmsConfig.loadFromDatabase
E/Babel_SMS( 7300): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7300): MmsConfig.loadFromResources
,E/Babel_SMS( 7300): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7300): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/SensorManager( 7300): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7300): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7300): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7300): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7300): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7300): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7300): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7300): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7300): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7300): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7300): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7300): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7300): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7300): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7300): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7300): found sensor: Motion Accel, handle=46
,W/Settings( 7300): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7300): startup - clean
,I/art     ( 7300): CheckpointMarkThreadRoots callback created = 0xb042d580
I/art     ( 7300): CheckpointMarkThreadRoots callback created = 0xb042d560
,I/Babel   ( 7300): deleted: false for 0
,I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7338 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7300): Unsupported mime audio/x-lg-flac
,I/CheckinRequestBuilder( 4275): Classify the device as Phone.
W/AudioCapabilities( 7300): Unsupported mime audio/adpcm
W/AudioCapabilities( 7300): Unsupported mime audio/g726
,W/AudioCapabilities( 7300): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7300): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7300): Unsupported mime video/mjpg
,W/VideoCapabilities( 7300): Unsupported mime video/theora
,D/libc-netbsd( 4275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/AudioCapabilities( 7300): Unsupported mime audio/evrc
W/AudioCapabilities( 7300): Unsupported mime audio/qcelp
W/VideoCapabilities( 7300): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7300): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7300): Unsupported mime audio/qcelp
W/AudioCapabilities( 7300): Unsupported mime audio/evrc
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4275): propertyValue:false
W/VideoCapabilities( 7300): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7300): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7300): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7300): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7300): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7338): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7338):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7338):   adb logcat -s GAv4
W/VideoCapabilities( 7300): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd( 4275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7338): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/libc-netbsd( 4275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/vclib   ( 7300): onServiceConnected
W/Babel   ( 7300): Attempted to change video mute state without an active call.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7338): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7338): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/NotificationManager( 7300): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7338): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7338): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7338): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7338): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/libc-netbsd( 4275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7300): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7300): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7300): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7300): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7300): propertyValue:false
,I/CheckinTask( 4275): Sending checkin request (9756 bytes)
I/ActivityManager(  972): Process com.google.android.music:main (pid 7179) has died
,I/Babel   ( 7300): connection state changed from UNKNOWN to CONNECTED
,I/MusicWidget( 2659): mDelayedStopHandler : unbind
,I/MusicBrowser( 2707): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2707): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2707): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2707): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2707): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2707): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2707): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  972):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@efcb64ccom.lge.music.MediaPlaybackService$6@2becf695
D/MusicBrowser( 2707): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@36ee37fa
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2707): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2707): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2707): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2707): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2707): reset
V/MediaPlayer[Native]( 2707): setListener
,V/MediaPlayer[Native]( 2707): disconnect
V/MediaPlayer[Native]( 2707): destructor
V/AudioFlinger(  282): releasing 19 from 2707 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2707): disconnect
D/MusicBrowser( 2707): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2707): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2707): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2707): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2707): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2707): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2707): [SmartShareManagerClient] unregisterListener: 860132266
W/SmartShareClient( 2707): [SmartShareManagerClient] unregisterListener invalid listener: 860132266
I/SmartShareClient( 2707): [SmartShareManagerClient] terminate service: 2707/MediaPlaybackService/620638960
E/HomeCloudIF( 2707): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2707): [SmartShareManagerClient] unbindService context:android.app.Application@18acdb9b
V/CloudHub( 2707): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2707): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2707): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2707): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2707): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
I/CloudHub( 2707): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,I/WebViewFactory( 7338): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7338): Time to load native libraries: 2 ms (timestamps 8574-8576)
,I/LibraryLoader( 7338): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7338): Binding Chromium to main looper Looper (main, tid 1) {1265a6f3}
I/LibraryLoader( 7338): Expected native library version number "",actual native library version number ""
I/chromium( 7338): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7338): Initializing chromium process, singleProcess=true
W/art     ( 7338): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7338): ApplicationContext is null in ApplicationStatus
W/chromium( 7338): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7338): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7338): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7338): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7338): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7338): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7338): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7338): Remote Branch: 
I/Adreno-EGL( 7338): Local Patches: 
I/Adreno-EGL( 7338): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb57e85e0, uid 10079
,I/NSApplication( 7338): Starting up...
W/AudioManagerAndroid( 7338): Requires BLUETOOTH permission
I/ActivityManager(  972): Killing 7085:com.android.vending/u0a36 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 4275): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  972): failed to open /acct/uid_10036/pid_7085/cgroup.procs: No such file or directory
,E/ActivityThread( 4275): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 7136): CheckpointMarkThreadRoots callback created = 0xb042de00
,I/art     ( 6442): Explicit concurrent mark sweep GC freed 2143(92KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 574us total 56.802ms
I/art     ( 7136): CheckpointMarkThreadRoots callback created = 0xb042ddd0
,I/ActivityManager(  972): Killing 7212:com.lge.email/u0a21 (adj 15): empty #11
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  972): failed to open /acct/uid_10021/pid_7212/cgroup.procs: No such file or directory
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
,I/ActivityManager(  972): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7407 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7407): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 4275): Classify the device as Phone.
,I/CheckinTask( 4275): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4275): Checking schedule, now: 1452294312883 next: 1452821561879
I/CheckinService( 4275): active receiver: disabled
,I/CheckinService( 4275): Checking schedule, now: 1452294312916 next: 1452821561879
,I/CheckinService( 4275): active receiver: disabled
D/CheckinService( 4275): Recording last checkin time for package unspecified as 1452294312925
I/ActivityManager(  972): Killing 7238:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/BluetoothManagerService(  972): Message: 20
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b1bb88f:true
,I/ActivityManager(  972): Killing 6883:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_7238/cgroup.procs: No such file or directory
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_6883/cgroup.procs: No such file or directory
D/BluetoothAdapterService(897595941)( 2012): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3edf2b23
D/BluetoothAdapterService(897595941)( 2012): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3edf2b23
I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7433 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7407): Create singleton instance
,D/UEI.SmartControl( 7433): Quickset Services start...
,I/UEI.SmartControl( 7433): Manufacture = LGE
D/UEI.SmartControl( 7433): File observer start...
E/UEI.SmartControl( 7433): IR Port is disabled: false
D/UEI.SmartControl( 7433): Starting file observer...
D/UEI.SmartControl( 7433): Extracting JNI libs...
D/UEI.SmartControl( 7433): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7407): getMode name:com.lge.qremote
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4275): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
I/CheckinService( 4275): Checkin interval check for package: unspecified last checkin: 1452294312925 min interval config: 0 actual interval: 446
,I/CheckinService( 4275): Checking schedule, now: 1452294313397 next: 1452821561879
I/CheckinService( 4275): active receiver: disabled
,V/SetupWizard( 7257): Connected to Gservices successfully
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 3642): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/AudioManager( 7407): getMode name:com.lge.qremote
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7433): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7433): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7433): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7433): --- Selecting new region: 2
,I/UEI.SmartControl( 7433): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7433): Platform has CIR...
D/UEI.SmartControl( 7433): NO CIR support, need to check package...
I/UEI.SmartControl( 7433): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7433): QS Service created
,E/UEI.SmartControl( 7433): QS start get config
,D/UEI.SmartControl( 7433): Loading JNI Libs...
,D/UEI.SmartControl( 7433):  configuring local db...
D/UEI.SmartControl( 7433):  ---- Has DB8: true
,D/UEI.SmartControl( 7433): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7433): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7433): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7433): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7433): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7433): IrrcClient ++ 
D/irrcClient( 7433): getIrrcService ++ 
D/irrcClient( 7433): getIrrcService -- 
D/irrcClient( 7433): IrrcClient -- 
W/irrc_jni( 7433): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7433): Services init done
I/UEI.SmartControl( 7433): Device manager: loading config....
,D/UEI.SmartControl( 7433): QS Service init finished
D/UEI.SmartControl( 7433): QS Service version name: 0.1.73
D/UEI.SmartControl( 7433): Config is loaded...
D/UEI.SmartControl( 7433): QS Service version code: 1073
D/UEI.SmartControl( 7433): Service requested: Control
,D/UEI.SmartControl( 7433):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7433): Notify AllClients services are ready: 0
,I/art     (  972): Explicit concurrent mark sweep GC freed 18540(898KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.906ms total 137.883ms
,D/UEI.SmartControl( 7433): -----IControl: 11
D/UEI.SmartControl( 7433): Internal service binding...
D/UEI.SmartControl( 7433): Caller: com.lge.qremote
D/UEI.SmartControl( 7433): ------------ IControl registerCallback...
I/UEI.SmartControl( 7433): Registering callback...
D/UEI.SmartControl( 7433): -----IControl: 19
D/UEI.SmartControl( 7433): Caller: com.lge.qremote
I/UEI.SmartControl( 7433): Registering Services Ready callback...
I/UEI.SmartControl( 7433): Notify client services are ready...
D/UEI.SmartControl( 7433): -----IControl: 8
D/UEI.SmartControl( 7433): Caller: com.lge.qremote
I/AudioManager( 7407): getMode name:com.lge.qremote
,I/AudioManager( 7407): getMode name:com.lge.qremote
,I/AudioManager( 7407): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7510 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7300): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7300): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/administrator(  972): Handling package changes for user 0
,I/NotificationManager( 7300): com.google.android.talk: cancel(8) by com.google.android.talk
I/AppUp4:AppBoxCP( 7510): onCreate
,W/AppUp4:DB( 7510):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7510):  setFingerPrint start
I/AppUp4:DB( 7510):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7510):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7510):  SDK version = 0
I/AppUp4:DB( 7510):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7510): AppBoxApplication onCreate()
,V/JNIHelp ( 7300): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:CustModeStarterReceiver( 7510): onReceive
I/AppUp4:CustModeStarterReceiver( 7510): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7510): Context : android.app.ReceiverRestrictedContext@1cf40f33
D/AppUp4:CustFacade( 7510): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7510): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7510): begin check event
I/AppUp4:CustModeStarterReceiver( 7510): Event For Nothing, skip.
,I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7534 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/System  ( 7300): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7300): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7534): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7534): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,I/NotificationService(  972): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  972): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  972): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  972): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@f5dde2f
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  972): Process com.google.android.apps.magazines (pid 7338) has died
,I/AppConfig( 7534): Total System Memory = 906309632
I/GalleryUtils( 7534): Application Heap = 96 MB
,W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7534): App Tier : NOT_DEF
,D/SystemHelper( 7534): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7557 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/ResourcesManager( 7557): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7557): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7557): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7557): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7557): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  972): applying state to connected service
,I/SystemConfig( 7557): BUILD Country: EU
I/SystemConfig( 7557): BUILD Operator: OPEN
,I/ActivityManager(  972): Killing 7280:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10051/pid_7280/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7584 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 2707:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  282): 2707 died, releasing its sessions
V/AudioFlinger(  282):  pid 1752 @ 0
V/AudioFlinger(  282):  pid 3160 @ 1
V/AudioFlinger(  282):  pid 3160 @ 2
,W/libprocessgroup(  972): failed to open /acct/uid_10028/pid_2707/cgroup.procs: No such file or directory
,I/SystemConfig( 7557): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7557): existFile = false
I/SystemConfig( 7557): canReadFile = false
I/SystemConfig( 7557): systemFeature RCS result false
D/SystemConfig( 7557): refreshRcsSupport() :false
I/LockScreenSettings( 7584): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7584): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7584): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7584): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7584): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7584): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1946): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7608 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 6746:com.android.chrome/u0a48 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1946): UpdateCorporaTask done [took 117 ms] updated apps [took 117 ms] 
,W/libprocessgroup(  972): failed to open /acct/uid_10048/pid_6746/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,D/Finsky  ( 7608): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 7608): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7608): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7608): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7608): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@348f13e5 on behalf of 7608
D/Finsky  ( 7608): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7608): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7608): Skipping gmscore version check
I/ActivityManager(  972): Killing 7257:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_7257/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4275): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7608): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/PackageBroadcastService( 4275): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7608): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4275): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 4275): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/UEI.SmartControl( 7433): Internal timer expired: 1
,I/Icing   ( 4275): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  972): Killing 7510:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_7510/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/charger_monitor(  466): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/charger_monitor(  466): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
D/WifiController(  972): battery changed pluggedType: 2
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ActivityManager(  972): Killing 7300:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10061/pid_7300/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 134982349691; DSPS: 4521366; Offset : -3003472527
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{d71d22a type 2 when 145794 com.google.android.gms} when 145794
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1452294339806 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28645 ms ago)
,D/qdlights(  972): set_light_backlight: 253
,D/qdlights(  972): set_light_backlight: 250
D/qdlights(  972): set_light_backlight: 246
,D/qdlights(  972): set_light_backlight: 243
,D/qdlights(  972): set_light_backlight: 240
,D/qdlights(  972): set_light_backlight: 236
,D/qdlights(  972): set_light_backlight: 233
,D/qdlights(  972): set_light_backlight: 230
,D/qdlights(  972): set_light_backlight: 226
,D/qdlights(  972): set_light_backlight: 223
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  972): set_light_backlight: 220
,D/qdlights(  972): set_light_backlight: 216
,D/qdlights(  972): set_light_backlight: 213
,D/qdlights(  972): set_light_backlight: 210
,D/qdlights(  972): set_light_backlight: 206
,D/qdlights(  972): set_light_backlight: 203
,D/qdlights(  972): set_light_backlight: 200
,D/qdlights(  972): set_light_backlight: 196
,D/qdlights(  972): set_light_backlight: 193
,D/qdlights(  972): set_light_backlight: 190
,D/qdlights(  972): set_light_backlight: 186
,D/qdlights(  972): set_light_backlight: 183
,D/qdlights(  972): set_light_backlight: 180
,D/qdlights(  972): set_light_backlight: 176
,D/qdlights(  972): set_light_backlight: 173
,D/qdlights(  972): set_light_backlight: 170
,D/qdlights(  972): set_light_backlight: 166
,D/qdlights(  972): set_light_backlight: 163
,D/qdlights(  972): set_light_backlight: 160
,D/qdlights(  972): set_light_backlight: 156
,D/qdlights(  972): set_light_backlight: 153
,D/qdlights(  972): set_light_backlight: 150
,D/qdlights(  972): set_light_backlight: 146
,D/qdlights(  972): set_light_backlight: 143
,D/qdlights(  972): set_light_backlight: 140
,D/qdlights(  972): set_light_backlight: 136
,D/qdlights(  972): set_light_backlight: 133
,D/qdlights(  972): set_light_backlight: 130
,D/qdlights(  972): set_light_backlight: 126
,D/qdlights(  972): set_light_backlight: 123
,D/qdlights(  972): set_light_backlight: 120
,D/qdlights(  972): set_light_backlight: 116
,D/qdlights(  972): set_light_backlight: 113
,D/qdlights(  972): set_light_backlight: 110
,D/qdlights(  972): set_light_backlight: 106
,D/qdlights(  972): set_light_backlight: 103
,D/qdlights(  972): set_light_backlight: 100
,D/qdlights(  972): set_light_backlight: 96
,D/qdlights(  972): set_light_backlight: 93
,D/qdlights(  972): set_light_backlight: 90
,D/qdlights(  972): set_light_backlight: 86
,D/qdlights(  972): set_light_backlight: 83
,D/qdlights(  972): set_light_backlight: 80
,D/qdlights(  972): set_light_backlight: 76
,D/qdlights(  972): set_light_backlight: 73
,D/qdlights(  972): set_light_backlight: 70
,D/qdlights(  972): set_light_backlight: 66
,D/qdlights(  972): set_light_backlight: 63
,D/qdlights(  972): set_light_backlight: 60
,D/qdlights(  972): set_light_backlight: 56
,D/qdlights(  972): set_light_backlight: 53
,D/qdlights(  972): set_light_backlight: 50
,D/qdlights(  972): set_light_backlight: 46
,D/qdlights(  972): set_light_backlight: 43
,D/qdlights(  972): set_light_backlight: 40
,D/qdlights(  972): set_light_backlight: 36
,D/qdlights(  972): set_light_backlight: 33
,D/qdlights(  972): set_light_backlight: 30
,D/qdlights(  972): set_light_backlight: 26
,D/qdlights(  972): set_light_backlight: 23
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  972): set_light_backlight: 20
,D/qdlights(  972): set_light_backlight: 16
,D/qdlights(  972): set_light_backlight: 13
,D/qdlights(  972): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 154983112288; DSPS: 5176751; Offset : -3003474615
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35638 ms ago)
I/PowerManagerService(  972): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35648 ms ago)
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  972): Sleeping (uid 1000)...
D/LPWGController(  972): [updateScreenState] screen on = false
D/LPWGController(  972): disable proximity sensor
D/LPWGController(  972): enable proximity sensor
I/SensorManager(  972): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3c76cf93] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  972): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  972): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  972): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  972): activate: handle is 48, enable
V/sensors_hal_Ctx(  972): activate sensors is 1400000000000
D/sensors_hal_Thresh(  972): enable: handle=48
I/sensors_hal_SAM(  972): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  972): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  972): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  972): enable: Received response: 0
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35682 ms ago)
I/Adreno-EGL(  972): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  972): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  972): Build Date: 03/02/15 Mon
I/Adreno-EGL(  972): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  972): Remote Branch: 
I/Adreno-EGL(  972): Local Patches: 
I/Adreno-EGL(  972): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1277 us)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Sensors (  423): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  972): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  972): processInd: handle 48, count=1
V/sensors_hal_Thresh(  972): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  972): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  972): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  972): poll: count: 256
I/sensors_hal_Ctx(  972): poll: released wakelock sensor_ind
D/sensors_hal_Util(  972): waitForResponse: timeout=0
D/LPWGController(  972): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  972): current mode = 1  value = 1 1
I/LPWGController(  972): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  972): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  972): set_light_backlight: 0
,I/SensorManager(  972): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  972): activate: handle is 46, disable
V/sensors_hal_Ctx(  972): activate sensors is 1000000000000
D/sensors_hal_LP2(  972): enable: handle=46
D/sensors_hal_LP2(  972): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  972): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  972): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  972): Display changed displayId=0
,V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  972): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1752): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  972): Excessive delay in setPowerMode(): 232ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  972): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/WifiServerServiceExt(  972): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 972
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
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
I/WifiServerServiceExt(  972): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1805): lockStatus = 0
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1805): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 3
D/NfcService( 1787): Discovery configuration equal, not updating.
,D/SplitWindow(  972): check instance of lgWin Window{23bdece u0 SearchPanel}
,D/InputDispatcher(  972): Window went away: Window{5330e80 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,D/Ulp_jni (  972): JNI:system_update. Event-0
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2701): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:5:51
,D/WeatherService( 2701): 2 : ACTION screen on
D/WeatherService( 2701): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2701): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2701): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:5:51
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): ACTION_SCREEN_ON
D/AppCleanupService( 4121): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 972
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
D/WifiController(  972): CMD_SCREEN_OFF 
D/WifiController(  972): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
I/Sensors (  423): sns_pwr.c(301):releasing wakelock
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2701): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:5:51
D/WeatherService( 2701): 2 : ACTION screen off
D/WeatherService( 2701): 2 : TimeTick Receiver Unregister
D/WeatherService( 2701): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:5:51
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): ACTION_SCREEN_OFF
,D/AppCleanupService( 4121): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4121): AppUsageStatsSaveTask
E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1787): getDefaultRoute
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: 0
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{12b4d1ef type 2 when 161547 com.android.systemui} when 161547
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1752): getCallState : 0
D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 174983866916; DSPS: 5832136; Offset : -3003481285
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  466): init target 500000
,D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=483288316, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{3d8df785 type 2 when 187490 com.google.android.gms} when 187490
,D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=483288316 [*alarm*], flags=0x0
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 44704(2MB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 13MB/22MB, paused 1.857ms total 149.387ms
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 4479 seconds from now (1452294381782)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{23f30a32 type 2 when 188450 android} when 188450
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  972): Explicit concurrent mark sweep GC freed 52959(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.065ms total 150.013ms
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 194984545293; DSPS: 6487518; Offset : -3003475232
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 214985299348; DSPS: 7142903; Offset : -3003485315
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 234985984965; DSPS: 7798285; Offset : -3003470147
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  466): init target 500000
,D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 254986773499; DSPS: 8453671; Offset : -3003475982
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  466): init target 500000
,D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 274987461356; DSPS: 9109053; Offset : -3003459434
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 294988150671; DSPS: 9764436; Offset : -3003469965
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  466): init target 500000
,D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 314988931705; DSPS: 10419822; Offset : -3003482232
,I/jxcore-log( 6129): --= Surplus to requirements =--
I/jxcore-log( 6129): 
,I/jxcore-log( 6129): ****TEST TOOK:  ms ****
I/jxcore-log( 6129): 
I/jxcore-log( 6129): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6129): 
D/charger_monitor(  466): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/AndroidRuntime( 7808): 
D/AndroidRuntime( 7808): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7808): CheckJNI is OFF
,D/AndroidRuntime( 7808): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  972): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  972): Killing 6129:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  972): WIN DEATH: Window{1d73888e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  972): Skipping PackageSetting{2dc9d682 com.example.hello/10317} due to missing metadata
D/InputDispatcher(  972): Focus left window: Window{1d73888e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  972): Window went away: Window{1d73888e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  972):   Force finishing activity ActivityRecord{21bd8f18 u0 com.test.thalitest/.MainActivity t220}
,D/DSDPConnection( 1752): Display #0 changed.
V/ActivityManager(  972): Display changed displayId=0
,W/ActivityManager(  972): Spurious death for ProcessRecord{207dad8a 6129:com.test.thalitest/u0a316}, curProc for 6129: null
,I/ActivityManager(  972): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
,I/art     ( 1946): Explicit concurrent mark sweep GC freed 9443(649KB) AllocSpace objects, 4(96KB) LOS objects, 40% free, 12MB/20MB, paused 1.555ms total 81.855ms
,D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3642): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3642): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3642): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3642): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3642): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3642): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3642): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3642): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3642): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3642): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3642): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3642): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4275): Explicit concurrent mark sweep GC freed 3975(209KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/18MB, paused 753us total 144.198ms
,I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7839 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 25.873ms
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 25.310ms
I/Activity( 1878): Activity.onPostResume() called 
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 22.226ms
,I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
,I/art     (  972): Explicit concurrent mark sweep GC freed 19512(1467KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 7.507ms total 257.853ms
I/art     (  972): WaitForGcToComplete blocked for 99.874ms for cause Explicit
,W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 7839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7839): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7839): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  972): Focus entered window: Window{2acd0ae7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21e46a63,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21e46a63,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/administrator(  972): Handling package changes for user 0
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1373): handleShortcutListChanged...
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
,D/KeyguardModel( 1373): handleShortcutListChanged...
I/NotificationService(  972): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  972): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  972): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
,I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
I/LGEmail ( 7839): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7839): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  972): Explicit concurrent mark sweep GC freed 5494(318KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 8.042ms total 305.658ms
,W/InputMethodManagerService(  972): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  972): Got RemoteException sending setActive(false) notification to pid 6129 uid 10316
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,D/AndroidRuntime( 7808): Shutting down VM
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  972): Timeline: Activity_windows_visible id: ActivityRecord{af6057d u0 com.lge.launcher2/.Launcher t219} time:316948
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
E/b       ( 1624): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/PackageChangeReceiver( 7839): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7865 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  972): Killing 7534:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/libprocessgroup(  972): failed to open /acct/uid_10023/pid_7534/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7865): onCreate
W/AppUp4:DB( 7865):  [AppBoxDatabaseHelper] construct

```
