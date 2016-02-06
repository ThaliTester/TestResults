#### Test 58380500fccea7e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/PackageChangeReceiver( 5213): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
I/ActivityManager(  947): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5241 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  947): Killing 4988:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10086/pid_4988/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5266 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  947): Killing 5079:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_5079/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 5266): onCreate
W/AppUp4:DB( 5266):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5266):  setFingerPrint start
I/AppUp4:DB( 5266):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5266):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5266):  SDK version = 0
I/AppUp4:DB( 5266):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5266): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5266): removed from Exclude : com.test.thalitest : 1
I/ActivityManager(  947): Killing 5049:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_5049/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
I/ActivityManager(  947): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5296 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AndroidRuntime( 5264): 
D/AndroidRuntime( 5264): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5264): CheckJNI is OFF
W/ResourcesManager( 5296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5296): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5296): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5296): Total System Memory = 906309632
I/GalleryUtils( 5296): Application Heap = 96 MB
I/AppConfig( 5296): App Tier : NOT_DEF
D/SystemHelper( 5296): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  947): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5328 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  947): Killing 3918:com.google.process.gapps/u0a6 (adj 15): empty #11
D/AndroidRuntime( 5264): Calling main entry com.android.commands.am.Am
I/art     (  311): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 284us total 25.547ms
I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 23.531ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.580ms
W/libprocessgroup(  947): failed to open /acct/uid_10006/pid_3918/cgroup.procs: No such file or directory
I/ActivityManager(  947): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  947): setTaskToReturnTo : TaskRecord{10a489c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  947): setTaskToReturnTo : TaskRecord{10a489c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  947): AppWindowTokenEx init.. 
D/ContextHelper(  947): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  947): Focus left window: Window{1891af5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5264): Shutting down VM
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  947): check instance of lgWin Window{3ddcc046 u0 Starting com.test.thalitest}
I/ActivityManager(  947): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5358 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5328): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/WindowStateAnimator(  947): Starting window displayed
I/SystemUI[Framework](  947): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  947): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  947): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  947): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  947): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2f53974a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  947): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = 13000000
D/BarTransitions( 1374): draw background and invalidate : color = b0b0b0b
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1877): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1877): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1877): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1877): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1877): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1877): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1877): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1877): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1877): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1877): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1877): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1877): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/HotwordDetector( 1943): Closing mic
I/MicrophoneInputStream( 1943): mic_close com.google.android.apps.gsa.speech.audio.u@2f9322cd
V/AudioRecord( 1943): stop()
D/AudioRecord( 1943): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
,V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb39d6000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/ActivityManager(  947): Activity reported stop, but no longer stopping: ActivityRecord{5aa8204 u0 com.lge.launcher2/.Launcher t221}
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
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
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb39d6000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
D/ContextHelper( 5358): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioFlinger(  281): releasing 16 from 1943 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem( 3150): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem(  947): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb39d6000 exiting
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioSystem( 1943): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioSystem( 1976): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioFlinger(  281): removeClient_l() pid 1943, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioSystem( 2739): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1943): Stopping hotword detection.
I/HotwordRecognitionRnr( 1943): Hotword detection finished
I/WebViewFactory( 5358): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/SystemConfig( 5328): BUILD Country: EU
I/SystemConfig( 5328): BUILD Operator: OPEN
I/LibraryLoader( 5358): Time to load native libraries: 10 ms (timestamps 9632-9642)
I/LibraryLoader( 5358): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5358): Binding Chromium to main looper Looper (main, tid 1) {735f295}
I/LibraryLoader( 5358): Expected native library version number "",actual native library version number ""
I/chromium( 5358): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5358): Initializing chromium process, singleProcess=true
W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5358): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  947): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5383 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 4861:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/chromium( 5358): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/libprocessgroup(  947): failed to open /acct/uid_10006/pid_4861/cgroup.procs: No such file or directory
W/ActivityManager(  947): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
E/libEGL  ( 5358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5358): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5358): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5358): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5358): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5358): Remote Branch: 
I/Adreno-EGL( 5358): Local Patches: 
I/Adreno-EGL( 5358): Reconstruct Branch: 
I/SystemConfig( 5328): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5328): existFile = false
I/SystemConfig( 5328): canReadFile = false
I/SystemConfig( 5328): systemFeature RCS result false
D/SystemConfig( 5328): refreshRcsSupport() :false
I/LockScreenSettings( 5383): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 5383): New app installed broadcast received ..
I/LockScreenSettings( 5383): Number of installed packages  1
V/AudioPolicyService(  281): registerClient() client 0xb3a6a420, uid 10316
D/BluetoothManagerService(  947): Message: 20
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cb26db8:true
D/BluetoothAdapterService(164635409)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f9796f
I/ActivityManager(  947): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5414 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  947): Killing 4210:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10006/pid_4210/cgroup.procs: No such file or directory
I/ActivityManager(  947): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5432 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5432): Gservices pushing to system: true; secure/global: true
,D/EulaProviderUpdateObserver( 5414): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5414): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5122): android.intent.action.PACKAGE_ADDED : com.test.thalitest
W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  947): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5452 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 5023:com.lge.clock/u0a10 (adj 15): empty #11
I/GoogleHttpClient( 5432): GMS http client unavailable, use old client
,W/AwContents( 5358): onDetachedFromWindow called when already detached. Ignoring
,W/libprocessgroup(  947): failed to open /acct/uid_10010/pid_5023/cgroup.procs: No such file or directory
D/SystemWebViewEngine( 5358): CordovaWebView is running on device made by: LGE
,W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5432): GMS http client unavailable, use old client
,I/Activity( 5358): Activity.onPostResume() called 
,D/OpenGLRenderer( 5358): Render dirty regions requested: true
I/OpenGLRenderer( 5358): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5358): Enabling debug mode 0
D/Atlas   ( 5358): Validating map...
,D/SplitWindow(  947): check instance of lgWin Window{2d61ea32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5358): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  947): Killing 5142:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10081/pid_5142/cgroup.procs: No such file or directory
,D/InputDispatcher(  947): Focus entered window: Window{2d61ea32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  947): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  947): Displayed com.test.thalitest/.MainActivity: +1s300ms
I/Timeline(  947): Timeline: Activity_windows_visible id: ActivityRecord{1828a2a5 u0 com.test.thalitest/.MainActivity t222} time:80472
I/Timeline( 5358): Timeline: Activity_idle id: android.os.BinderProxy@3112be68 time:80494
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/BindingManager( 5358): Cannot call determinedVisibility() - never saw a connection for the pid: 5358
,V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{174f74df type 2 when 80598 android} when 80598
,D/AlertService( 3752): Beginning updateAlertNotification
,D/AlertService( 3752): No fired or scheduled alerts
,I/NotificationManager( 3752): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 3752): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 3752): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3752): com.android.calendar: cancel(20) by com.android.calendar
D/JsMessageQueue( 5358): Set native->JS mode to OnlineEventsBridgeMode
D/AlertService( 3752): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3752): No events found starting within 1 week.
,I/GAv4    ( 5452): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5452):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5452):   adb logcat -s GAv4
,W/GAv4    ( 5452): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5452): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5452): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5452): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/jxcore_app_log( 5358): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426086400
,I/chromium( 5358): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5358): CheckpointMarkThreadRoots callback created = 0x9a9634a0
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5452): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/art     ( 5358): CheckpointMarkThreadRoots callback created = 0x9a963470
,I/art     ( 5358): Background partial concurrent mark sweep GC freed 7721(607KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 6.158ms total 44.913ms
,W/ResourcesManager( 5452): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5452): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5509 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 5194:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  947): failed to open /acct/uid_10014/pid_5194/cgroup.procs: No such file or directory
I/art     ( 5452): CheckpointMarkThreadRoots callback created = 0xb050fa20
,W/ResourcesManager( 5509): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 5452): CheckpointMarkThreadRoots callback created = 0xb050fa00
,V/JNIHelp ( 5452): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5452): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5452): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  947): Killing 5213:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10021/pid_5213/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5539 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  947): Explicit concurrent mark sweep GC freed 22529(1238KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.268ms total 184.509ms
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 137 ms] updated apps [took 135 ms] 
,D/Finsky  ( 5539): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5539): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/jxcore-log( 5358): Initializing JXcore engine
,W/jxcore-log( 5358): JXcore engine is ready
W/Settings( 5539): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5539): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5539): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 5539): com.android.vending: cancel(1003285959) by com.android.vending
,V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@2ce6082d on behalf of 5539
D/Ads     ( 5539): Skipping gmscore version check
,D/Finsky  ( 5539): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5539): [1] Libraries$2.run: Finished loading 1 libraries.
W/Thread-631( 5503): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5902]" dev="sockfs" ino=5902 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-631( 5503): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-631( 5503): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6072]" dev="sockfs" ino=6072 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-631( 5503): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-631( 5503): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-631( 5503): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25511]" dev="sockfs" ino=25511 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5358): Starting JXcore engine
,I/ActivityManager(  947): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5582 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5539): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5539): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5539): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  947): Killing 5241:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/ResourcesManager( 5582): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5582): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/jxcore-log( 5358): Platform android
W/jxcore-log( 5358): 
,W/jxcore-log( 5358): Process ARCH arm
W/jxcore-log( 5358): 
I/MultiDex( 5582): VM with version 2.1.0 has multidex support
I/MultiDex( 5582): install
I/MultiDex( 5582): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  947): failed to open /acct/uid_10009/pid_5241/cgroup.procs: No such file or directory
,V/JNIHelp ( 5582): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5582): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5582): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23cf210d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5582): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5582): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5582): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5582): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5582): Reading stored module config
D/ChimeraCfgMgr( 5582): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5582): Loading module APK com.google.android.play.games
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
D/NativeLibraryUtils( 5582): Install completed successfully. count=14 extracted=0
,I/jxcore-log( 5358): JXcore Cordova bridge is ready!
I/jxcore-log( 5358): 
,W/jxcore-log( 5358): JXcore engine is started
I/art     ( 5582): CheckpointMarkThreadRoots callback created = 0xaaef6d30
,I/art     ( 5582): CheckpointMarkThreadRoots callback created = 0xaaef6d10
,D/ChimeraCfgMgr( 5582): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5582): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5582): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5582): Submit a task: k
,D/ChimeraCfgMgr( 5582): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5582): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5582): Processing package: com.test.thalitest
,D/GassUtils( 5582): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5582): Found info for package com.test.thalitest in db.
,I/Icing   ( 5582): Storage manager: low false usage 1.72MB avail 2.38GB capacity 4.06GB
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,I/jxcore-log( 5358): Toggling radios to true
I/jxcore-log( 5358): 
E/MDM     ( 1733): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/BluetoothAdapter( 5358): enable(): BT is already enabled..!
D/WifiServiceImplEx(  947): setWifiEnabled: true pid=5358, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  947): setWifiEnabled: true pid=5358, uid=10316
W/BaseAppContext( 5582): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 5582): cleanUpNonGplusAccounts done.
D/WifiServiceImplEx(  947): disconnect pid=5358, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  947): reconnect pid=5358, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5358): Radios toggled
I/jxcore-log( 5358): 
I/jxcore-log( 5358): My device name is: LGE-LG-D722
I/jxcore-log( 5358): 
I/art     ( 5582): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5582): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/wpa_supplicant( 2810): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2810): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  947): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  947): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  947): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  947): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  276): Clearing all IP addresses on wlan0
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1733): Read error: ssl=0xaaedfe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaedfe00: I/O error during system call, Broken pipe
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20(  947): hidePasspointNotification off =false
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:22.018 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  947): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  947): hidePasspointNotification off =false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=-10ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): Forcing reevaluation
E/WifiStateMachine(  947): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 2810): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:22.038 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  947): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  947): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
E/BaseAppContext( 5582): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5582): Using Auth Proxy for data requests.
D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/ConnectivityService(  947): Default network via Wi-Fi disconnect. stop DSQN
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:22.147 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DSQN    (  947): disableDataServiceNotify
D/WifiHS20(  947): hidePasspointNotification off =false
D/DSQN    (  947): stop dsqn bin
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/ConnectivityService(  947): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/WifiNetworkAgent(  947): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  947): hidePasspointNotification off =false
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:22.181 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:22.186 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/BaseAppContext( 5582): Using Auth Proxy for data requests.
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateDISCONNECTED
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  947): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateSCANNING
D/LocationInitializer( 5582): Restart initialization of location
D/Nat464Xlat(  947): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): Disconnected - quitting
D/CSLegacyTypeTracker(  947): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  947): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  947): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1840): |CORE| No family connected
V/NetworkPolicy(  947): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  947): MasterInitialState.processMessage what=3
W/ActivityManager(  947): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  947): RTC_WAKEUP set : Alarm{3538e5af type 0 when 1454285556282 com.android.providers.contacts} when 1454285556282
V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{138f4dbc type 2 when 60178 com.google.android.talk} when 60178
D/ConnectivityService(  947): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  947): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DhcpStateMachine(  947): StoppedState
D/DhcpStateMachine(  947): StoppedState{ when=-189ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/AlarmManager(  947): RTC_WAKEUP set : Alarm{375e109a type 0 when 1454717602206 com.google.android.googlequicksearchbox} when 1454717602206
,D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  947): MasterInitialState.processMessage what=3
V/NetworkPolicy(  947): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkManagementService(  947): Removing idletimer
W/Settings(  947): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  947): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5582): Using Auth Proxy for data requests.
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/BaseAppContext( 5582): Using Auth Proxy for data requests.
W/BaseAppContext( 5582): Using Auth Proxy for data requests.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  947): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5648 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Icing   ( 5582): Array storage bad crc 1219874408 vs 4612308
,E/Icing   ( 5582): Array storage bad crc 2266763706 vs 2351971754
E/Icing   ( 5582): Array storage bad crc 1639874009 vs 3640793788
E/Icing   ( 5582): Trie mmap suffix failed
,W/Icing   ( 5582): Docstore bad crc 0x56ea04cd vs 0x1b356bad
,W/BaseAppContext( 5582): Using Auth Proxy for data requests.
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,W/IcingInternalCorpora( 5582): getNumBytesRead when not calculated.
,E/Icing   ( 5582): Array storage bad crc 2024692317 vs 0
E/Icing   ( 5582): Trie mmap node failed
,D/InitAlarmsService( 3752): Clearing and rescheduling alarms.
I/ActivityManager(  947): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5673 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5673): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 5582): Background sticky concurrent mark sweep GC freed 15446(1419KB) AllocSpace objects, 14(224KB) LOS objects, 12% free, 12MB/14MB, paused 5.724ms total 66.311ms
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/CalendarProvider2( 5673): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@29fce420
,D/CalendarProvider2( 5673): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5673): Created com.android.providers.calendar.CalendarAlarmManager@735f295(com.android.providers.calendar.CalendarProvider2@29fce420)
D/CalendarProvider2( 5673): Scheduling check of next Alarm
D/CalendarProvider2( 5673): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  947): Killing 3752:com.android.calendar/u0a13 (adj 15): empty #11
,I/Icing   ( 5582): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  947): failed to open /acct/uid_10013/pid_3752/cgroup.procs: No such file or directory
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2810): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/ChimeraCfgMgr( 5582): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5582): Module APK com.google.android.play.games already loaded
,D/LocSvc_java(  947): onReceive
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.221 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/Gmail   ( 5648): getAccountsCursor
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.224 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateASSOCIATING
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2810): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateASSOCIATED
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
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.253 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.256 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 2810): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2810): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/WifiServiceExtension(  947): setVHTCapabilityType  : false
I/WifiServerServiceExt(  947): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
W/GAV2    ( 5648): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/WifiServerServiceExt(  947): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  947): setSecurityType  : 2
D/ConnectivityService(  947): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  947): Got NetworkAgent Messenger
,D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  947): NetworkAgent connected
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.331 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.335 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine(  947): Start Dhcp Watchdog 2
D/DhcpStateMachine(  947): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  947): WaitBeforeStartState
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateGROUP_HANDSHAKE
E/Gmail   ( 5648): Error finding the version of the Email provider.....
E/Gmail   ( 5648): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5648): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5648): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5648): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5648): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5648): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5648): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5648): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5648): We do not support migrating this version of the Email provider.
D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateCOMPLETED
I/Gmail   ( 5648): getAccountsCursor
,I/ActivityManager(  947): Killing 5266:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  947): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  947): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  947): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29e5456e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  947): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29e5456e target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  947): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  947): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  947): DHCP Start wake lock is acquired.
D/CommandListener(  276): Setting iface cfg
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  947): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
W/ActivityManager(  947): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  947): failed to open /acct/uid_10011/pid_5266/cgroup.procs: No such file or directory
D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  947): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  947): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  947): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  947): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  947): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  947): ignoring duplicate network state non-change
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.531 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  947): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  947): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.54 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiHS20(  947): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService(  947): Unexpected mtu value: 0, wlan0
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  947): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  947): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  276): netlink response contains error (File exists)
,D/WifiHS20(  947): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.567 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  947): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Gmail   ( 5648): Observing account changes for notifications
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:23.572 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  947): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  947): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  947): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/Nat464Xlat(  947): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  947): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  947): currentScore = 0, newScore = 20
D/ConnectivityService(  947):    accepting network in place of null
D/ConnectivityService(  947): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  947): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  947): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  947): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  947): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  947): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  947): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  947): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  947): validation of new default Network = false
D/ConnectivityService(  947): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  947): enableDataServiceNotify 
D/DSQN    (  947): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): [LWD] wait 500ms before dns check
V/NetworkPolicy(  947): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService(  947): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/DSQN    ( 5724): DSQN samuel.seo ver 141203
E/DSQN    ( 5724): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5724): created command queue thread
I/DSQN    ( 5724): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5724): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/DhcpStateMachine(  947): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  947): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  947): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/dhcpcd  ( 5727): version 5.5.6 starting
E/dhcpcd  ( 5727): get_duid: Read-only file system
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/dhcpcd  ( 5727): wlan0: rebinding lease of 192.168.1.134
,I/Gmail   ( 5648): notifyAccountChanged
I/Gmail   ( 5648): getAccountsCursor
I/Gmail   ( 5648): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5648): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 5432): Explicit concurrent mark sweep GC freed 7853(395KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 852us total 146.874ms
I/Gmail   ( 5648): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5648): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5582): Internal init done: storage state 0
I/dhcpcd  ( 5727): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/art     (  947): Explicit concurrent mark sweep GC freed 57577(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.498ms total 220.585ms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 5727): wlan0: leased 192.168.1.134 for 86400 seconds
,I/NotificationManager( 5582): com.google.android.gms: cancel(10436) by com.google.android.gms
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@343d6162 on behalf of 5582
,I/Icing   ( 5582): 22 corpora need re-polling
,W/InstanceID/Rpc( 5582): Found 10006
W/InstanceID/Rpc( 5582): Found 10006
,I/Icing   ( 5582): Post-init done
,I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5752 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/CalendarProvider2( 5673): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5673): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.989ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.006ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 21.174ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): [LWD] DNSResolver start dns
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
I/ActivityManager(  947): Killing 5296:com.android.gallery3d/u0a23 (adj 15): empty #11
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 3171): Explicit concurrent mark sweep GC freed 6409(376KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.004ms total 53.255ms
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@259a82f3 on behalf of 5582
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  947): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5724): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5724): restart monitoring
,D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5724): dsqn report finish
D/DSQN    (  947): DSQM DsqnNotification wlan0  1
D/DSQN    (  947): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 06 Feb 2016 00:13:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454717604225], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454717604203]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/libprocessgroup(  947): failed to open /acct/uid_10023/pid_5296/cgroup.procs: No such file or directory
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  947): Validated
D/ConnectivityService(  947): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  947): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  947): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  947): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  947): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  947): set CMD_CAPTIVE_CHECK_COMPLETED
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@11a1fbb0 on behalf of 5582
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/Icing   ( 5582): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  947): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  947): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  947): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  947): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  947): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  947): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  947): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  947): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  947): RunningState
I/ActivityManager(  947): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5782 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PhoneMonitor( 5752): Register our PhoneStateListener
,I/ActivityManager(  947): Killing 5328:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10018/pid_5328/cgroup.procs: No such file or directory
,V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{23935280 type 2 when 86580 com.google.android.gms} when 86580
,D/PhoneMonitor( 5752): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5752): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5752): [parse] Load xml
V/TelephonyAutoProfiling( 5752): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5752): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5752): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     ( 5582): Background sticky concurrent mark sweep GC freed 12402(801KB) AllocSpace objects, 7(112KB) LOS objects, 6% free, 13MB/14MB, paused 5.108ms total 41.161ms
I/CheckinService( 5582): Checkin interval check for package: unspecified last checkin: 1454717595483 min interval config: 0 actual interval: 9039
,I/CheckinService( 5582): Disabling old GoogleServicesFramework version
,I/Gmail   ( 5648): getAccountsCursor
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5582): Checking schedule, now: 1454717604607 next: 1454717625445
I/CheckinService( 5582): active receiver: disabled
,D/ConnectivityService(  947): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  947): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5807 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  947): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  947): identical MTU - not setting
D/Nat464Xlat(  947): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  947): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:24.711 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  947): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  947): enableDataServiceNotify 
D/DSQN    (  947): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
D/DSQN    (  947): dsqn is running restart
,I/DSQN    ( 5827): DSQN samuel.seo ver 141203
E/DSQN    ( 5827): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5827): created command queue thread
I/DSQN    ( 5827): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5827): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/MusicStore( 5782): Database version: 120
,W/ResourcesManager( 5807): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5782): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5782): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5782): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5782): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5782): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5782): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 5807): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5807): MmsConfig.loadMmsSettings
I/Babel_SMS( 5807): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5807): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5807): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5807): MmsConfig.loadFromResources
,E/Babel_SMS( 5807): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5807): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  947): onReceive
D/LocSvc_java(  947): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  947): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  947): broadcast - no network connections
D/LocSvc_java(  947): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  947): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  947): onReceive
D/LocSvc_java(  947): got connectivity action
D/LocSvc_java(  947): broadcast - no network connections
D/LocSvc_java(  947): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  947): Sending msg: 4 arg1:0 arg2:1
W/art     ( 5782): Suspending all threads took: 6.076ms
D/LocSvc_java(  947): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  947): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  947): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  947): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  947): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  947): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  947): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityThread( 5782): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5782): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@324839d4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5782): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5782): GMSCore installation verified
D/GpsLocationProvider(  947): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 5782): Background sticky concurrent mark sweep GC freed 21009(1069KB) AllocSpace objects, 4(64KB) LOS objects, 8% free, 10MB/11MB, paused 25.723ms total 138.972ms
I/ConfigStore( 5782): Config Database version: 1
,D/GpsLocationProvider(  947): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Icing   ( 5582): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
I/Icing   ( 5582): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
W/ActivityManager(  947): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{34e89278 5582:com.google.android.gms/u0a6} (pid=5582, uid=10006) that is not exported from uid 10046
,E/Icing   ( 5582): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{34e89278 5582:com.google.android.gms/u0a6} (pid=5582, uid=10006) that is not exported from uid 10046
I/Icing   ( 5582): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
E/Icing   ( 5582): Aborting indexing of corpus volumes__id
I/Icing   ( 5582): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/SensorManager( 5807): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5807): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5807): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5807): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5807): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5807): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5807): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5807): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5807): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5807): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5807): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5807): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5807): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5807): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5807): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5807): found sensor: Motion Accel, handle=46
,I/art     ( 5807): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/MediaRouter( 5782): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/NetworkMonitor( 5782): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader(  947): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/Settings( 5807): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     ( 5807): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/Babel_Crash( 5807): startup - clean
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  947): Handling package changes for user 0
,I/Babel   ( 5807): deleted: false for 0
,I/ActivityManager(  947): Process com.lge.bnr (pid 5122) has died
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/NetworkMonitor( 5782): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5782): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5782): Using platform SSLCertificateSocketFactory
I/art     ( 5782): CheckpointMarkThreadRoots callback created = 0xb0516a70
I/art     ( 5782): CheckpointMarkThreadRoots callback created = 0xb0516a40
,I/NotificationManager( 5782): com.google.android.music: cancel(1061) by com.google.android.music
,I/art     ( 5582): WaitForGcToComplete blocked for 6.772ms for cause HeapTrim
I/NotificationService(  947): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  947): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  947): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  947): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  947): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  947): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@15a42c39
,W/AudioCapabilities( 5807): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5807): Unsupported mime audio/adpcm
W/AudioCapabilities( 5807): Unsupported mime audio/g726
,W/AudioCapabilities( 5807): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5807): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5807): Unsupported mime video/mjpg
,W/art     ( 5807): Suspending all threads took: 12.116ms
,W/VideoCapabilities( 5807): Unsupported mime video/theora
I/ActivityManager(  947): Process com.google.android.apps.docs (pid 5452) has died
,W/AudioCapabilities( 5807): Unsupported mime audio/evrc
W/AudioCapabilities( 5807): Unsupported mime audio/qcelp
W/VideoCapabilities( 5807): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager(  947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/AudioCapabilities( 5807): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5807): Unsupported mime audio/qcelp
I/ActivityManager(  947): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5853 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 5807): Unsupported mime audio/evrc
,I/AudioManager( 5101): getMode name:com.lge.qremote
W/VideoCapabilities( 5807): Unsupported mime video/mp4v-esdp
,I/AudioManager( 5101): getMode name:com.lge.qremote
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
I/AudioManager( 5101): getMode name:com.lge.qremote
,I/VideoCapabilities( 5807): Unsupported profile 4 for video/mp4v-es
,W/ResourceType(  947): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/VideoCapabilities( 5807): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5807): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5807): Unrecognized profile 2130706433 for video/avc
I/AudioManager( 5101): getMode name:com.lge.qremote
W/VideoCapabilities( 5807): Unrecognized profile 2130706433 for video/avc
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-06 01:13:26.402 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AudioManager( 5101): getMode name:com.lge.qremote
D/UEI.SmartControl( 5853): Quickset Services start...
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
I/UEI.SmartControl( 5853): Manufacture = LGE
I/vclib   ( 5807): onServiceConnected
D/UEI.SmartControl( 5853): File observer start...
,E/UEI.SmartControl( 5853): IR Port is disabled: false
D/UEI.SmartControl( 5853): Starting file observer...
D/UEI.SmartControl( 5853): Extracting JNI libs...
W/Babel   ( 5807): Attempted to change video mute state without an active call.
D/UEI.SmartControl( 5853): --- this system supports 32-bit or 64-bit only
E/MDM     ( 1733): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/NotificationManager( 5807): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LocationInitializer( 5582): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
V/WifiInternetCheck(  947): Single check msg out of sync, ignoring.
,I/ActivityManager(  947): Process com.android.vending (pid 5539) has died
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 5101): getMode name:com.lge.qremote
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  947): onReceive
D/LocSvc_java(  947): got connectivity action
D/LocSvc_java(  947): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  947): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  947): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  947): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  947): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 5782): type=WIFI subType= reason=null isConnected=true
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/GpsLocationProvider(  947): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/ResourcesManager( 5807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LocationProviderProxy(  947): applying state to connected service
D/GpsLocationProvider(  947): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  947): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5881 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 5807): com.google.android.talk: cancel(8) by com.google.android.talk
,W/art     ( 5807): Suspending all threads took: 9.639ms
,V/JNIHelp ( 5807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  947): Explicit concurrent mark sweep GC freed 48791(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.655ms total 192.529ms
,I/AppUp4:AppBoxCP( 5881): onCreate
,W/AppUp4:DB( 5881):  [AppBoxDatabaseHelper] construct
D/UEI.SmartControl( 5853): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5853): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5853): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/AppUp4:DB( 5881):  setFingerPrint start
I/AppUp4:DB( 5881):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5881):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5881):  SDK version = 0
I/AppUp4:DB( 5881):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5881): AppBoxApplication onCreate()
W/System  ( 5807): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5807): Installed default security provider GmsCore_OpenSSL
,I/AppUp4:CustModeStarterReceiver( 5881): onReceive
I/AppUp4:CustModeStarterReceiver( 5881): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/UEI.SmartControl( 5853): --- Selecting new region: 2
I/UEI.SmartControl( 5853): -- Running on KitKat(19) and above! JNI will be used.
D/AppUp4:CustFacade( 5881): Context : android.app.ReceiverRestrictedContext@31f8f27f
D/AppUp4:CustFacade( 5881): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5881): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5881): begin check event
I/AppUp4:CustModeStarterReceiver( 5881): Event For Nothing, skip.
D/UEI.SmartControl( 5853): Platform has CIR...
D/UEI.SmartControl( 5853): NO CIR support, need to check package...
I/UEI.SmartControl( 5853): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5853): QS Service created
,I/ActivityManager(  947): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5901 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,E/UEI.SmartControl( 5853): QS start get config
,I/ActivityManager(  947): Process com.google.android.apps.plus (pid 5509) has died
,D/UEI.SmartControl( 5853): Loading JNI Libs...
,D/UEI.SmartControl( 5853):  configuring local db...
W/ResourcesManager( 5901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5901): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5901): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/NotificationManager( 1943): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/Icing   ( 5582): Loaded CLD2 Version V2.0 - 20141016
,I/AppConfig( 5901): Total System Memory = 906309632
,I/GalleryUtils( 5901): Application Heap = 96 MB
I/AppConfig( 5901): App Tier : NOT_DEF
,D/SystemHelper( 5901): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  947): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5923 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/UEI.SmartControl( 5853):  ---- Has DB8: true
,D/UEI.SmartControl( 5853): QS start statue = true Error code = 0
D/UEI.SmartControl( 5853): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5853): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5853): IRRCDataComm has AudioManager!!!!.
,D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
W/irrc_jni( 5853): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5853): IrrcClient ++ 
D/irrcClient( 5853): getIrrcService ++ 
,W/ResourcesManager( 5923): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/irrcClient( 5853): getIrrcService -- 
D/irrcClient( 5853): IrrcClient -- 
W/irrc_jni( 5853): IRRCPlayer_nativeInit -- 
W/ResourcesManager( 5923): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/UEI.SmartControl( 5853): Services init done
,I/System.out(  947): propertyValue:false
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  947): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  947): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  947): propertyValue:false
D/UEI.SmartControl( 5853): QS Service init finished
D/UEI.SmartControl( 5853): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5853): QS Service version code: 1073
D/UEI.SmartControl( 5853): Service requested: Control
I/UEI.SmartControl( 5853): Device manager: loading config....
D/UEI.SmartControl( 5853): Config is loaded...
I/DSQN    ( 5827): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5827): restart monitoring
I/DSQN    ( 5827): dsqn report finish
D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  947): DSQM DsqnNotification wlan0  1
D/DSQN    (  947): start to monitor internet connection
,V/WifiInternetCheck(  947): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 5853):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5853): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5853): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5853): Internal service binding...
D/UEI.SmartControl( 5853): -----IControl: 11
,D/UEI.SmartControl( 5853): Caller: com.lge.qremote
D/UEI.SmartControl( 5853): ------------ IControl registerCallback...
I/UEI.SmartControl( 5853): Registering callback...
D/UEI.SmartControl( 5853): -----IControl: 19
D/UEI.SmartControl( 5853): Caller: com.lge.qremote
I/UEI.SmartControl( 5853): Registering Services Ready callback...
I/UEI.SmartControl( 5853): Notify client services are ready...
D/UEI.SmartControl( 5853): -----IControl: 8
,D/UEI.SmartControl( 5853): Caller: com.lge.qremote
I/ActivityManager(  947): Killing 5383:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/Icing   ( 5582): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  947): failed to open /acct/uid_10069/pid_5383/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=5947 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{11af2766 type 2 when 90153 com.android.providers.calendar} when 90153
,I/SystemConfig( 5923): BUILD Country: EU
I/SystemConfig( 5923): BUILD Operator: OPEN
,W/ResourcesManager( 5947): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/SystemConfig( 5923): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5923): existFile = false
I/SystemConfig( 5923): canReadFile = false
I/SystemConfig( 5923): systemFeature RCS result false
D/SystemConfig( 5923): refreshRcsSupport() :false
I/ActivityManager(  947): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5966 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 5414:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_5414/cgroup.procs: No such file or directory
,I/GAV2    ( 5648): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5582): Google Analytics 8.4.89 is starting up.
,I/LockScreenSettings( 5966): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5966): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5966): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 5966): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5966): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5966): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6000 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  947): Killing 5673:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10014/pid_5673/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Killing 5648:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10053/pid_5648/cgroup.procs: No such file or directory
,I/Icing   ( 5582): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
,I/Icing   ( 5582): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
I/Icing   ( 5582): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
I/Icing   ( 5582): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
,W/PlayMovies( 5947): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5947): 
,I/Icing   ( 5582): Indexing done FC5805F301A6400196925772B79FE617968B1409
,I/Icing   ( 5582): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
I/Icing   ( 5582): Indexing done 261F31C44790DA98645222D6E4244392E5409193
I/Icing   ( 5582): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
I/ActivityManager(  947): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6041 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/PlayMovies( 5947): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5947): 
I/Icing   ( 5582): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
I/Icing   ( 5582): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
,D/PlayMovies( 5947): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 5947): 
D/PlayMovies( 5947): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 5947): 
,I/Icing   ( 5582): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
,I/Icing   ( 5582): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
W/AudioCapabilities( 5947): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5947): Unsupported mime audio/adpcm
W/AudioCapabilities( 5947): Unsupported mime audio/g726
W/AudioCapabilities( 5947): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5947): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5947): Unsupported mime video/mjpg
W/VideoCapabilities( 5947): Unsupported mime video/theora
I/ActivityManager(  947): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.SearchQuery$Provider: pid=6066 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 21.608ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.080ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.245ms
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/art     ( 5432): Explicit concurrent mark sweep GC freed 2830(112KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 685us total 37.046ms
,W/AudioCapabilities( 5947): Unsupported mime audio/evrc
,W/AudioCapabilities( 5947): Unsupported mime audio/qcelp
W/VideoCapabilities( 5947): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5947): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5947): Unsupported mime audio/qcelp
W/AudioCapabilities( 5947): Unsupported mime audio/evrc
W/VideoCapabilities( 5947): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5947): Unsupported profile 4 for video/mp4v-es
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 124 ms] updated apps [took 124 ms] 
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): CdmEngine::QueryStatus
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5947): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
,I/WVCdm   (  281): L3 Terminate.
W/art     ( 5947): No such thread id for suspend: 38
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Finsky  ( 6041): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 6066): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6066): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  947): Killing 5752:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  947): failed to open /acct/uid_10038/pid_5752/cgroup.procs: No such file or directory
I/Icing   ( 5582): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
,I/Icing   ( 5582): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
I/ActivityManager(  947): Process com.google.android.music:main (pid 5782) has died
,W/ActivityManager(  947): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6066): Observing account changes for notifications
,I/ActivityManager(  947): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6111 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6066): getAccountsCursor
E/Gmail   ( 6066): Error finding the version of the Email provider.....
E/Gmail   ( 6066): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6066): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6066): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6066): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6066): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6066): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6066): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6066): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6066): We do not support migrating this version of the Email provider.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6041): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 6041): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6041): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6041): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 6041): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6041): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6041): Skipping gmscore version check
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@36c7fa29 on behalf of 6041
I/ActivityManager(  947): Killing 5853:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,D/Finsky  ( 6041): [709] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
I/MusicStore( 6111): Database version: 120
D/Finsky  ( 6041): [709] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,W/System.err( 5101): android.os.DeadObjectException
,W/System.err( 5101): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5101): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5101): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5101): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5101): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 5101): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5101): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5101): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5101): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5101): android.os.DeadObjectException
W/System.err( 5101): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5101): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5101): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5101): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5101): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5101): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5101): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5101): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5101): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/Gmail   ( 6066): notifyAccountChanged
,I/Gmail   ( 6066): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6066): getAccountsCursor
I/Gmail   ( 6066): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6066): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6066): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     (  947): Explicit concurrent mark sweep GC freed 22309(1213KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.408ms total 175.730ms
,W/libprocessgroup(  947): failed to open /acct/uid_10089/pid_5853/cgroup.procs: No such file or directory
,W/ActivityManager(  947): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms,
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6041): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  947): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6160 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PackageBroadcastService( 5582): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5582): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 5101): getMode name:com.lge.qremote
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6111): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/AudioManager( 5101): getMode name:com.lge.qremote
D/Finsky  ( 6041): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 6160): Quickset Services start...
,I/UEI.SmartControl( 6160): Manufacture = LGE
D/UEI.SmartControl( 6160): File observer start...
E/UEI.SmartControl( 6160): IR Port is disabled: false
D/UEI.SmartControl( 6160): Starting file observer...
D/UEI.SmartControl( 6160): Extracting JNI libs...
D/UEI.SmartControl( 6160): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6190 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6111): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6111): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6111): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6111): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 6066): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 6111): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 6190): Register our PhoneStateListener
W/ActivityThread( 6111): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6111): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@324839d4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6111): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6111): GMSCore installation verified
I/art     ( 6111): CheckpointMarkThreadRoots callback created = 0xb042d510
,D/UEI.SmartControl( 6160): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6160): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6160): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  947): Process com.android.contacts (pid 5923) has died
I/ConfigStore( 6111): Config Database version: 1
,I/art     ( 6111): CheckpointMarkThreadRoots callback created = 0xb042d4f0
I/Icing   ( 5582): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
,I/Icing   ( 5582): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 5582): Aborting indexing of corpus omnibox
I/Icing   ( 5582): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
I/Icing   ( 5582): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 5582): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
I/UEI.SmartControl( 6160): --- Selecting new region: 2
I/UEI.SmartControl( 6160): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6160): Platform has CIR...
,D/UEI.SmartControl( 6160): NO CIR support, need to check package...
I/UEI.SmartControl( 6160): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6160): QS Service created
I/Icing   ( 5582): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
I/Icing   ( 5582): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
I/ActivityManager(  947): Process com.android.gallery3d (pid 5901) has died
,V/AlarmManager(  947): RTC_WAKEUP set : Alarm{94f5129 type 0 when 1454717611320 com.android.vending} when 1454717611320
V/SetupWizard( 6190): Connected to Gservices successfully
,D/Finsky  ( 6041): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,E/UEI.SmartControl( 6160): QS start get config
,D/PhoneMonitor( 6190): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6190): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6190): [parse] Load xml
,I/Icing   ( 5582): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/Icing   ( 5582): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/TelephonyAutoProfiling( 6190): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6190): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/UEI.SmartControl( 6160): Loading JNI Libs...
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 6160):  configuring local db...
D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/LocationInitializer( 5582): Restart initialization of location
,D/PhoneMonitor( 6190): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/MediaRouter( 6111): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
I/NetworkMonitor( 6111): type=WIFI subType= reason=null isConnected=true
,I/Icing   ( 5582): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
I/Icing   ( 5582): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NetworkMonitor( 6111): type=WIFI subType= reason=null isConnected=true
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 29318(1899KB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 13MB/22MB, paused 1.394ms total 132.158ms
I/Icing   ( 5582): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
I/Icing   ( 5582): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/AlarmManager(  947): RTC_WAKEUP set : Alarm{3b932227 type 0 when 1454717611609 com.google.android.googlequicksearchbox} when 1454717611609
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GHttpClientFactory( 6111): Using our fixed implementation of GMSCore's GoogleHttpClient
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GoogleURLConnFactory( 6111): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1733): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/NotificationManager(  947): android: cancelAsUser(2) by android
,I/ActivityManager(  947): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6231 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/Icing   ( 5582): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
I/Icing   ( 5582): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
,I/NotificationManager( 6111): com.google.android.music: cancel(1061) by com.google.android.music
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5358): 
,D/UEI.SmartControl( 6160):  ---- Has DB8: true
,D/UEI.SmartControl( 6160): QS start statue = true Error code = 0
D/UEI.SmartControl( 6160): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6160): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6160): IRRCDataComm has AudioManager!!!!.
,D/libc-netbsd( 6041): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6041): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6041): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6041): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/Icing   ( 5582): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
I/Icing   ( 5582): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 6041): propertyValue:false
D/libc-netbsd( 6041): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6041): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/irrc_jni( 6160): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6160): IrrcClient ++ 
D/irrcClient( 6160): getIrrcService ++ 
,D/irrcClient( 6160): getIrrcService -- 
D/irrcClient( 6160): IrrcClient -- 
W/irrc_jni( 6160): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6160): Services init done
,I/UEI.SmartControl( 6160): Device manager: loading config....
I/Icing   ( 5582): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
D/UEI.SmartControl( 6160): QS Service init finished
I/Icing   ( 5582): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
D/UEI.SmartControl( 6160): QS Service version name: 0.1.73
D/UEI.SmartControl( 6160): QS Service version code: 1073
I/Icing   ( 5582): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
D/UEI.SmartControl( 6160): Config is loaded...
I/Icing   ( 5582): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
D/UEI.SmartControl( 6160): Service requested: Control
,I/Icing   ( 5582): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
,D/UEI.SmartControl( 6160): -----IControl: 11
D/UEI.SmartControl( 6160): Caller: com.lge.qremote
D/UEI.SmartControl( 6160): ------------ IControl registerCallback...
D/UEI.SmartControl( 6160): Internal service binding...
I/UEI.SmartControl( 6160): Registering callback...
D/UEI.SmartControl( 6160): -----IControl: 19
D/UEI.SmartControl( 6160): Caller: com.lge.qremote
I/UEI.SmartControl( 6160): Registering Services Ready callback...
D/libc-netbsd( 6041): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6041): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6231): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6160):  ----- QS SDK is ready!!!
W/ResourcesManager( 6231): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6231): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/UEI.SmartControl( 6160): Notify AllClients services are ready: 0
W/ResourcesManager( 6231): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6231): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Icing   ( 5582): updateResources: need to parse f{com.google.android.gms}
D/UEI.SmartControl( 6160): -----IControl: 8
D/UEI.SmartControl( 6160): Caller: com.lge.qremote
,I/ActivityManager(  947): Killing 5807:com.google.android.talk/u0a61 (adj 15): empty #11
,I/IndexDatabaseHelper( 6231): Using schema version: 115
,I/IndexDatabaseHelper( 6231): Index is fine
W/libprocessgroup(  947): failed to open /acct/uid_10061/pid_5807/cgroup.procs: No such file or directory
,I/Icing   ( 5582): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  947): android: cancelAsUser(2) by android
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
I/qtaguid ( 6041): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6041): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6041): untagSocket(41) failed with errno -22
D/Finsky  ( 6041): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  947): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6264 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 5881:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10011/pid_5881/cgroup.procs: No such file or directory
,I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  947): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6285 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  947): Process com.google.android.videos (pid 5947) has died
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  947): android: cancelAsUser(2) by android
,W/ResourcesManager( 6285): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6285): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5358): 
,I/MultiDex( 6285): VM with version 2.1.0 has multidex support
I/MultiDex( 6285): install
I/MultiDex( 6285): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  947): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6309 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  947): Process com.google.android.apps.plus (pid 6000) has died
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5358): 
W/ResourcesManager( 6309): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/JNIHelp ( 6285): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 95386814083; DSPS: 3224019; Offset : -3009780097
,W/ActivityThread( 6285): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6285): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38505b4f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6285): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6285): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6285): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6285): Reading stored module config
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5358): 
,I/ActivityManager(  947): Process com.lge.lockscreensettings (pid 5966) has died
,D/ChimeraCfgMgr( 6285): Loading module com.google.android.gms.car from APK com.google.android.gms
I/Icing   ( 5582): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5582): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/NativeLibraryUtils( 6285): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  947): Process com.google.android.music:main (pid 6111) has died
,D/CAR.SERVICE( 6285): Connecting to CarCallService...
,I/Babel_SMS( 6309): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6309): MmsConfig.loadMmsSettings
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5358): 
,I/art     ( 6309): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/art     (  947): Explicit concurrent mark sweep GC freed 16752(770KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.853ms total 148.247ms
I/art     ( 6309): CheckpointMarkThreadRoots callback created = 0xb042d530
,I/ActivityManager(  947): Process com.google.android.gm (pid 6066) has died
,D/UEI.SmartControl( 6160): Service.onTrimMemory: 60
E/UEI.SmartControl( 6160): Setup service releasing memory...
I/PhoneApp( 1750): onTrimMemory: 10
I/PhoneApp( 1750): trim memory
,I/BackgroundMemoryTrimmer( 1943): Trimming objects from memory, since app is in the background.
I/Babel_SMS( 6309): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6309): MmsConfig.loadFromDatabase
,I/art     ( 6285): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6285): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6309): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6309): MmsConfig.loadFromResources
E/Babel_SMS( 6309): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6309): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6309): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6309): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6309): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6309): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6309): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6309): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6309): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6309): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6309): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6309): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6309): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6309): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6309): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6309): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6309): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6309): found sensor: Motion Accel, handle=46
I/art     ( 6160): Explicit concurrent mark sweep GC freed 10504(753KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 380us total 74.222ms
D/CAR.SERVICE( 6285): com.google.android.projection.gearhead isn't installed.
,W/Settings( 6309): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6309): startup - clean
D/CAR.TEL.Service( 6285): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6285): Creating a new PhoneAdapter instance
I/Babel   ( 6309): deleted: false for 0
,W/ActivityManager(  947): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6285): setListener: com.google.android.gms.car.dn@3e12466a
W/ActivityManager(  947): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6285): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6285): Starting CarCallService with initial phone null
I/NotificationManager( 6285): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/qtaguid ( 6041): Failed write_ctrl(u 41) res=-1 errno=22
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6309): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6309): Unsupported mime audio/adpcm
I/qtaguid ( 6041): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6041): untagSocket(41) failed with errno -22
D/UEI.SmartControl( 6160): Service.onTrimMemory: 60
E/UEI.SmartControl( 6160): Setup service releasing memory...
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
W/AudioCapabilities( 6309): Unsupported mime audio/g726
W/AudioCapabilities( 6309): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6309): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6309): Unsupported mime video/mjpg
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6264): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/CAR.SERVICE( 6285): Package validated; name: com.android.vending
W/VideoCapabilities( 6309): Unsupported mime video/theora
D/UEI.SmartControl( 6160): Service.onTrimMemory: 60
E/UEI.SmartControl( 6160): Setup service releasing memory...
,V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/NotificationManager( 6041): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6041): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
W/AudioCapabilities( 6309): Unsupported mime audio/evrc
W/AudioCapabilities( 6309): Unsupported mime audio/qcelp
W/VideoCapabilities( 6309): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6309): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6309): Unsupported mime audio/qcelp
W/AudioCapabilities( 6309): Unsupported mime audio/evrc
W/VideoCapabilities( 6309): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6309): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6309): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6309): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6309): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6309): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6309): onServiceConnected
,W/Babel   ( 6309): Attempted to change video mute state without an active call.
I/ActivityManager(  947): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6352 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 6309): Suspending all threads took: 26.104ms
,I/art     ( 6041): WaitForGcToComplete blocked for 57.977ms for cause HomogeneousSpaceCompact
I/NotificationManager( 6309): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6309): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6309): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6309): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6352): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6352): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/art     ( 6041): CheckpointMarkThreadRoots callback created = 0xb055d790
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6352): Error finding the version of the Email provider.....
E/Gmail   ( 6352): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6352): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6352): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6352): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6352): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6352): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6352): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6352): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6352): We do not support migrating this version of the Email provider.
,I/art     ( 6041): CheckpointMarkThreadRoots callback created = 0xb055d170
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6231): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Gmail   ( 6352): getAccountsCursor
D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  947): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6352): Observing account changes for notifications
D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6231): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6231): MCCMNC not supported: null
I/PCSuite ( 6264): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6264): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/Gmail   ( 6352): notifyAccountChanged
,I/Gmail   ( 6352): getAccountsCursor
I/Gmail   ( 6352): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6352): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6352): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6352): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  947): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6396 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5432): Explicit concurrent mark sweep GC freed 2914(115KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 434us total 28.980ms
,W/ResourcesManager( 6396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6352): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarApplication( 6396): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6396): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6396): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@a10e79e, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@31f8f27f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2e1c224c, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@735f295, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@361fdfaa, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2934379b, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@110f1738, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@9d02311, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@8744c76, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2214b277, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@103a6ee4, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1f02df4d, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@16d0ba02, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2f17ff13, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@38a19550, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@242b2349, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1e94744e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2f9796f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2212b67c, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1579ab05, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1c7875a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@16ce3d8b, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3112be68, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@76ef281, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@8e6bf26, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@15e12767, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@b895914, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3c1735bd, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@356fa7b2, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4ed303, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2c2cf280, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@100670b9, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@312c8cfe, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@d619c5f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@aeb6ac, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3b145f75, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@26407b0a, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@22ad9f7b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea69198, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@20d87df1, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@bf33dd6, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1cecb857, l
D/GeneralP,referenceUtils( 6396): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6396): [init]
,I/Config  ( 6396): LGCalendar ver.4.40.17
I/Config  ( 6396): start check model
I/Config  ( 6396): start check native_ca
I/Config  ( 6396): Config Operator=OPEN, Country=EU
D/Config  ( 6396): [setDefaultValuesToPref]
D/Config  ( 6396): [parseProfiles]
D/ProfilesParser( 6396): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6396): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6396): [updateProfiletoCountryInfo]
D/GeneralPreference( 6396): [checkAndMigrateOldPreference]
D/AlertReceiver( 6396): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  947): android: cancelAsUser(2) by android
,I/qtaguid ( 6041): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6041): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6041): untagSocket(41) failed with errno -22
,I/InitNotificationRingtoneService( 6396): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6396): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/HolidayIntentService( 6396): onHandleIntent
,D/HolidayDataLoader( 6396): readJsonAsset : holiday.json
D/AlertService( 6396): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6396): [updateWidgets] 
D/MonthWidgetProvider( 6396): [onReceive]
D/CalendarWidgetProvider( 6396): [onReceive]
D/CalendarWidgetProvider( 6396): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,I/AlertUtils( 6396): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/CalendarTypeController( 6396): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,D/WeekWidgetProvider( 6396): [onReceive]
D/CalendarWidgetProvider( 6396): [onReceive]
D/CalendarWidgetProvider( 6396): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6396): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AlertUtils( 6396): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6396): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
E/HolidayIntentService( 6396): onHandleIntent:holiday data empty
I/ActivityManager(  947): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6422 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AlertUtils( 6396): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6396): End InitializeAlertRingtoneService.onHandleIntent
,W/ResourcesManager( 6041): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6041): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MusicStore( 6422): Database version: 120
,D/Finsky  ( 6041): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  947): RTC_WAKEUP set : Alarm{2d3a1e90 type 0 when 1454717616119 com.android.vending} when 1454717616119
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/DeviceConnectionService( 1733): client connected with version: 8296000
D/Finsky  ( 6041): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6041): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6422): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6422): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6422): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6422): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6422): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6422): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a8301e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6422): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6422): GMSCore installation verified
I/ConfigStore( 6422): Config Database version: 1
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/art     (  947): Explicit concurrent mark sweep GC freed 17882(824KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.079ms total 140.228ms
,I/MediaRouter( 6422): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6422): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6422): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6422): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  947): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6456 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 325us total 25.953ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.698ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 23.111ms
,I/GHttpClientFactory( 6422): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6422): Using platform SSLCertificateSocketFactory
I/ActivityManager(  947): Killing 6352:com.google.android.gm/u0a53 (adj 15): empty #11
,W/ResourcesManager( 6456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  947): failed to open /acct/uid_10053/pid_6352/cgroup.procs: No such file or directory
,I/NotificationManager( 6422): com.google.android.music: cancel(1061) by com.google.android.music
D/UEI.SmartControl( 6160): Internal timer expired: 1
,I/LGEmail ( 6456): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6456): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6456): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  947): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6487 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6456): JNI_OnLoad()
I/HubEmail( 6456): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6456): registerNatives()
I/HubEmail( 6456): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6456): registerNativeMethods()
I/HubEmail( 6456): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6456): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  947): Killing 6231:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_6231/cgroup.procs: No such file or directory
W/Settings( 6456): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6487): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6487): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6487): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6487): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6487): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6487): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6487): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6487): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  947): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6511 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6487): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6487): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6487): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6487): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6487): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6487): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  947): Killing 6160:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5101): android.os.DeadObjectException
W/System.err( 5101): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5101): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5101): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5101): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5101): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5101): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5101): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5101): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5101): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5101): android.os.DeadObjectException
W/System.err( 5101): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5101): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5101): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5101): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5101): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5101): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5101): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5101): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5101): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5101): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5101): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5101): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,E/libprocessgroup(  947): failed to kill 1 processes for processgroup 6160
,W/ActivityManager(  947): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  947): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6535 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6511): onCreate
W/AppUp4:DB( 6511):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6511):  setFingerPrint start
I/AppUp4:DB( 6511):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6511):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6511):  SDK version = 0
I/AppUp4:DB( 6511):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6511): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6511): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6511): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6511): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6511): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6511): onReceive
I/AppUp4:CustModeStarterReceiver( 6511): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6511): Context : android.app.ReceiverRestrictedContext@361fdfaa
D/AppUp4:CustFacade( 6511): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6511): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6511): begin check event
I/AppUp4:CustModeStarterReceiver( 6511): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 6511): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6511): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6511): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6511): handleAsyncCustNotification do not startCustService
I/ActivityManager(  947): Killing 6264:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6535): Quickset Services start...
I/UEI.SmartControl( 6535): Manufacture = LGE
D/UEI.SmartControl( 6535): File observer start...
E/UEI.SmartControl( 6535): IR Port is disabled: false
D/UEI.SmartControl( 6535): Starting file observer...
D/UEI.SmartControl( 6535): Extracting JNI libs...
D/UEI.SmartControl( 6535): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6535): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6535): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6535): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_6264/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3150): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3150): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3150): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6190): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6190): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3171): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/UEI.SmartControl( 6535): --- Selecting new region: 2
I/UEI.SmartControl( 6535): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6535): Platform has CIR...
D/UEI.SmartControl( 6535): NO CIR support, need to check package...
I/UEI.SmartControl( 6535): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6535): QS Service created
,I/ActivityManager(  947): Process com.android.vending (pid 6041) has died
,V/DownloadManager( 3171): DownloadService onCreate
I/DownloadManager( 3171): in removeSpuriousFiles
,E/UEI.SmartControl( 6535): QS start get config
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3171): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@261431ae on behalf of 3171
I/DownloadManager( 3171): in trimDatabase
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@38505b4f on behalf of 3171
,I/ActivityManager(  947): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6563 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3171): DownloadService onStartCommand
D/CAR.SERVICE( 6285): mConnectedToCar = false, abort
E/ActivityThread( 6285): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1284e712 that was originally bound here
E/ActivityThread( 6285): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1284e712 that was originally bound here
E/ActivityThread( 6285): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6285): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6285): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6285): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6285): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6285): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6285): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6285): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6285): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6285): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6285): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6285): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6285): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6285): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6285): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6285): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6285): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6285): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6285): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6285): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6285): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6535): Loading JNI Libs...
,D/UEI.SmartControl( 6535):  configuring local db...
V/DownloadManager( 3171): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@1075baba on behalf of 3171
E/ActivityThread( 6285): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2eeabc55 that was originally bound here
E/ActivityThread( 6285): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2eeabc55 that was originally bound here
E/ActivityThread( 6285): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6285): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6285): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6285): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6285): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6285): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6285): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6285): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6285): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6285): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6285): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6285): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6285): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6285): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6285): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6285): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6285): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6285): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6285): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6285): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  947): Unbind failed: could not find connection for android.os.BinderProxy@962f103
,V/DownloadManager( 3171): DownloadService onDestroy
,D/WeatherAncestor( 2722): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:13:38
,D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherAncestor( 2722): connectivity changed - connection : true
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2722): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:13:38
D/WeatherService( 2722): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  947): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  947): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6581 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 6309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 6309): propertyValue:false
D/UEI.SmartControl( 6535):  ---- Has DB8: true
,D/UEI.SmartControl( 6535): QS start statue = true Error code = 0
D/UEI.SmartControl( 6535): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6535): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6535): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6535): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6535): IrrcClient ++ 
D/irrcClient( 6535): getIrrcService ++ 
,D/irrcClient( 6535): getIrrcService -- 
D/irrcClient( 6535): IrrcClient -- 
W/irrc_jni( 6535): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6535): Services init done
I/UEI.SmartControl( 6535): Device manager: loading config....
D/UEI.SmartControl( 6535): QS Service init finished
,D/UEI.SmartControl( 6535): Config is loaded...
D/UEI.SmartControl( 6535): QS Service version name: 0.1.73
D/UEI.SmartControl( 6535): QS Service version code: 1073
D/UEI.SmartControl( 6535): Service requested: Control
I/ActivityManager(  947): Killing 5101:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6535):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6535): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6535): Internal service binding...
,W/libprocessgroup(  947): failed to open /acct/uid_10106/pid_5101/cgroup.procs: No such file or directory
I/Babel   ( 6309): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6581): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6581): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6581): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6581): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6581): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6581):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6581):   adb logcat -s GAv4
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/GAv4    ( 6581): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6581): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6581): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6581): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6581): Time to load native libraries: 4 ms (timestamps 1633-1637)
I/LibraryLoader( 6581): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6581): Binding Chromium to main looper Looper (main, tid 1) {30a4b63f}
,I/LibraryLoader( 6581): Expected native library version number "",actual native library version number ""
I/chromium( 6581): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6581): Initializing chromium process, singleProcess=true
,W/art     ( 6581): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6581): ApplicationContext is null in ApplicationStatus
W/chromium( 6581): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6581): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6581): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6581): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6581): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6581): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6581): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6581): Remote Branch: 
I/Adreno-EGL( 6581): Local Patches: 
I/Adreno-EGL( 6581): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb4027160, uid 10079
,I/NSApplication( 6581): Starting up...
W/AudioManagerAndroid( 6581): Requires BLUETOOTH permission
,I/ActivityManager(  947): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6646 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 6422:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ActivityManager(  947): Killing 6285:com.google.android.gms:car/u0a6 (adj 15): empty #12
,W/libprocessgroup(  947): failed to open /acct/uid_10081/pid_6422/cgroup.procs: No such file or directory
,W/libprocessgroup(  947): failed to open /acct/uid_10006/pid_6285/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6669 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 6456:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10021/pid_6456/cgroup.procs: No such file or directory
,W/ResourcesManager( 6669): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AlertService( 6396): Beginning updateAlertNotification
,I/ActivityManager(  947): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6695 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/ResourcesManager( 6695): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/CalendarProvider2( 6695): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@29fce420
,I/iu.SyncManager( 5582): SYNC; picasa accounts
,D/CalendarProvider2( 6695): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6695): Created com.android.providers.calendar.CalendarAlarmManager@735f295(com.android.providers.calendar.CalendarProvider2@29fce420)
D/AlertService( 6396): No fired or scheduled alerts
,I/NotificationManager( 6396): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6396): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 6396): com.android.calendar: cancel(19) by com.android.calendar
D/NetworkLogImpl( 5582): Loaded NetworkSpeedPredictor
I/NotificationManager( 6396): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6396): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  947): Killing 6487:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.Environment( 5582): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5582): num queued entries: 0
I/iu.UploadsManager( 5582): num updated entries: 0
,I/iu.SyncManager( 5582): NEXT; no task
W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_6487/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6396): No events found starting within 1 week.
,I/ActivityManager(  947): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6724 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 6511:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10011/pid_6511/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Killing 6396:com.android.calendar/u0a13 (adj 15): empty #11
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  947): failed to open /acct/uid_10013/pid_6396/cgroup.procs: No such file or directory
I/MusicStore( 6724): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6724): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6724): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6724): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6724): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6724): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6724): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6724): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6724): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a8301e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6724): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6724): GMSCore installation verified
I/ConfigStore( 6724): Config Database version: 1
,I/MediaRouter( 6724): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6724): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6724): type=WIFI subType= reason=null isConnected=true
,I/art     (  947): Explicit concurrent mark sweep GC freed 17981(874KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.115ms total 143.064ms
,I/NetworkMonitor( 6724): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  947): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6771 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6724): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6724): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  947): Killing 6535:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/ResourcesManager( 6771): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6771): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6771): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  947): failed to open /acct/uid_10089/pid_6535/cgroup.procs: No such file or directory
,I/NotificationManager( 6724): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6771): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6771): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6771): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  947): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 292us total 23.584ms
I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.456ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 24.827ms
,I/HubEmail( 6771): JNI_OnLoad()
I/HubEmail( 6771): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6771): registerNatives()
I/HubEmail( 6771): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6771): registerNativeMethods()
I/HubEmail( 6771): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6771): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  947): Killing 6190:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10038/pid_6190/cgroup.procs: No such file or directory
,W/Settings( 6771): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6805): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6805): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6805): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6805): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6805): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6805): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  947): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6833 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6805): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6805): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6805): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6805): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6805): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  947): Killing 6563:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10051/pid_6563/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6833): onCreate
,W/AppUp4:DB( 6833):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6833):  setFingerPrint start
I/AppUp4:DB( 6833):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6833):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6833):  SDK version = 0
I/AppUp4:DB( 6833):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6833): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6833): onReceive
I/AppUp4:CustModeStarterReceiver( 6833): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6833): Context : android.app.ReceiverRestrictedContext@361fdfaa
D/AppUp4:CustFacade( 6833): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6833): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6833): begin check event
I/AppUp4:CustModeStarterReceiver( 6833): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6833): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6833): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6833): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6833): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  947): Killing 6309:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10061/pid_6309/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3150): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3150): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3150): networkInfo.isConnected() = false
,I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6854 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 5358): Test app app.js loaded
I/jxcore-log( 5358): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1ab396 added. We now have 1 listener(s)
D/BluetoothAdapterService(164635409)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f9796f
,I/jxcore-log( 5358): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): TAP version 13
I/jxcore-log( 5358): 
,I/chromium( 5358): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 5358): 
D/PhoneMonitor( 6854): Register our PhoneStateListener
,I/jxcore-log( 5358): ok 1 should be equal
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): ok 2 should be equal
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ok 3 should be equal
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): ok 4 should be equal,
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 5358): 
D/MobileConnectivityChangeReceiver( 6854): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6854): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  947): Killing 6581:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/jxcore-log( 5358): ok 5 should be equal
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): ok 6 should be equal
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ok 7 should be equal
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ok 8 should be equal
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ok 9 should throw
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ok 10 should throw
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #parseBeacons no beacons returns null
I/jxcore-log( 5358): 
E/libprocessgroup(  947): failed to kill 1 processes for processgroup 6581
,V/DownloadManager( 3171): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneMonitor( 6854): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/jxcore-log( 5358): ok 11 should be equal
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 5358): 
V/TelephonyAutoProfiling( 6854): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6854): [parse] Load xml
V/TelephonyAutoProfiling( 6854): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6854): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/jxcore-log( 5358): ok 12 should throw
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
D/PhoneMonitor( 6854): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/jxcore-log( 5358): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 5358): 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/DownloadManager( 3171): DownloadService onCreate
I/NotificationManager( 3171): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3171): in removeSpuriousFiles
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@42d90c8 on behalf of 3171
I/DownloadManager( 3171): in trimDatabase
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@2c33c561 on behalf of 3171
I/ActivityManager(  947): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6889 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3171): DownloadService onStartCommand
V/DownloadManager( 3171): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5582): Checkin interval check for package: unspecified last checkin: 1454717595483 min interval config: 0 actual interval: 28666
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@ceef174 on behalf of 3171
I/CheckinService( 5582): Checking schedule, now: 1454717624172 next: 1454717625445
I/CheckinService( 5582): active receiver: disabled
,I/jxcore-log( 5358): ok 13 should be equal
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 5358): 
,I/ActivityManager(  947): Killing 6646:com.android.chrome/u0a48 (adj 15): empty #11
,I/jxcore-log( 5358): ok 14 (unnamed assert)
I/jxcore-log( 5358): 
,D/WeatherAncestor( 2722): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:13:44
W/libprocessgroup(  947): failed to open /acct/uid_10048/pid_6646/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherAncestor( 2722): connectivity changed - connection : true
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2722): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:13:44
D/WeatherService( 2722): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/jxcore-log( 5358): ok 15 should be equal
I/jxcore-log( 5358): 
,I/ActivityManager(  947): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6912 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
V/DownloadManager( 3171): DownloadService onDestroy
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
W/ActivityManager(  947): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
I/jxcore-log( 5358): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 5358): 
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 5358): ok 16 (unnamed assert)
I/jxcore-log( 5358): 
,I/jxcore-log( 5358): ok 17 (unnamed assert)
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # setup
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 5358): 
,I/CheckinService( 5582): Done disabling old GoogleServicesFramework version
,I/Babel_SMS( 6912): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6912): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6912): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6912): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6912): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6912): MmsConfig.loadFromResources
E/Babel_SMS( 6912): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6912): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6912): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6912): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6912): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6912): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6912): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6912): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6912): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6912): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6912): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6912): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6912): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6912): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6912): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6912): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6912): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6912): found sensor: Motion Accel, handle=46
,W/Settings( 6912): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6912): startup - clean
I/jxcore-log( 5358): ok 18 (unnamed assert)
I/jxcore-log( 5358): 
I/jxcore-log( 5358): # teardown
I/jxcore-log( 5358): 
I/Babel   ( 6912): deleted: false for 0
,I/art     ( 6912): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/art     ( 6912): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/ActivityManager(  947): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6944 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6912): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6912): Unsupported mime audio/adpcm
W/AudioCapabilities( 6912): Unsupported mime audio/g726
W/AudioCapabilities( 6912): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6912): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6912): Unsupported mime video/mjpg
,W/VideoCapabilities( 6912): Unsupported mime video/theora
W/AudioCapabilities( 6912): Unsupported mime audio/evrc
,W/AudioCapabilities( 6912): Unsupported mime audio/qcelp
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6912): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6912): Unsupported mime audio/qcelp
W/AudioCapabilities( 6912): Unsupported mime audio/evrc
,W/VideoCapabilities( 6912): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6912): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6912): onServiceConnected
W/Babel   ( 6912): Attempted to change video mute state without an active call.
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6944): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6944):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6944):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/NotificationManager( 6912): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6912): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6912): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6912): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6912): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6912): propertyValue:false
W/GAv4    ( 6944): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6944): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6912): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 6944): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  947): Killing 6669:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10086/pid_6669/cgroup.procs: No such file or directory
,I/WebViewFactory( 6944): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6944): Time to load native libraries: 1 ms (timestamps 7649-7650)
I/LibraryLoader( 6944): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6944): Binding Chromium to main looper Looper (main, tid 1) {30a4b63f}
I/LibraryLoader( 6944): Expected native library version number "",actual native library version number ""
I/chromium( 6944): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6944): Initializing chromium process, singleProcess=true
,W/art     ( 6944): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6944): ApplicationContext is null in ApplicationStatus
W/chromium( 6944): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6944): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6944): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6944): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6944): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6944): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6944): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6944): Remote Branch: 
I/Adreno-EGL( 6944): Local Patches: 
I/Adreno-EGL( 6944): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb4027080, uid 10079
,W/AudioManagerAndroid( 6944): Requires BLUETOOTH permission
I/NSApplication( 6944): Starting up...
I/ActivityManager(  947): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7010 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 6695:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10014/pid_6695/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7029 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 6724:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10081/pid_6724/cgroup.procs: No such file or directory
W/ResourcesManager( 7029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  947): Killing 6771:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10021/pid_6771/cgroup.procs: No such file or directory
,I/AppUp4:CustModeStarterReceiver( 6833): onReceive
I/AppUp4:CustModeStarterReceiver( 6833): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6833): Context : android.app.ReceiverRestrictedContext@361fdfaa
D/AppUp4:CustFacade( 6833): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6833): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6833): begin check event
I/AppUp4:CustModeStarterReceiver( 6833): Event For Nothing, skip.
I/ActivityManager(  947): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7055 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 6912): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7055): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 6912): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,W/System  ( 6912): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6912): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7055): Total System Memory = 906309632
,I/GalleryUtils( 7055): Application Heap = 96 MB
I/AppConfig( 7055): App Tier : NOT_DEF
D/SystemHelper( 7055): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  947): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7087 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7087): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7087): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7087): BUILD Country: EU
I/SystemConfig( 7087): BUILD Operator: OPEN
,I/ActivityManager(  947): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7112 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  947): Killing 6805:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_6805/cgroup.procs: No such file or directory
,I/SystemConfig( 7087): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7087): existFile = false
I/SystemConfig( 7087): canReadFile = false
I/SystemConfig( 7087): systemFeature RCS result false
D/SystemConfig( 7087): refreshRcsSupport() :false
I/LockScreenSettings( 7112): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7112): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7112): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7112): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7112): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7112): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  947): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7133 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7029): CheckpointMarkThreadRoots callback created = 0xb042d520
I/art     (  311): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 30.318ms
,I/art     ( 7029): CheckpointMarkThreadRoots callback created = 0xb042d4f0
I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.182ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 25.888ms
,I/ActivityManager(  947): Killing 6854:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 143 ms] updated apps [took 142 ms] 
,W/libprocessgroup(  947): failed to open /acct/uid_10038/pid_6854/cgroup.procs: No such file or directory
,I/art     (  947): Explicit concurrent mark sweep GC freed 22867(1388KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.360ms total 137.925ms
,D/Finsky  ( 7133): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7133): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7133): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7133): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7133): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@1284e712 on behalf of 7133
D/Ads     ( 7133): Skipping gmscore version check
D/Finsky  ( 7133): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7133): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7133): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5582): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7133): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  947): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7184 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 5582): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5582): updateResources: need to parse f{com.google.android.gms}
,I/MusicStore( 7184): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7184): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7184): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7184): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7184): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7184): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7184): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7184): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7184): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a8301e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7184): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7184): GMSCore installation verified
I/ConfigStore( 7184): Config Database version: 1
,I/MediaRouter( 7184): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7184): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7184): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7184): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  947): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7223 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7184): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7184): Using platform SSLCertificateSocketFactory,
,W/ResourcesManager( 7223): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7223): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7223): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  947): Killing 6889:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10051/pid_6889/cgroup.procs: No such file or directory
,I/LGEmail ( 7223): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 7184): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 7223): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7223): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  947): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7223): JNI_OnLoad()
I/HubEmail( 7223): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7223): registerNatives()
I/HubEmail( 7223): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7223): registerNativeMethods()
I/HubEmail( 7223): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7223): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  947): Killing 6944:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10079/pid_6944/cgroup.procs: No such file or directory
,W/Settings( 7223): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7254): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7254): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/Icing   ( 5582): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/ContextImpl( 7254): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7254): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6833): onReceive
I/AppUp4:CustModeStarterReceiver( 6833): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6833): Context : android.app.ReceiverRestrictedContext@361fdfaa
D/AppUp4:CustFacade( 6833): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6833): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6833): begin check event
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AppUp4:CustModeStarterReceiver( 6833): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/LgeMiscReceiver( 3150): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3150): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3150): networkInfo.isConnected() = true
D/LGDMClient( 7254): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/PhoneState( 3150): setPdpRejectCasuse : false
D/LGDMClient( 7254): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7254): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7254): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7288 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Icing   ( 5582): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  947): Killing 7010:com.android.chrome/u0a48 (adj 15): empty #11
W/ContextImpl( 7254): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
W/libprocessgroup(  947): failed to open /acct/uid_10048/pid_7010/cgroup.procs: No such file or directory
,E/LGDMClient( 7254): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7254): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7254): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7254): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7254): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  947): Killing 7055:com.android.gallery3d/u0a23 (adj 15): empty #11
D/PhoneMonitor( 7288): Register our PhoneStateListener
,W/libprocessgroup(  947): failed to open /acct/uid_10023/pid_7055/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7288): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7288): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  947): Killing 7087:com.android.contacts/u0a18 (adj 15): empty #11
D/PhoneMonitor( 7288): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7288): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7288): [parse] Load xml
V/TelephonyAutoProfiling( 7288): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7288): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7288): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  947): failed to open /acct/uid_10018/pid_7087/cgroup.procs: No such file or directory
V/DownloadManager( 3171): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3171): DownloadService onCreate
I/DownloadManager( 3171): in removeSpuriousFiles
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@2aea0ee3 on behalf of 3171
I/NotificationManager( 3171): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3171): in trimDatabase
V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@3cc3b0e0 on behalf of 3171
I/ActivityManager(  947): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7314 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3171): DownloadService onStartCommand
V/DownloadManager( 3171): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@30a4b63f on behalf of 3171
I/CheckinService( 5582): Checkin interval check for package: unspecified last checkin: 1454717595483 min interval config: 0 actual interval: 33919
I/CheckinService( 5582): Checking schedule, now: 1454717629414 next: 1454717625445
I/CheckinService( 5582): active receiver: enabled
,V/DownloadManager( 3171): DownloadService onDestroy
I/CheckinService( 5582): Preparing to send checkin request
,I/EventLogService( 5582): Accumulating logs since 1454717588005
,D/WeatherAncestor( 2722): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:13:49
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherAncestor( 2722): connectivity changed - connection : true
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2722): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:13:49
D/WeatherService( 2722): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager(  947): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinRequestBuilder( 5582): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  947): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7336 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 5582): Failed to find provider info for com.google.android.wearable.settings
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/art     ( 5432): Explicit concurrent mark sweep GC freed 1835(67KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 428us total 27.434ms
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7336): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7336):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7336):   adb logcat -s GAv4
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7336): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAv4    ( 7336): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7336): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  947): RTC_WAKEUP set : Alarm{2f9e73d3 type 0 when 1454717625445 com.google.android.gms} when 1454717625445
,V/AlarmManager(  947): RTC_WAKEUP set : Alarm{1f0c8609 type 0 when 1454717630090 com.android.vending} when 1454717630090
I/art     (  947): Explicit concurrent mark sweep GC freed 19235(904KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.308ms total 152.458ms
,I/ActivityManager(  947): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7367 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7367): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/Finsky  ( 7133): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
W/ResourcesManager( 7367): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7133): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/MultiDex( 7367): VM with version 2.1.0 has multidex support
I/MultiDex( 7367): install
I/MultiDex( 7367): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7367): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WebViewFactory( 7336): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ActivityThread( 7367): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7367): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38505b4f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7367): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7367): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7367): com.google.android.gms: cancel(39789) by com.google.android.gms
I/LibraryLoader( 7336): Time to load native libraries: 2 ms (timestamps 2676-2678)
,I/LibraryLoader( 7336): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7336): Binding Chromium to main looper Looper (main, tid 1) {30a4b63f}
I/LibraryLoader( 7336): Expected native library version number "",actual native library version number ""
I/chromium( 7336): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7336): Initializing chromium process, singleProcess=true
,W/art     ( 7336): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 7367): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7367): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/SysUtils( 7336): ApplicationContext is null in ApplicationStatus
W/chromium( 7336): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7336): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7336): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7336): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7336): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7336): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7336): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7336): Remote Branch: 
I/Adreno-EGL( 7336): Local Patches: 
I/Adreno-EGL( 7336): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb3a6aca0, uid 10079
,W/AudioManagerAndroid( 7336): Requires BLUETOOTH permission
I/NSApplication( 7336): Starting up...
D/NativeLibraryUtils( 7367): Install completed successfully. count=14 extracted=0
I/ActivityManager(  947): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7419 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 7112:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10069/pid_7112/cgroup.procs: No such file or directory
,D/WVCdm   (  281): Instantiating CDM.
I/WVCdm   (  281): CdmEngine::OpenSession
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
I/ActivityManager(  947): Killing 7184:com.google.android.music:main/u0a81 (adj 15): empty #11
D/WVCdm   (  281): PrepareKeyRequest: nonce=1562476677
W/libprocessgroup(  947): failed to open /acct/uid_10081/pid_7184/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7440 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     ( 7367): CheckpointMarkThreadRoots callback created = 0xb04d4eb0
I/art     ( 7367): CheckpointMarkThreadRoots callback created = 0xb04d4ea0
,W/ResourcesManager( 7440): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  947): Message: 20
,D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc21170:true
D/BluetoothAdapterService(164635409)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f9796f
D/BluetoothAdapterService(164635409)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f9796f
I/ActivityManager(  947): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7458 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7440): Create singleton instance
,I/AudioManager( 7440): getMode name:com.lge.qremote
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  947): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7476 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 26.915ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.981ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.585ms
,I/ActivityManager(  947): Killing 7223:com.lge.email/u0a21 (adj 15): empty #11
,D/UEI.SmartControl( 7458): Quickset Services start...
,I/UEI.SmartControl( 7458): Manufacture = LGE
D/UEI.SmartControl( 7458): File observer start...
E/UEI.SmartControl( 7458): IR Port is disabled: false
D/UEI.SmartControl( 7458): Starting file observer...
D/UEI.SmartControl( 7458): Extracting JNI libs...
D/UEI.SmartControl( 7458): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  947): failed to open /acct/uid_10021/pid_7223/cgroup.procs: No such file or directory
,W/ResourcesManager( 7476): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/dex2oat ( 7493): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/UEI.SmartControl( 7458): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7458): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7458): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/CalendarProvider2( 7476): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@29fce420
D/CalendarProvider2( 7476): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7476): Created com.android.providers.calendar.CalendarAlarmManager@735f295(com.android.providers.calendar.CalendarProvider2@29fce420)
D/CalendarProviderBroadcastReceiver( 7476): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7476): [IntentService] WakeLock acquire, start IntentSerivce
,I/UEI.SmartControl( 7458): --- Selecting new region: 2
I/UEI.SmartControl( 7458): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7458): Platform has CIR...
D/UEI.SmartControl( 7458): NO CIR support, need to check package...
I/UEI.SmartControl( 7458): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7458): QS Service created
D/CalendarProvider2( 7476): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7476): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7476): [getOrCreateCalendarAlarmManager]
E/UEI.SmartControl( 7458): QS start get config
,I/ActivityManager(  947): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7502 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/dex2oat ( 7493): dex2oat took 132.590ms (threads: 4)
,I/Adreno-EGL( 7367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7367): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7367): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7367): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7367): Remote Branch: 
I/Adreno-EGL( 7367): Local Patches: 
I/Adreno-EGL( 7367): Reconstruct Branch: 
,D/CalendarProvider2( 7476): [IntentService] Release Lock
D/CalendarProvider2( 7476): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  947): Killing 6833:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7458): Loading JNI Libs...
D/UEI.SmartControl( 7458):  configuring local db...
,W/libprocessgroup(  947): failed to open /acct/uid_10011/pid_6833/cgroup.procs: No such file or directory
I/WVCdm   (  281): CdmEngine::OpenSession
,D/UEI.SmartControl( 7458):  ---- Has DB8: true
,D/UEI.SmartControl( 7458): QS start statue = true Error code = 0
D/UEI.SmartControl( 7458): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7458): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7458): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7458): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7458): IrrcClient ++ 
D/irrcClient( 7458): getIrrcService ++ 
,D/irrcClient( 7458): getIrrcService -- 
D/irrcClient( 7458): IrrcClient -- 
W/irrc_jni( 7458): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7458): Services init done
I/UEI.SmartControl( 7458): Device manager: loading config....
D/UEI.SmartControl( 7458): Config is loaded...
,D/UEI.SmartControl( 7458):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7458): Notify AllClients services are ready: 0
I/ActivityManager(  947): Process com.google.android.talk (pid 6912) has died
W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/UEI.SmartControl( 7458): QS Service init finished
D/UEI.SmartControl( 7458): QS Service version name: 0.1.73
D/UEI.SmartControl( 7458): QS Service version code: 1073
D/UEI.SmartControl( 7458): Service requested: Control
D/UEI.SmartControl( 7458): -----IControl: 11
D/UEI.SmartControl( 7458): Caller: com.lge.qremote
D/UEI.SmartControl( 7458): ------------ IControl registerCallback...
I/UEI.SmartControl( 7458): Registering callback...
D/UEI.SmartControl( 7458): -----IControl: 19
D/UEI.SmartControl( 7458): Internal service binding...
,D/UEI.SmartControl( 7458): Caller: com.lge.qremote
I/UEI.SmartControl( 7458): Registering Services Ready callback...
I/UEI.SmartControl( 7458): Notify client services are ready...
D/UEI.SmartControl( 7458): -----IControl: 8
D/UEI.SmartControl( 7458): Caller: com.lge.qremote
I/ActivityManager(  947): Killing 7254:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_1000/pid_7254/cgroup.procs: No such file or directory
,I/Gmail   ( 7502): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7502): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7502): Error finding the version of the Email provider.....
E/Gmail   ( 7502): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7502): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7502): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7502): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7502): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7502): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7502): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7502): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7502): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7502): getAccountsCursor
I/ActivityManager(  947): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7541 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  947): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  947): Killing 7288:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/Gmail   ( 7502): Observing account changes for notifications
,W/libprocessgroup(  947): failed to open /acct/uid_10038/pid_7288/cgroup.procs: No such file or directory
,W/ActivityManager(  947): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7541): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 7502): notifyAccountChanged
,I/Gmail   ( 7502): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7502): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7502): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7502): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7502): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/WVCdm   (  281): CdmEngine::CloseSession
,I/Babel_SMS( 7541): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7541): MmsConfig.loadMmsSettings
I/Babel_SMS( 7541): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7541): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7541): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7541): MmsConfig.loadFromResources
E/Babel_SMS( 7541): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7541): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=3136539546
,D/SensorManager( 7541): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7541): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7541): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7541): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7541): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7541): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7541): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7541): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7541): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7541): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7541): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7541): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7541): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7541): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7541): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7541): found sensor: Motion Accel, handle=46
W/Settings( 7541): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7541): startup - clean
I/Babel   ( 7541): deleted: false for 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 7541): CheckpointMarkThreadRoots callback created = 0xb042d920
,I/Gmail   ( 7502): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 7541): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/AudioManager( 7440): getMode name:com.lge.qremote
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/LocationInitializer( 5582): Restart initialization of location
W/AudioCapabilities( 7541): Unsupported mime audio/x-lg-flac
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/AudioCapabilities( 7541): Unsupported mime audio/adpcm
E/MDM     ( 1733): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/AudioCapabilities( 7541): Unsupported mime audio/g726
,W/AudioCapabilities( 7541): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7541): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7541): Unsupported mime video/mjpg
D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 115387748815; DSPS: 3879410; Offset : -3009791983
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/VideoCapabilities( 7541): Unsupported mime video/theora
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/Finsky  ( 7133): [905] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/AudioCapabilities( 7541): Unsupported mime audio/evrc
W/AudioCapabilities( 7541): Unsupported mime audio/qcelp
W/VideoCapabilities( 7541): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7541): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7541): Unsupported mime audio/qcelp
W/AudioCapabilities( 7541): Unsupported mime audio/evrc
W/VideoCapabilities( 7541): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7541): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7541): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7541): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7541): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7541): Unrecognized profile 2130706433 for video/avc
,I/art     (  947): Explicit concurrent mark sweep GC freed 16278(730KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.843ms total 160.558ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/vclib   ( 7541): onServiceConnected
,W/Babel   ( 7541): Attempted to change video mute state without an active call.
I/NotificationManager( 7541): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7586 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/NotificationManager(  947): android: cancelAsUser(2) by android
,I/MusicWidget( 2607): mDelayedStopHandler : unbind
,D/libc-netbsd( 7133): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7133): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7133): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7133): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 7586): Register our PhoneStateListener
I/MusicBrowser( 2739): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2739): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2739): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2739): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2739): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/ActivityManager(  947): Killing 7314:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 7586): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7586): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7586): [parse] Load xml
V/TelephonyAutoProfiling( 7586): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7586): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7586): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 7133): propertyValue:false
,W/libprocessgroup(  947): failed to open /acct/uid_10051/pid_7314/cgroup.procs: No such file or directory
,I/MusicBrowser( 2739): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5582): Checkin interval check for package: unspecified last checkin: 1454717595483 min interval config: 0 actual interval: 38239
,I/MediaFocusControl(  947):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@16ce3d8bcom.lge.music.MediaPlaybackService$6@3112be68
D/MusicBrowser( 2739): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/CheckinService( 5582): Checkin interval check for package: unspecified last checkin: 1454717595483 min interval config: 0 actual interval: 38252
,I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@8744c76
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
E/MDM     ( 1733): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5582): Restart initialization of location
I/MusicBrowser( 2739): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2739): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/MusicBrowser( 2739): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2739): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2739): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2739): [MediaPlaybackService.java:6706:stop()] oooooo 
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/MediaPlayer[Native]( 2739): reset
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/AudioManager( 7440): getMode name:com.lge.qremote
V/MediaPlayer[Native]( 2739): setListener
V/MediaPlayer[Native]( 2739): disconnect
V/MediaPlayer[Native]( 2739): destructor
,V/AudioFlinger(  281): releasing 19 from 2739 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
I/AudioManager( 7440): getMode name:com.lge.qremote
V/MediaPlayer[Native]( 2739): disconnect
D/MusicBrowser( 2739): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
W/ContextImpl( 3562): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/SmartShareClient( 2739): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2739): [SmartShareManagerClient] smartshare client enabled
I/AudioManager( 7440): getMode name:com.lge.qremote
I/MusicBrowser( 2739): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2739): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2739): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2739): [SmartShareManagerClient] unregisterListener: 124711553
W/SmartShareClient( 2739): [SmartShareManagerClient] unregisterListener invalid listener: 124711553
I/SmartShareClient( 2739): [SmartShareManagerClient] terminate service: 2739/MediaPlaybackService/773595724
,E/HomeCloudIF( 2739): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2739): [SmartShareManagerClient] unbindService context:android.app.Application@8e6bf26
V/CloudHub( 2739): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2739): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2739): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2739): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2739): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/AudioManager( 7440): getMode name:com.lge.qremote
I/AudioManager( 7440): getMode name:com.lge.qremote
I/CloudHub( 2739): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29979
I/AudioManager( 7440): getMode name:com.lge.qremote
,I/ActivityManager(  947): Killing 7336:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10079/pid_7336/cgroup.procs: No such file or directory
,I/ActivityManager(  947): Killing 7419:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10048/pid_7419/cgroup.procs: No such file or directory
,I/WVCdm   (  281): CdmEngine::CloseSession
I/WVCdm   (  281): L3 Terminate.
,I/Adreno-EGL( 7367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7367): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7367): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7367): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7367): Remote Branch: 
I/Adreno-EGL( 7367): Local Patches: 
I/Adreno-EGL( 7367): Reconstruct Branch: 
I/Adreno-EGL( 7367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7367): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7367): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7367): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7367): Remote Branch: 
I/Adreno-EGL( 7367): Local Patches: 
I/Adreno-EGL( 7367): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5582): Classify the device as Phone.
,D/libc-netbsd( 5582): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5582): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5582): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5582): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5582): propertyValue:false
D/libc-netbsd( 5582): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5582): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5582): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5582): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5582): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5582): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5582): Sending checkin request (9815 bytes)
,I/CheckinRequestBuilder( 5582): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5582): Failed to find provider info for com.google.android.wearable.settings
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 5582): Classify the device as Phone.
,I/CheckinTask( 5582): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5582): Checking schedule, now: 1454717636517 next: 1455244885513
I/CheckinService( 5582): active receiver: disabled
,I/CheckinService( 5582): Checking schedule, now: 1454717636547 next: 1455244885513
,I/CheckinService( 5582): active receiver: disabled
,D/CheckinService( 5582): Recording last checkin time for package unspecified as 1454717636555
V/SetupWizard( 7586): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7458): Internal timer expired: 1
,I/GAV2    ( 7502): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  947): Killing 7476:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  947): Killing 7029:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  947): failed to open /acct/uid_10014/pid_7476/cgroup.procs: No such file or directory
,W/libprocessgroup(  947): failed to open /acct/uid_10086/pid_7029/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  947): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
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
D/administrator(  947): Handling package changes for user 0
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  947): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7688 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager( 7541): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,I/NotificationManager( 7541): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7541): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7541): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7688): onCreate
W/AppUp4:DB( 7688):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7688):  setFingerPrint start
I/AppUp4:DB( 7688):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7688):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7688):  SDK version = 0
I/AppUp4:DB( 7688):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7688): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7688): onReceive
,I/AppUp4:CustModeStarterReceiver( 7688): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7688): Context : android.app.ReceiverRestrictedContext@31f8f27f
D/AppUp4:CustFacade( 7688): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7688): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7688): begin check event
I/AppUp4:CustModeStarterReceiver( 7688): Event For Nothing, skip.
I/NotificationService(  947): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  947): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  947): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/System  ( 7541): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7541): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  947): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7709 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  947): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  947): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  947): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@e531bd
,W/ResourcesManager( 7709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7709): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager(  947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx(  947): acquireWakeLockInternal: lock=528857585, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=947
,D/WeatherService( 2722): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:14:0
,D/WeatherService( 2722): 2 : TimeTick Intent And Screen On
D/WeatherService( 2722): 2 : SDK version : 21
W/ActivityManager(  947): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2722): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherService( 2722): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2722): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2722): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2722): 2 : Fixed theme : optimus
D/WeatherReflect( 2722): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
D/lim     ( 2722): 2 : time = 01:14
,I/WeatherReflect( 2722): Model Name : LG-D722
D/WeatherTheme( 2722): 2 : Different view - status_min_formatted : 13 != 14
D/WeatherTheme( 2722): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2722): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2722): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
W/ResourceType(  947): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/Weather4x2_optimus( 2722): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2722): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2722): forecast size is 0
,D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2722): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2722): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2722): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2722): url is : null
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2722): 2 : update view, appWidgetId: 2
D/WeatherService( 2722): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:14:0
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  947): Process com.android.vending (pid 7133) has died
,D/PowerManagerServiceEx(  947): releaseWakeLockInternal: lock=528857585 [*alarm*], flags=0x0
,I/AppConfig( 7709): Total System Memory = 906309632
I/GalleryUtils( 7709): Application Heap = 96 MB
,I/AppConfig( 7709): App Tier : NOT_DEF
D/SystemHelper( 7709): region [EU], country [EU], operator [OPEN], sub-operator []
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  947): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7730 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  947): Process com.google.android.gm (pid 7502) has died
,D/LocationProviderProxy(  947): applying state to connected service
,W/ResourcesManager( 7730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7730): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7730): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7730): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7730): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/AudioFlinger(  281): 2739 died, releasing its sessions
,V/AudioFlinger(  281):  pid 1750 @ 0
V/AudioFlinger(  281):  pid 3150 @ 1
V/AudioFlinger(  281):  pid 3150 @ 2
,I/ActivityManager(  947): Process com.lge.music (pid 2739) has died
,I/SystemConfig( 7730): BUILD Country: EU
I/SystemConfig( 7730): BUILD Operator: OPEN
,I/ActivityManager(  947): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7752 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/SystemConfig( 7730): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7730): existFile = false
I/SystemConfig( 7730): canReadFile = false
I/SystemConfig( 7730): systemFeature RCS result false
D/SystemConfig( 7730): refreshRcsSupport() :false
,I/LockScreenSettings( 7752): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7752): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7752): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7752): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7752): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7752): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7772 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7772): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  947): Process com.google.android.gms.unstable (pid 7367) has died
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  947): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7797 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
,D/Finsky  ( 7797): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  297): Sensor:pa_therm0:33000 mC
,I/art     (  947): Explicit concurrent mark sweep GC freed 28049(1427KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.110ms total 156.447ms
,D/Finsky  ( 7797): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7797): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7797): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7797): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3171): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3171): created cursor android.database.sqlite.SQLiteCursor@2eeabc55 on behalf of 7797
D/Finsky  ( 7797): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 7797): Skipping gmscore version check
,D/Finsky  ( 7797): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7797): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5582): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5582): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7797): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5582): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 5582): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5582): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  947): Killing 7458:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7440): android.os.DeadObjectException
,W/System.err( 7440): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7440): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7440): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7440): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7440): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7440): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7440): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7440): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7440): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7440): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7440): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7440): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7440): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7440): android.os.DeadObjectException
W/System.err( 7440): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7440): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7440): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7440): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7440): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7440): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7440): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7440): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7440): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7440): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7440): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7440): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7440): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  947): failed to open /acct/uid_10089/pid_7458/cgroup.procs: No such file or directory
W/ActivityManager(  947): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  947): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7871 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7871): Quickset Services start...
,I/UEI.SmartControl( 7871): Manufacture = LGE
D/UEI.SmartControl( 7871): File observer start...
E/UEI.SmartControl( 7871): IR Port is disabled: false
D/UEI.SmartControl( 7871): Starting file observer...
D/UEI.SmartControl( 7871): Extracting JNI libs...
D/UEI.SmartControl( 7871): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7871): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7871): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7871): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7871): --- Selecting new region: 2
,I/UEI.SmartControl( 7871): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7871): Platform has CIR...
D/UEI.SmartControl( 7871): NO CIR support, need to check package...
I/UEI.SmartControl( 7871): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7871): QS Service created
E/UEI.SmartControl( 7871): QS start get config
,D/UEI.SmartControl( 7871): Loading JNI Libs...
,D/UEI.SmartControl( 7871):  configuring local db...
D/UEI.SmartControl( 7871):  ---- Has DB8: true
,D/UEI.SmartControl( 7871): QS start statue = true Error code = 0
D/UEI.SmartControl( 7871): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7871): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7871): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7871): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7871): IrrcClient ++ 
D/irrcClient( 7871): getIrrcService ++ 
D/irrcClient( 7871): getIrrcService -- 
D/irrcClient( 7871): IrrcClient -- 
W/irrc_jni( 7871): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7871): Services init done
,I/UEI.SmartControl( 7871): Device manager: loading config....
D/UEI.SmartControl( 7871): QS Service init finished
D/UEI.SmartControl( 7871): QS Service version name: 0.1.73
D/UEI.SmartControl( 7871): Config is loaded...
D/UEI.SmartControl( 7871): QS Service version code: 1073
D/UEI.SmartControl( 7871): Service requested: Control
D/UEI.SmartControl( 7871): -----IControl: 11
,D/UEI.SmartControl( 7871): Caller: com.lge.qremote
I/ActivityManager(  947): Killing 7440:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7871): ------------ IControl registerCallback...
I/UEI.SmartControl( 7871): Registering callback...
W/libprocessgroup(  947): failed to open /acct/uid_10106/pid_7440/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7871): Internal service binding...
,D/UEI.SmartControl( 7871):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7871): Notify AllClients services are ready: 0
,W/SQLiteConnectionPool( 5582): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  487): init target 500000
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ActivityManager(  947): Killing 7586:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  947): failed to open /acct/uid_10038/pid_7586/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  947): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7871): Internal timer expired: 1
,D/UEI.SmartControl( 7871): Service.onUnbind: IControl
D/UEI.SmartControl( 7871): Service.onDestroy
W/System.err( 7871): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@9d02311
W/System.err( 7871): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7871): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7871): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7871): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7871): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7871): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7871): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7871): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7871): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7871): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7871): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7871): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7871): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7871): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7871): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7871): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@9d02311
D/UEI.SmartControl( 7871): Shutdown IRRCPlayer... 
,W/irrc_jni( 7871): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7871): ~IrrcClient ++ 
D/irrcClient( 7871): ~IrrcClient -- 
W/irrc_jni( 7871): IRRCPlayer_nativeFinalize -- 
,D/UEI.SmartControl( 7871): Blaster closed
D/UEI.SmartControl( 7871): Blaster closed
D/UEI.SmartControl( 7871): Shut down QS...
D/UEI.SmartControl( 7871): Stopped file observer...
I/UEI.SmartControl( 7871): QS lib stop result = true
D/UEI.SmartControl( 7871): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 135388502088; DSPS: 4534795; Offset : -3009801468
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{3e82af27 type 2 when 146721 com.google.android.gms} when 146721
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1454717664746 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 2767 seconds from now (1454717665181)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 47147(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 13MB/22MB, paused 2.618ms total 136.850ms
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  947): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/LocationManagerService(  947): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  947): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  947): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PowerManagerService(  947): ALS enabled for SRE
,D/PowerManagerServiceEx(  947): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29571 ms ago)
D/qdlights(  947): set_light_backlight: 254
,D/qdlights(  947): set_light_backlight: 251
D/qdlights(  947): set_light_backlight: 247
,D/qdlights(  947): set_light_backlight: 244
,D/qdlights(  947): set_light_backlight: 241
,D/qdlights(  947): set_light_backlight: 237
,D/qdlights(  947): set_light_backlight: 234
,D/qdlights(  947): set_light_backlight: 231
,D/qdlights(  947): set_light_backlight: 227
,D/qdlights(  947): set_light_backlight: 224
,D/qdlights(  947): set_light_backlight: 221
,D/qdlights(  947): set_light_backlight: 217
,D/qdlights(  947): set_light_backlight: 214
,D/qdlights(  947): set_light_backlight: 211
,D/qdlights(  947): set_light_backlight: 207
,D/qdlights(  947): set_light_backlight: 204
,D/qdlights(  947): set_light_backlight: 201
,D/qdlights(  947): set_light_backlight: 197
,D/qdlights(  947): set_light_backlight: 194
,D/qdlights(  947): set_light_backlight: 191
,D/qdlights(  947): set_light_backlight: 187
,D/qdlights(  947): set_light_backlight: 184
,D/qdlights(  947): set_light_backlight: 181
,D/qdlights(  947): set_light_backlight: 177
,D/qdlights(  947): set_light_backlight: 174
,D/qdlights(  947): set_light_backlight: 171
,D/qdlights(  947): set_light_backlight: 167
,D/qdlights(  947): set_light_backlight: 164
,D/qdlights(  947): set_light_backlight: 161
,D/qdlights(  947): set_light_backlight: 157
,D/qdlights(  947): set_light_backlight: 154
,D/qdlights(  947): set_light_backlight: 151
,D/qdlights(  947): set_light_backlight: 147
,D/qdlights(  947): set_light_backlight: 144
,D/qdlights(  947): set_light_backlight: 141
,D/qdlights(  947): set_light_backlight: 137
,D/qdlights(  947): set_light_backlight: 134
,D/qdlights(  947): set_light_backlight: 131
,D/qdlights(  947): set_light_backlight: 127
,D/qdlights(  947): set_light_backlight: 124
,D/qdlights(  947): set_light_backlight: 121
,D/qdlights(  947): set_light_backlight: 117
,D/qdlights(  947): set_light_backlight: 114
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  947): set_light_backlight: 111
,D/qdlights(  947): set_light_backlight: 107
,D/qdlights(  947): set_light_backlight: 104
,D/qdlights(  947): set_light_backlight: 101
,D/qdlights(  947): set_light_backlight: 97
,D/qdlights(  947): set_light_backlight: 94
,D/qdlights(  947): set_light_backlight: 91
,D/qdlights(  947): set_light_backlight: 87
,D/qdlights(  947): set_light_backlight: 84
,D/qdlights(  947): set_light_backlight: 81
,D/qdlights(  947): set_light_backlight: 77
,D/qdlights(  947): set_light_backlight: 74
,D/qdlights(  947): set_light_backlight: 71
,D/qdlights(  947): set_light_backlight: 67
,D/qdlights(  947): set_light_backlight: 64
,D/qdlights(  947): set_light_backlight: 61
,D/qdlights(  947): set_light_backlight: 57
,D/qdlights(  947): set_light_backlight: 54
,D/qdlights(  947): set_light_backlight: 51
,D/qdlights(  947): set_light_backlight: 47
,D/qdlights(  947): set_light_backlight: 44
,D/qdlights(  947): set_light_backlight: 41
,D/qdlights(  947): set_light_backlight: 37
,D/qdlights(  947): set_light_backlight: 34
,D/qdlights(  947): set_light_backlight: 31
,D/qdlights(  947): set_light_backlight: 27
,D/qdlights(  947): set_light_backlight: 24
,D/qdlights(  947): set_light_backlight: 21
,D/qdlights(  947): set_light_backlight: 17
,D/qdlights(  947): set_light_backlight: 14
,D/qdlights(  947): set_light_backlight: 11
,D/qdlights(  947): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 155389169633; DSPS: 5190177; Offset : -3009804970
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/PowerManagerService(  947): ALS enabled for SRE
D/PowerManagerServiceEx(  947): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36555 ms ago)
I/PowerManagerService(  947): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  947): ALS enabled for SRE
D/PowerManagerServiceEx(  947): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36571 ms ago)
,W/ContextImpl(  947): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  947): Sleeping (uid 1000)...
D/LPWGController(  947): [updateScreenState] screen on = false
,D/LPWGController(  947): disable proximity sensor
D/LPWGController(  947): enable proximity sensor
,I/SensorManager(  947): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@38328b0f] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  947): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  947): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  947): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  947): activate: handle is 48, enable
,V/sensors_hal_Ctx(  947): activate sensors is 1400000000000
D/sensors_hal_Thresh(  947): enable: handle=48
I/sensors_hal_SAM(  947): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  947): waitForResponse: timeout=1000
V/sensors_hal_SAM(  947): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  947): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  947): enable: Received response: 0
D/PowerManagerServiceEx(  947): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36634 ms ago)
I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  947): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  947): Build Date: 03/02/15 Mon
I/Adreno-EGL(  947): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  947): Remote Branch: 
I/Adreno-EGL(  947): Local Patches: 
I/Adreno-EGL(  947): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1029 us)
,I/Sensors (  428): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  947): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  947): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  947): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  947): processInd: handle 48, count=1
V/sensors_hal_Thresh(  947): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  947): processInd : proximity state changed - FAR
,D/sensors_hal_Ctx(  947): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  947): poll: count: 256
I/sensors_hal_Ctx(  947): poll: released wakelock sensor_ind
D/sensors_hal_Util(  947): waitForResponse: timeout=0
D/LPWGController(  947): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  947): current mode = 1  value = 1 1
I/LPWGController(  947): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  947): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  947): set_light_backlight: 0
,I/SensorManager(  947): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  947): activate: handle is 46, disable
V/sensors_hal_Ctx(  947): activate sensors is 1000000000000
D/sensors_hal_LP2(  947): enable: handle=46
D/sensors_hal_LP2(  947): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  947): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  947): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  947): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  947): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  947): Display changed displayId=0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  947): Excessive delay in setPowerMode(): 250ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  947): Got set_interactive hint
,D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1374): notifyScreenOffLocked
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/WifiServerServiceExt(  947): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  947): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 947
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
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
D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/GpsLocationProvider(  947): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1804): lockStatus = 0
D/LEDService( 1804): stopPatternFlashing()
D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
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
,D/SplitWindow(  947): check instance of lgWin Window{27327d7a u0 SearchPanel}
,D/Ulp_jni (  947): JNI:system_update. Event-0
,D/InputDispatcher(  947): Window went away: Window{e7074cb u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,I/Sensors (  428): sns_pwr.c(301):releasing wakelock
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2722): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:14:36
,D/WeatherService( 2722): 2 : ACTION screen on
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2722): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:14:36
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): ACTION_SCREEN_ON
,D/AppCleanupService( 4036): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 947
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
,V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/WifiController(  947): CMD_SCREEN_OFF 
D/WifiController(  947): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  947): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/VolumeVibrator( 1804): clear
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2722): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:14:36
D/WeatherService( 2722): 2 : ACTION screen off
D/WeatherService( 2722): 2 : TimeTick Receiver Unregister
D/WeatherService( 2722): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:14:36
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  947): ACTION_SCREEN_OFF
D/AppCleanupService( 4036): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4036): AppUsageStatsSaveTask
,E/NxpNfcJni( 1787): getReconnectState = 0x0
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
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{1916c92b type 2 when 162548 com.android.systemui} when 162548
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1750): getCallState : 0
D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 175389859469; DSPS: 5845559; Offset : -3009786781
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/PowerManagerServiceEx(  947): acquireWakeLockInternal: lock=528857585, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=947
,V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{2240f188 type 2 when 182999 android} when 182999
D/PowerManagerServiceEx(  947): releaseWakeLockInternal: lock=528857585 [*alarm*], flags=0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  947): battery changed pluggedType: 2
,V/AlarmManager(  947): ELAPSED_WAKEUP set : Alarm{366e7721 type 2 when 188519 com.google.android.gms} when 188519
,I/ActivityManager(  947): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7998 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 10.715ms total 78.265ms
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 393us total 31.489ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 395us total 34.793ms
,I/DigitalAppWidgetProvider( 7998): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7998): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@31f8f27f
I/ActivityManager(  947): Killing 7541:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  947): failed to open /acct/uid_10061/pid_7541/cgroup.procs: No such file or directory
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 195390913472; DSPS: 6500954; Offset : -3009800738
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 215391676642; DSPS: 7156339; Offset : -3009800638
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 235392436582; DSPS: 7811724; Offset : -3009803584
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
W/Settings(  947): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  947): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  947): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 255393114647; DSPS: 8467106; Offset : -3009798859
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  947): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  947): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  947): tsOffsetIs: Apps: 275393879796; DSPS: 9122491; Offset : -3009796729
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5358): --= Surplus to requirements =--
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ****TEST TOOK:  ms ****
I/jxcore-log( 5358): 
I/jxcore-log( 5358): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5358): 
,D/AndroidRuntime( 8059): 
D/AndroidRuntime( 8059): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8059): CheckJNI is OFF
,D/AndroidRuntime( 8059): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  947): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  947): Killing 5358:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  947): WIN DEATH: Window{2d61ea32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  947): Focus left window: Window{2d61ea32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  947): Window went away: Window{2d61ea32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  947): Skipping PackageSetting{3778a2df com.example.hello/10317} due to missing metadata
,I/ActivityManager(  947):   Force finishing activity ActivityRecord{1828a2a5 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  947): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
,W/ActivityManager(  947): Spurious death for ProcessRecord{19daf746 5358:com.test.thalitest/u0a316}, curProc for 5358: null
I/ActivityManager(  947): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  947):   Force finishing activity ActivityRecord{1828a2a5 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  947): Duplicate finish request for ActivityRecord{1828a2a5 u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/InputReader(  947): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1943): Explicit concurrent mark sweep GC freed 13346(776KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 3.752ms total 97.908ms
W/System.err( 3562): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/art     ( 5582): Explicit concurrent mark sweep GC freed 6643(350KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 837us total 118.472ms
,W/System.err( 3562): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3562): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3562): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3562): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3562): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3562): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3562): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3562): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3562): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3562): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3562): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  947): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8090 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
,D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
,I/SystemUI[Framework](  947): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  947): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  947): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  947): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  947): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2f53974a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  947): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  947): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  947): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  947): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  947): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  947): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2f53974a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  947): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1374): handleShortcutListChanged...
D/InputDispatcher(  947): Focus entered window: Window{1891af5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourcesManager( 8090): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/art     (  947): Explicit concurrent mark sweep GC freed 53309(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 12.827ms total 291.830ms
W/ResourcesManager( 8090): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     (  947): WaitForGcToComplete blocked for 292.085ms for cause Explicit
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
D/administrator(  947): Handling package changes for user 0
,I/LGEmail ( 8090): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8090): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  947): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  947): Got RemoteException sending setActive(false) notification to pid 5358 uid 10316
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  947): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  947): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
D/JobSchedulerService(  947): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  947): Timeline: Activity_windows_visible id: ActivityRecord{5aa8204 u0 com.lge.launcher2/.Launcher t221} time:293829
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/TaskPersister(  947): removeObsoleteFile: deleting file=222_task.xml
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1604): Unable to connect to the editor to retrieve text... will retry later
,I/art     (  947): Explicit concurrent mark sweep GC freed 9078(550KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 9.789ms total 341.615ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 8090): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/AppUp4:PreloadHelper( 7688): added Exclude : com.test.thalitest
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/AndroidRuntime( 8059): Shutting down VM
,I/ActivityManager(  947): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8117 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  947): Killing 7709:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager(  947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  947): failed to open /acct/uid_10023/pid_7709/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourceType(  947): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 8117): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8117): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8117): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8117): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 8117): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/SharedPreferencesImpl( 1877): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
