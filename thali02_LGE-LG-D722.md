#### Test 58752353dc32d9f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/AppUp4:DB( 5368):  setFingerPrint start
I/AppUp4:DB( 5368):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5368):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5368):  SDK version = 0
I/AppUp4:DB( 5368):  beforefinger == newfinger no write in DB
I/CheckinRequestBuilder( 4266): Classify the device as Phone.
D/AppUp4:AppBoxApplication( 5368): AppBoxApplication onCreate()
I/CheckinTask( 4266): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4266): Checking schedule, now: 1455113483265 next: 1455640732259
I/CheckinService( 4266): active receiver: disabled
D/AppUp4:PreloadHelper( 5368): removed from Exclude : com.test.thalitest : 1
--------- beginning of system
I/ActivityManager(  953): Killing 5069:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/CheckinService( 4266): Recording last checkin time for package unspecified as 1455113483304
W/libprocessgroup(  953): failed to open /acct/uid_10086/pid_5069/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Killing 5160:com.lge.sync/1000 (adj 15): empty #11
I/ActivityManager(  953): Killing 5135:com.android.settings/1000 (adj 15): empty #12
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_5160/cgroup.procs: No such file or directory
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_5135/cgroup.procs: No such file or directory
I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5395 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 334us total 24.883ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 342us total 24.049ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.732ms
W/ResourcesManager( 5395): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5395): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5395): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5395): Total System Memory = 906309632
I/GalleryUtils( 5395): Application Heap = 96 MB
I/AppConfig( 5395): App Tier : NOT_DEF
D/SystemHelper( 5395): region [EU], country [EU], operator [OPEN], sub-operator []
D/AndroidRuntime( 5393): 
D/AndroidRuntime( 5393): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5393): CheckJNI is OFF
I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5414 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  953): Killing 3964:com.google.process.gapps/u0a6 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_3964/cgroup.procs: No such file or directory
W/ResourcesManager( 5414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5414): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5414): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5414): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5414): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5414): BUILD Country: EU
I/SystemConfig( 5414): BUILD Operator: OPEN
D/AndroidRuntime( 5393): Calling main entry com.android.commands.am.Am
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  953): setTaskToReturnTo : TaskRecord{36e99430 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  953): setTaskToReturnTo : TaskRecord{36e99430 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  953): AppWindowTokenEx init.. 
D/ContextHelper(  953): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  953): Focus left window: Window{2a46394a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5393): Shutting down VM
I/PhoneWindow(  953): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  953): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  953): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  953): check instance of lgWin Window{cb07c7 u0 Starting com.test.thalitest}
I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5448 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 4948:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
I/ActivityManager(  953): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5470 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
,I/SystemConfig( 5414): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5414): existFile = false
I/SystemConfig( 5414): canReadFile = false
I/SystemConfig( 5414): systemFeature RCS result false
D/SystemConfig( 5414): refreshRcsSupport() :false
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_4948/cgroup.procs: No such file or directory
W/ActivityManager(  953): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{3dbb21f4 type 2 when 80328 android} when 80328
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  953): Starting window displayed
I/LockScreenSettings( 5448): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/WindowManager(  953): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  953): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  953): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  953): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  953): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27584db4,  pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1374): notify navigation bar color(0xfff5f5f5)
I/SystemUI[Framework](  953): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1946): Closing mic
I/MicrophoneInputStream( 1946): mic_close com.google.android.apps.gsa.speech.audio.u@3dc41c83
V/AudioRecord( 1946): stop()
D/AudioRecord( 1946): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
I/LockScreenSettings( 5448): New app installed broadcast received ..
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
I/LockScreenSettings( 5448): Number of installed packages  1
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb386f000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e6a0) usecase(7: audio-record)
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
I/ActivityManager(  953): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5495 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/ActivityManager(  953): Killing 4266:com.google.android.gms/u0a6 (adj 15): empty #11
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb386f000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1946): stop()
V/AudioRecord( 1946): stop()
V/AudioRecord( 1946): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): releasing 16 from 1946 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1752): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb386f000 exiting
V/AudioSystem(  953): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e6a0)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e6a0) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioFlinger(  282): removeClient_l() pid 1946, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 2015): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3192): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1946): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1946): Stopping hotword detection.
I/HotwordRecognitionRnr( 1946): Hotword detection finished
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_4266/cgroup.procs: No such file or directory
D/ContextHelper( 5470): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/WebViewFactory( 5470): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/EulaProviderUpdateObserver( 5495): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5495): uri : package:com.test.thalitest
D/[BNRAppListMgrReceiver]( 5205): android.intent.action.PACKAGE_ADDED : com.test.thalitest
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LibraryLoader( 5470): Time to load native libraries: 2 ms (timestamps 697-699)
I/LibraryLoader( 5470): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5470): Binding Chromium to main looper Looper (main, tid 1) {3da4b068}
I/LibraryLoader( 5470): Expected native library version number "",actual native library version number ""
I/chromium( 5470): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  953): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5514 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5116:com.lge.clock/u0a10 (adj 15): empty #11
I/BrowserStartupController( 5470): Initializing chromium process, singleProcess=true
W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5470): ApplicationContext is null in ApplicationStatus
W/libprocessgroup(  953): failed to open /acct/uid_10010/pid_5116/cgroup.procs: No such file or directory
W/chromium( 5470): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5470): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5470): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5470): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5470): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5470): Remote Branch: 
I/Adreno-EGL( 5470): Local Patches: 
I/Adreno-EGL( 5470): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb57e7520, uid 10316
D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb61bb6:true
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
I/ActivityManager(  953): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5549 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5549): Gservices pushing to system: true; secure/global: true
,D/AlertService( 3779): Beginning updateAlertNotification
,D/AlertService( 3779): No fired or scheduled alerts
I/NotificationManager( 3779): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 3779): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 3779): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3779): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3779): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5470): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 5470): [generateLayout] setColorNavigationBar => color=0x ff000001
D/AlarmScheduler( 3779): No events found starting within 1 week.
,D/PhoneWindowEx( 5470): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5470): [setNavigationBarColor2] color=0x fff5f5f5
I/GoogleHttpClient( 5549): GMS http client unavailable, use old client
,D/SystemWebViewEngine( 5470): CordovaWebView is running on device made by: LGE
W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
,I/GoogleHttpClient( 5549): GMS http client unavailable, use old client
,I/Activity( 5470): Activity.onPostResume() called 
,D/OpenGLRenderer( 5470): Render dirty regions requested: true
I/OpenGLRenderer( 5470): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5470): Enabling debug mode 0
D/Atlas   ( 5470): Validating map...
,D/SplitWindow(  953): check instance of lgWin Window{18e44dfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5470): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  953): Killing 5234:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10081/pid_5234/cgroup.procs: No such file or directory
,D/InputDispatcher(  953): Focus entered window: Window{18e44dfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  953): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  953): Displayed com.test.thalitest/.MainActivity: +1s317ms
I/Timeline(  953): Timeline: Activity_windows_visible id: ActivityRecord{19bae8a9 u0 com.test.thalitest/.MainActivity t222} time:81554
,I/Timeline( 5470): Timeline: Activity_idle id: android.os.BinderProxy@9cc4362 time:81562
W/BindingManager( 5470): Cannot call determinedVisibility() - never saw a connection for the pid: 5470
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/GAv4    ( 5514): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5514):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5514):   adb logcat -s GAv4
,W/GAv4    ( 5514): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5514): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5514): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5514): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/JsMessageQueue( 5470): Set native->JS mode to OnlineEventsBridgeMode
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5514): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5514): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5514): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5605 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5293:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/art     ( 5514): CheckpointMarkThreadRoots callback created = 0xaaf2a1f0
,D/charger_monitor(  493): init target 500000
,W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_5293/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5205): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/charger_monitor(  493): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/art     ( 5514): CheckpointMarkThreadRoots callback created = 0xb050fa50
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  953): battery changed pluggedType: 2
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/MainApplication( 5205): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/NotificationManager( 5514): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,W/ResourcesManager( 5605): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5514): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/jxcore_app_log( 5470): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618697600
,W/System  ( 5514): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5514): Installed default security provider GmsCore_OpenSSL
,I/chromium( 5470): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5470): CheckpointMarkThreadRoots callback created = 0x9f998600
,I/art     ( 5470): CheckpointMarkThreadRoots callback created = 0x9f9985d0
,I/ActivityManager(  953): Killing 5315:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10021/pid_5315/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5639 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1946): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1946): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
,D/Finsky  ( 5639): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5639): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5639): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5639): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5639): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/NotificationManager( 5639): com.android.vending: cancel(1003285959) by com.android.vending
,V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@e62e2e0 on behalf of 5639
D/Ads     ( 5639): Skipping gmscore version check
,D/Finsky  ( 5639): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5639): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  953): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5686 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5639): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5639): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5639): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  953): Killing 5343:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/ResourcesManager( 5686): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5686): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  953): failed to open /acct/uid_10009/pid_5343/cgroup.procs: No such file or directory
,I/MultiDex( 5686): VM with version 2.1.0 has multidex support
I/MultiDex( 5686): install
,I/MultiDex( 5686): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  953): Process com.android.contacts (pid 5414) has died
,W/jxcore-log( 5470): Initializing JXcore engine
,W/jxcore-log( 5470): JXcore engine is ready
I/art     ( 5470): Background partial concurrent mark sweep GC freed 21266(1002KB) AllocSpace objects, 2(2MB) LOS objects, 40% free, 16MB/28MB, paused 5.403ms total 55.897ms
,W/Thread-641( 5626): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6275]" dev="sockfs" ino=6275 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-641( 5626): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-641( 5626): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[4997]" dev="sockfs" ino=4997 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-641( 5626): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-641( 5626): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-641( 5626): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26359]" dev="sockfs" ino=26359 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5470): Starting JXcore engine
,I/art     (  953): Explicit concurrent mark sweep GC freed 22448(1139KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 18.608ms total 177.708ms
,I/ActivityManager(  953): Process com.android.gallery3d (pid 5395) has died
,V/JNIHelp ( 5686): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/jxcore-log( 5470): Platform android
W/jxcore-log( 5470): 
,W/jxcore-log( 5470): Process ARCH arm
W/jxcore-log( 5470): 
W/ActivityThread( 5686): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5686): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18aa74c3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5686): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5686): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5686): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5686): Reading stored module config
,D/PackageBroadcastService( 5686): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5686): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5686): Loading module APK com.google.android.play.games
,D/InitAlarmsService( 3779): Clearing and rescheduling alarms.
,D/NativeLibraryUtils( 5686): Install completed successfully. count=14 extracted=0
I/ActivityManager(  953): Process com.lge.appbox.client (pid 5368) has died
,I/ActivityManager(  953): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5722 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5686): CheckpointMarkThreadRoots callback created = 0xb042d3e0
,W/ResourcesManager( 5722): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 5686): CheckpointMarkThreadRoots callback created = 0xb042d3c0
,D/CalendarProvider2( 5722): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3e06764e
,D/CalendarProvider2( 5722): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5722): Created com.android.providers.calendar.CalendarAlarmManager@2788b78b(com.android.providers.calendar.CalendarProvider2@3e06764e)
,D/CalendarProvider2( 5722): Scheduling check of next Alarm
D/CalendarProvider2( 5722): SCHEDULE_ALARM_REMOVE
I/jxcore-log( 5470): JXcore Cordova bridge is ready!
I/jxcore-log( 5470): 
W/jxcore-log( 5470): JXcore engine is started
,D/ChimeraCfgMgr( 5686): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5686): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5686): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5686): Submit a task: k
,D/ChimeraCfgMgr( 5686): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5686): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5686): Processing package: com.test.thalitest
D/GassUtils( 5686): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5686): Found info for package com.test.thalitest in db.
,I/PeopleDatabaseHelper( 5686): cleanUpNonGplusAccounts done.
I/Icing   ( 5686): Storage manager: low false usage 1.78MB avail 2.38GB capacity 4.06GB
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
E/MDM     ( 1735): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationInitializer( 5686): Restart initialization of location
,I/art     ( 5686): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5686): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5763 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 5470): Toggling radios to true
I/jxcore-log( 5470): 
I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 34.264ms
,D/BluetoothAdapter( 5470): enable(): BT is already enabled..!
V/AlarmManager(  953): RTC_WAKEUP set : Alarm{30226d03 type 0 when 1455113489595 com.google.android.googlequicksearchbox} when 1455113489595
D/WifiServiceImplEx(  953): setWifiEnabled: true pid=5470, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.257ms
,D/WifiService(  953): setWifiEnabled: true pid=5470, uid=10316
D/WifiServiceImplEx(  953): disconnect pid=5470, uid=10316, packageName=com.test.thalitest
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.150ms
D/WifiServiceImplEx(  953): reconnect pid=5470, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5470): Radios toggled
I/jxcore-log( 5470): 
I/jxcore-log( 5470): My device name is: LGE-LG-D722
I/jxcore-log( 5470): 
,I/wpa_supplicant( 2757): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2757): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  953): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1806): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/BaseAppContext( 5686): Using Auth Proxy for data requests.
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  953): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1735): Read error: ssl=0xb044c000: I/O error during system call, Connection timed out
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  953): hidePasspointNotification off =false
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  953): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:29.839 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xb044c000: I/O error during system call, Broken pipe
,I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  953): hidePasspointNotification off =false
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:29.849 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2757): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  953): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): ValidatedState{ when=-2ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Forcing reevaluation
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
,E/BaseAppContext( 5686): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/CommandListener(  278): Clearing all IP addresses on wlan0
,W/BaseAppContext( 5686): Using Auth Proxy for data requests.
D/ConnectivityService(  953): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  953): disableDataServiceNotify
D/WifiHS20(  953): hidePasspointNotification off =false
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/DSQN    (  953): stop dsqn bin
,I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:29.947 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/WifiNetworkAgent(  953): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  953): hidePasspointNotification off =false
,D/ConnectivityService(  953): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:29.97 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:29.976 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  953): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  953): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/CSLegacyTypeTracker(  953): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  953): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/DhcpStateMachine(  953): StoppedState
D/DhcpStateMachine(  953): StoppedState{ when=-129ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateSCANNING
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  953): MasterInitialState.processMessage what=3
V/NetworkPolicy(  953): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1830): |CORE| No family connected
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  953): MasterInitialState.processMessage what=3
D/ConnectivityService(  953): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1830): |CORE| No family connected
I/QCNEJ   ( 1830): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  953): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    (  953): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1752): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1830): |CORE| sendDefaultNwMsg: default = -1
D/NetworkManagementService(  953): Removing idletimer
W/Settings(  953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  953): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
W/IcingInternalCorpora( 5686): getNumBytesRead when not calculated.
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/BaseAppContext( 5686): Using Auth Proxy for data requests.
W/BaseAppContext( 5686): Using Auth Proxy for data requests.
,W/BaseAppContext( 5686): Using Auth Proxy for data requests.
W/BaseAppContext( 5686): Using Auth Proxy for data requests.
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/BaseAppContext( 5686): Using Auth Proxy for data requests.
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5763): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CalendarProvider2( 5722): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5722): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/GAV2    ( 5763): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5763): Error finding the version of the Email provider.....
E/Gmail   ( 5763): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5763): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5763): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5763): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5763): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5763): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5763): We do not support migrating this version of the Email provider.
I/Gmail   ( 5763): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/Icing   ( 5686): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/InstanceID/Rpc( 5686): Found 10006
,I/art     ( 5549): Explicit concurrent mark sweep GC freed 7893(397KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.264ms total 48.683ms
,I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5831 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5763): Observing account changes for notifications
,D/ChimeraCfgMgr( 5686): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5686): Module APK com.google.android.play.games already loaded
,I/art     ( 5686): Background sticky concurrent mark sweep GC freed 1020(80KB) AllocSpace objects, 2(32KB) LOS objects, 7% free, 13MB/14MB, paused 6.679ms total 29.284ms
,I/Gmail   ( 5763): notifyAccountChanged
I/Gmail   ( 5763): getAccountsCursor
I/Gmail   ( 5763): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5763): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5763): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Gmail   ( 5763): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/wpa_supplicant( 2757): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/PhoneMonitor( 5831): Register our PhoneStateListener
,D/LocSvc_java(  953): onReceive
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.021 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.025 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/ActivityManager(  953): Killing 3779:com.android.calendar/u0a13 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2757): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/PhoneMonitor( 5831): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5831): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5831): [parse] Load xml
,I/wpa_supplicant( 2757): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2757): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
V/TelephonyAutoProfiling( 5831): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5831): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5831): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  953): failed to open /acct/uid_10013/pid_3779/cgroup.procs: No such file or directory
,D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.164 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension(  953): setVHTCapabilityType  : false
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.172 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/Gmail   ( 5763): getAccountsCursor
I/WifiServerServiceExt(  953): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  953): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  953): setSecurityType  : 2
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.197 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.202 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  953): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  953): Got NetworkAgent Messenger
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  953): NetworkAgent connected
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
D/DhcpStateMachine(  953): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  953): WaitBeforeStartState
E/WifiStateMachine(  953): Start Dhcp Watchdog 2
,I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5861 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  953): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/Icing   ( 5686): Internal init done: storage state 0
,I/NotificationManager( 5686): com.google.android.gms: cancel(10436) by com.google.android.gms
,E/WifiStateMachine(  953): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  953): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  953): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2fa2b5d3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2fa2b5d3 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  953): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  953): DHCP Start wake lock is acquired.
I/art     (  953): Explicit concurrent mark sweep GC freed 41065(1872KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.694ms total 213.656ms
,D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  953): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateCOMPLETED
,D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  953): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/Icing   ( 5686): Post-init done
D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  953): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  953): ignoring duplicate network state non-change
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  953): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.443 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  953): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
E/WifiStateMachine(  953): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.449 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.458 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  953): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  953): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:31.467 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
E/ConnectivityService(  953): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  953): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  953): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  953): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  953): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  953): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  953): Setting Dns servers for network 101 to [/192.168.1.1]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  953): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  953): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/Connectivit,yService(  953): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  953): currentScore = 0, newScore = 20
D/ConnectivityService(  953):    accepting network in place of null
D/ConnectivityService(  953): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  953): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1752): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  953): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  953): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  953): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  953): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/Tethering(  953): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1830): |CORE| No family connected
I/QCNEJ   ( 1830): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1830): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  953): validation of new default Network = false
D/ConnectivityService(  953): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  953): enableDataServiceNotify 
D/DSQN    (  953): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): [LWD] Start DNSResolver start to wait
,V/NetworkPolicy(  953): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): [LWD] wait 500ms before dns check
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  953): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/DSQN    ( 5885): DSQN samuel.seo ver 141203
E/DSQN    ( 5885): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5885): created command queue thread
I/DSQN    ( 5885): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5885): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/ResourcesManager( 5861): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/CheckinService( 5686): Checkin interval check for package: unspecified last checkin: 1455113483304 min interval config: 0 actual interval: 8279
,I/CheckinService( 5686): Disabling old GoogleServicesFramework version
,D/DhcpStateMachine(  953): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  953): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  953): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5892): version 5.5.6 starting
E/dhcpcd  ( 5892): get_duid: Read-only file system
,I/art     ( 5686): Background partial concurrent mark sweep GC freed 22187(1450KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 12MB/21MB, paused 6.411ms total 86.496ms
,I/dhcpcd  ( 5892): wlan0: rebinding lease of 192.168.1.134
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 31917(2MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 13MB/22MB, paused 2.373ms total 113.211ms
I/CheckinService( 5686): Checking schedule, now: 1455113491738 next: 1455113513259
,I/CheckinService( 5686): active receiver: disabled
,I/Babel_SMS( 5861): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5861): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5861): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5861): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5861): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5861): MmsConfig.loadFromResources
,E/Babel_SMS( 5861): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5861): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5861): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5861): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5861): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5861): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5861): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5861): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5861): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5861): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5861): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5861): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5861): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5861): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5861): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5861): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5861): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5861): found sensor: Motion Accel, handle=46
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): [LWD] DNSResolver start dns
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/Settings( 5861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5861): startup - clean
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/art     ( 5861): CheckpointMarkThreadRoots callback created = 0xb042d880
I/System.out(  953): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel   ( 5861): deleted: false for 0
,I/DSQN    ( 5885): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5885): restart monitoring
I/DSQN    ( 5885): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  953): DSQM DsqnNotification wlan0  1
D/DSQN    (  953): start to monitor internet connection
I/art     ( 5861): CheckpointMarkThreadRoots callback created = 0xb042d860
,W/AudioCapabilities( 5861): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5861): Unsupported mime audio/adpcm
W/AudioCapabilities( 5861): Unsupported mime audio/g726
,W/AudioCapabilities( 5861): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5861): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5861): Unsupported mime video/mjpg
,W/VideoCapabilities( 5861): Unsupported mime video/theora
W/AudioCapabilities( 5861): Unsupported mime audio/evrc
,W/AudioCapabilities( 5861): Unsupported mime audio/qcelp
W/VideoCapabilities( 5861): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5861): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5861): Unsupported mime audio/qcelp
W/AudioCapabilities( 5861): Unsupported mime audio/evrc
W/VideoCapabilities( 5861): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5861): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5861): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5861): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5861): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5861): Unrecognized profile 2130706433 for video/avc
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 14:11:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455113492356], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455113492106]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Validated
D/ConnectivityService(  953): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  953):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  953): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  953): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WifiDataContinuityService(  953): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  953): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyNetworkFactory-1( 1752): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  953): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  953): Process com.google.android.apps.docs (pid 5514) has died
,I/vclib   ( 5861): onServiceConnected
W/Babel   ( 5861): Attempted to change video mute state without an active call.
D/ConnectivityService(  953): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 5861): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5861): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5861): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5916 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5183): getMode name:com.lge.qremote
,I/AudioManager( 5183): getMode name:com.lge.qremote
,I/AudioManager( 5183): getMode name:com.lge.qremote
,W/System  ( 5861): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5861): Installed default security provider GmsCore_OpenSSL
,D/UEI.SmartControl( 5916): Quickset Services start...
I/AudioManager( 5183): getMode name:com.lge.qremote
,I/Icing   ( 5686): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/UEI.SmartControl( 5916): Manufacture = LGE
D/UEI.SmartControl( 5916): File observer start...
E/UEI.SmartControl( 5916): IR Port is disabled: false
D/UEI.SmartControl( 5916): Starting file observer...
D/UEI.SmartControl( 5916): Extracting JNI libs...
D/UEI.SmartControl( 5916): --- this system supports 32-bit or 64-bit only
,I/dhcpcd  ( 5892): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
E/MDM     ( 1735): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/NotificationManager( 5861): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LocationInitializer( 5686): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/dhcpcd  ( 5892): wlan0: leased 192.168.1.134 for 86400 seconds
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5183): getMode name:com.lge.qremote
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  953): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService(  953): identical MTU - not setting
D/Nat464Xlat(  953): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  953): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
D/ConnectivityService(  953): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  953): enableDataServiceNotify 
D/DSQN    (  953): start dsqn bin
D/Icing   ( 5686): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  953): Process com.lge.bnr (pid 5205) has died
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,D/DSQN    (  953): dsqn is running restart
,I/Icing   ( 5686): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  953): Process com.lge.lockscreensettings (pid 5448) has died
,I/QCNEJ   ( 1830): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:33.013 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/DSQN    ( 5945): DSQN samuel.seo ver 141203
,E/DSQN    ( 5945): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5945): created command queue thread
I/DSQN    ( 5945): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5945): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  953): onReceive
D/LocSvc_java(  953): got connectivity action
D/LocSvc_java(  953): broadcast - no network connections
D/LocSvc_java(  953): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  953): Sending msg: 4 arg1:0 arg2:1
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  953): onReceive
D/LocSvc_java(  953): got connectivity action
D/LocSvc_java(  953): broadcast - no network connections
D/LocSvc_java(  953): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  953): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  953): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  953): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,D/LocSvc_java(  953): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  953): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  953): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  953): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  953): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  953): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  953): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NotificationManager( 5861): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5965 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  953): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  953): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  953): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  953): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  953): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  953): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  953): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  953): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  953): RunningState
,D/UEI.SmartControl( 5916): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5916): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5916): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5916): --- Selecting new region: 2
,I/UEI.SmartControl( 5916): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5916): Platform has CIR...
D/UEI.SmartControl( 5916): NO CIR support, need to check package...
I/UEI.SmartControl( 5916): Model: LG-D722 uses JNI
I/AppUp4:AppBoxCP( 5965): onCreate
W/AppUp4:DB( 5965):  [AppBoxDatabaseHelper] construct
,D/UEI.SmartControl( 5916): QS Service created
I/AppUp4:DB( 5965):  setFingerPrint start
I/AppUp4:DB( 5965):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/AppUp4:DB( 5965):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5965):  SDK version = 0
I/AppUp4:DB( 5965):  beforefinger == newfinger no write in DB
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,D/AppUp4:AppBoxApplication( 5965): AppBoxApplication onCreate()
I/QCNEJ   ( 1830): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
E/UEI.SmartControl( 5916): QS start get config
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
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/AppUp4:CustModeStarterReceiver( 5965): onReceive
I/AppUp4:CustModeStarterReceiver( 5965): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/AppUp4:CustFacade( 5965): Context : android.app.ReceiverRestrictedContext@48d1505
D/AppUp4:CustFacade( 5965): isCustomizationCompleted : false
I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
D/AppUp4:CustFacade( 5965): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5965): begin check event
I/AppUp4:CustModeStarterReceiver( 5965): Event For Nothing, skip.
D/administrator(  953): Handling package changes for user 0
,D/UEI.SmartControl( 5916): Loading JNI Libs...
D/UEI.SmartControl( 5916):  configuring local db...
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5985 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ActivityManager(  953): Process com.android.vending (pid 5639) has died
,W/ResourcesManager( 5985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5985): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5985): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationService(  953): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  953): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  953): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  953): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@82810db
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,D/UEI.SmartControl( 5916):  ---- Has DB8: true
D/UEI.SmartControl( 5916): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5916): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5916): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5916): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5916): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5916): IrrcClient ++ 
D/irrcClient( 5916): getIrrcService ++ 
,D/irrcClient( 5916): getIrrcService -- 
D/irrcClient( 5916): IrrcClient -- 
W/irrc_jni( 5916): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5916): Services init done
I/UEI.SmartControl( 5916): Device manager: loading config....
D/UEI.SmartControl( 5916): QS Service init finished
,D/UEI.SmartControl( 5916): QS Service version name: 0.1.73
D/UEI.SmartControl( 5916): QS Service version code: 1073
D/UEI.SmartControl( 5916): Config is loaded...
D/UEI.SmartControl( 5916): Service requested: Control
D/UEI.SmartControl( 5916): Internal service binding...
D/UEI.SmartControl( 5916): -----IControl: 11
D/UEI.SmartControl( 5916): Caller: com.lge.qremote
D/UEI.SmartControl( 5916): ------------ IControl registerCallback...
I/UEI.SmartControl( 5916): Registering callback...
D/UEI.SmartControl( 5916): -----IControl: 19
,D/UEI.SmartControl( 5916): Caller: com.lge.qremote
I/UEI.SmartControl( 5916): Registering Services Ready callback...
I/UEI.SmartControl( 5916): Notify client services are ready...
D/UEI.SmartControl( 5916): -----IControl: 8
D/UEI.SmartControl( 5916): Caller: com.lge.qremote
W/ResourcesManager(  953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppConfig( 5985): Total System Memory = 906309632
,D/UEI.SmartControl( 5916):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5916): Notify AllClients services are ready: 0
,I/GalleryUtils( 5985): Application Heap = 96 MB
I/AppConfig( 5985): App Tier : NOT_DEF
D/SystemHelper( 5985): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  953): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6007 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  953): Process com.google.android.apps.plus (pid 5605) has died
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 6007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6007): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6007): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6007): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 6007): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  953): applying state to connected service
V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{3c848597 type 2 when 90151 com.android.providers.calendar} when 90151
,I/QCNEJ   ( 1830): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-10 15:11:34.328 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/SystemConfig( 6007): BUILD Country: EU
I/SystemConfig( 6007): BUILD Operator: OPEN
,V/WifiInternetCheck(  953): Single check msg out of sync, ignoring.
,I/ActivityManager(  953): Process com.google.android.gm (pid 5763) has died
,D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6030 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{1d01e433 type 2 when 90377 com.google.android.gms} when 90377
,D/LocSvc_java(  953): onReceive
D/LocSvc_java(  953): got connectivity action
D/LocSvc_java(  953): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  953): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  953): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  953): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  953): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/SystemConfig( 6007): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6007): existFile = false
,I/SystemConfig( 6007): canReadFile = false
I/SystemConfig( 6007): systemFeature RCS result false
D/SystemConfig( 6007): refreshRcsSupport() :false
,I/LockScreenSettings( 6030): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6030): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6030): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6030): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6030): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6030): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6048 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  953): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourcesManager( 6048): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/lowmemorykiller(  243): Error writing /proc/5183/oom_score_adj; errno=22
,I/UpdateIcingCorporaServi( 1946): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6082 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1946): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
,I/ActivityManager(  953): Process com.lge.qremote (pid 5183) has died
,D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  953): propertyValue:false
,D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  953): propertyValue:false
I/DSQN    ( 5945): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5945): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5945): dsqn report finish
D/DSQN    (  953): DSQM DsqnNotification wlan0  1
D/DSQN    (  953): start to monitor internet connection
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WifiInternetCheck(  953): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  953): Process com.uei.lg.quicksetsdk.lite (pid 5916) has died
,D/Finsky  ( 6082): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6082): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6082): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6082): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6082): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 6082): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@1a7b0999 on behalf of 6082
D/Finsky  ( 6082): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6082): Skipping gmscore version check
D/PackageBroadcastService( 5686): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6082): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  953): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6141 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5686): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5686): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6082): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 6141): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3969fc38:true
,I/art     (  953): Explicit concurrent mark sweep GC freed 68763(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.264ms total 171.189ms
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6171 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.464ms
,V/LGMDMManager( 6141): Create singleton instance
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 321us total 25.920ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 20.521ms
,D/UEI.SmartControl( 6171): Quickset Services start...
I/UEI.SmartControl( 6171): Manufacture = LGE
D/UEI.SmartControl( 6171): File observer start...
E/UEI.SmartControl( 6171): IR Port is disabled: false
D/UEI.SmartControl( 6171): Starting file observer...
D/UEI.SmartControl( 6171): Extracting JNI libs...
,D/UEI.SmartControl( 6171): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6141): getMode name:com.lge.qremote
,I/AudioManager( 6141): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6171): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6171): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6171): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6171): --- Selecting new region: 2
,I/UEI.SmartControl( 6171): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6171): Platform has CIR...
D/UEI.SmartControl( 6171): NO CIR support, need to check package...
I/UEI.SmartControl( 6171): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6171): QS Service created
V/SetupWizard( 5831): Connected to Gservices successfully
,E/UEI.SmartControl( 6171): QS start get config
D/UEI.SmartControl( 6171): Loading JNI Libs...
,D/UEI.SmartControl( 6171):  configuring local db...
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/MDM     ( 1735): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,D/LocationInitializer( 5686): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
,I/ActivityManager(  953): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6205 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6205): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6171):  ---- Has DB8: true
,D/UEI.SmartControl( 6171): QS start statue = true Error code = 0
D/UEI.SmartControl( 6171): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6171): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6171): IRRCDataComm has AudioManager!!!!.
I/IndexDatabaseHelper( 6205): Using schema version: 115
I/IndexDatabaseHelper( 6205): Index is fine
,W/irrc_jni( 6171): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6171): IrrcClient ++ 
D/irrcClient( 6171): getIrrcService ++ 
D/irrcClient( 6171): getIrrcService -- 
D/irrcClient( 6171): IrrcClient -- 
W/irrc_jni( 6171): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6171): Services init done
,D/UEI.SmartControl( 6171): QS Service init finished
D/UEI.SmartControl( 6171): QS Service version name: 0.1.73
D/UEI.SmartControl( 6171): QS Service version code: 1073
D/UEI.SmartControl( 6171): Service requested: Control
I/UEI.SmartControl( 6171): Device manager: loading config....
D/UEI.SmartControl( 6171): Config is loaded...
D/UEI.SmartControl( 6171):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6171): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6171): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6171): Internal service binding...
D/UEI.SmartControl( 6171): -----IControl: 11
,D/UEI.SmartControl( 6171): Caller: com.lge.qremote
D/UEI.SmartControl( 6171): ------------ IControl registerCallback...
I/UEI.SmartControl( 6171): Registering callback...
,D/UEI.SmartControl( 6171): -----IControl: 19
I/Icing   ( 5686): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/UEI.SmartControl( 6171): Caller: com.lge.qremote
I/UEI.SmartControl( 6171): Registering Services Ready callback...
I/UEI.SmartControl( 6171): Notify client services are ready...
D/UEI.SmartControl( 6171): -----IControl: 8
D/UEI.SmartControl( 6171): Caller: com.lge.qremote
,I/ActivityManager(  953): Killing 5722:com.android.providers.calendar/u0a14 (adj 15): empty #11
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Icing   ( 5686): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/ActivityManager(  953): Killing 5495:com.lge.eula/1000 (adj 15): empty #12
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_5722/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_5495/cgroup.procs: No such file or directory
I/ActivityManager(  953): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6232 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5965:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_5965/cgroup.procs: No such file or directory
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{1c70e368 type 0 when 1455113498159 com.android.vending} when 1455113498159
,D/Finsky  ( 6082): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PCSuite ( 6232): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6232): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  953): android: cancelAsUser(2) by android
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/PCSuite ( 6232): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6232): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/PCSuite ( 6232): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6232): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/PCSuite ( 6232): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6232): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/libc-netbsd( 6082): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6082): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6082): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6082): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6264 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5985:com.android.gallery3d/u0a23 (adj 15): empty #11
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 6082): propertyValue:false
D/libc-netbsd( 6082): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6082): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  953): failed to open /acct/uid_10023/pid_5985/cgroup.procs: No such file or directory
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd( 6082): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6082): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 6264): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6264): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 6264): Error finding the version of the Email provider.....
E/Gmail   ( 6264): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6264): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6264): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6264): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6264): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6264): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6264): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6264): We do not support migrating this version of the Email provider.
I/Gmail   ( 6264): Observing account changes for notifications
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6264): getAccountsCursor
I/ActivityManager(  953): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6303 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5470): 
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  953): Killing 6007:com.android.contacts/u0a18 (adj 15): empty #11
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  953): tsOffsetIs: Apps: 94850871323; DSPS: 3199556; Offset : -2797960433
W/libprocessgroup(  953): failed to open /acct/uid_10018/pid_6007/cgroup.procs: No such file or directory
,I/NotificationManager(  953): android: cancelAsUser(2) by android
,W/ResourcesManager( 6303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6303): CalendarApplication.onCreate()
,I/qtaguid ( 6082): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6082): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6082): untagSocket(41) failed with errno -22
D/Finsky  ( 6082): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/PreferenceKeysParser( 6303): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6303): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2109887c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@48d1505, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3357a95a, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2788b78b, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3da4b068, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@54efc81, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@20570126, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@10c94167, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@34486b14, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@38eddfbd, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@a209b2, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@159e8d03, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@16cb2480, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@149dbab9, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3a230efe, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@5f2f65f, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3bfe08ac, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@12d64975, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@151d1d0a, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1bfa997b, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@34990398, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@23cf07f1, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@28f7ffd6, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@370f5257, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@22e6c144, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@29bb322d, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@9cc4362, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@284cbcf3, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2130adb0, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3cc5c429, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2af33ae, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2cec354f, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@22eaf4dc, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@32cd79e5, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@28bedcba, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3260d76b, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3ca082c8, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@26e0cf61, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@12ee0a86, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@337f47, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9f0374, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3c7a009
D/GeneralPreferenceUtils( 6303): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6303): [init]
I/Config  ( 6303): LGCalendar ver.4.40.17
I/Config  ( 6303): start check model
I/Config  ( 6303): start check native_ca
,I/Config  ( 6303): Config Operator=OPEN, Country=EU
D/Config  ( 6303): [setDefaultValuesToPref]
D/Config  ( 6303): [parseProfiles]
D/ProfilesParser( 6303): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6303): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6303): [updateProfiletoCountryInfo]
D/GeneralPreference( 6303): [checkAndMigrateOldPreference]
D/AlertReceiver( 6303): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6303): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6303): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/Gmail   ( 6264): notifyAccountChanged
,I/Gmail   ( 6264): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6264): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6264): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6264): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  953): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6332 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/Gmail   ( 6264): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  953): android: cancelAsUser(2) by android
,I/AlertUtils( 6303): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
W/ResourcesManager( 6332): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6332): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
W/HolidayIntentService( 6303): onHandleIntent
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,D/HolidayDataLoader( 6303): readJsonAsset : holiday.json
I/AlertUtils( 6303): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6303): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6303): set default noti to content://media/internal/audio/media/38
,D/AlertService( 6303): 0 Action = android.intent.action.PROVIDER_CHANGED
I/InitNotificationRingtoneService( 6303): End InitializeAlertRingtoneService.onHandleIntent
,E/AgendaWidgetManager( 6303): [updateWidgets] 
,D/MonthWidgetProvider( 6303): [onReceive]
D/CalendarWidgetProvider( 6303): [onReceive]
D/CalendarWidgetProvider( 6303): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6303): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6303): [onReceive]
D/CalendarWidgetProvider( 6303): [onReceive]
D/CalendarWidgetProvider( 6303): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6303): [onCreate] mContext.getPackageName() = com.android.calendar
I/MultiDex( 6332): VM with version 2.1.0 has multidex support
I/MultiDex( 6332): install
I/MultiDex( 6332): VM has multidex support, MultiDex support library is disabled.
,E/HolidayIntentService( 6303): onHandleIntent:holiday data empty
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{27d4143c type 0 when 1455113499554 com.google.android.googlequicksearchbox} when 1455113499554
,V/JNIHelp ( 6332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6082): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6082): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6082): untagSocket(41) failed with errno -22
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6205): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/art     (  953): Explicit concurrent mark sweep GC freed 19035(945KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 12.852ms total 193.190ms
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/Gmail   ( 6264): getAccountsCursor
,W/ActivityThread( 6332): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6332): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19e9a655: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6332): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6332): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6332): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ChimeraCfgMgr( 6332): Reading stored module config
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/ChimeraCfgMgr( 6332): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/PCSuite ( 6232): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
I/PCSuite ( 6232): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6364 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6332): Install completed successfully. count=14 extracted=0
,I/art     ( 6082): CheckpointMarkThreadRoots callback created = 0xb042d990
,I/art     ( 6082): CheckpointMarkThreadRoots callback created = 0xb042d950
,I/ActivityManager(  953): Process com.google.android.apps.plus (pid 6048) has died
D/CAR.SERVICE( 6332): Connecting to CarCallService...
,I/art     ( 6332): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6332): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5470): 
,D/CAR.SERVICE( 6332): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6332): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6332): Creating a new PhoneAdapter instance
W/ActivityManager(  953): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6332): setListener: com.google.android.gms.car.dn@13350528
W/ActivityManager(  953): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6332): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6332): Starting CarCallService with initial phone null
I/NotificationManager( 6332): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 6332): CheckpointMarkThreadRoots callback created = 0xb042da00
,I/art     ( 6332): CheckpointMarkThreadRoots callback created = 0xb042d9f0
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5470): 
I/MusicStore( 6364): Database version: 120
I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5470): 
,D/CAR.SERVICE( 6332): Package validated; name: com.android.vending
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5470): 
,I/ActivityManager(  953): Process com.google.android.talk (pid 5861) has died
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5470): 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/NotificationManager( 6082): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6082): [1] GearheadStateMonitor.access$100: mIsProjecting:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6364): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6364): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6364): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6364): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6364): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/NotificationManager(  953): android: cancelAsUser(2) by android
W/ActivityThread( 6364): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6364): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39615204: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6364): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6364): GMSCore installation verified
I/ConfigStore( 6364): Config Database version: 1
,I/MediaRouter( 6364): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6364): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6364): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6364): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  953): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6402 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6364): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6364): Using platform SSLCertificateSocketFactory
,I/qtaguid ( 6082): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6082): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6082): untagSocket(41) failed with errno -22
I/art     ( 5549): Explicit concurrent mark sweep GC freed 3020(121KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 435us total 40.948ms
W/ResourcesManager( 6402): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6402): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  953): Process com.google.android.gm (pid 6264) has died
,I/NotificationManager( 6364): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 6402): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6402): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/ResourcesManager( 6082): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6082): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 6082): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{181acf7e type 0 when 1455113501814 com.android.vending} when 1455113501814
,D/DeviceConnectionService( 1735): client connected with version: 8296000
,D/Finsky  ( 6082): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6082): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/eas_req ( 6402): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  953): Process com.android.settings (pid 6205) has died
,I/ActivityManager(  953): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6431 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6402): JNI_OnLoad()
I/HubEmail( 6402): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6402): registerNatives()
I/HubEmail( 6402): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6402): registerNativeMethods()
I/HubEmail( 6402): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6402): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  953): Killing 6030:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10069/pid_6030/cgroup.procs: No such file or directory
,D/LGDMClient( 6431): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6431): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6431): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6431): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6431): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6431): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6431): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6431): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6459 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6431): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6431): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6431): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6431): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6431): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6431): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  953): Killing 6171:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6141): android.os.DeadObjectException
,W/System.err( 6141): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6141): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6141): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6141): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6141): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6141): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6141): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6141): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6141): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6141): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6141): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6141): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6141): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6141): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6141): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6141): android.os.DeadObjectException
W/System.err( 6141): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6141): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6141): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6141): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6141): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6141): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6141): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6141): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6141): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6141): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6141): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6141): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6141): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6141): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6141): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/AppUp4:AppBoxCP( 6459): onCreate
,W/AppUp4:DB( 6459):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6459):  setFingerPrint start
I/AppUp4:DB( 6459):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6459):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6459):  SDK version = 0
I/AppUp4:DB( 6459):  beforefinger == newfinger no write in DB
W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_6171/cgroup.procs: No such file or directory
W/ActivityManager(  953): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/AppUp4:AppBoxApplication( 6459): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6459): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6459): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6459): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6459): [onReceive] request level :IDLE....
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6477 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/AppUp4:CustModeStarterReceiver( 6459): onReceive
I/AppUp4:CustModeStarterReceiver( 6459): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6459): Context : android.app.ReceiverRestrictedContext@3da4b068
D/AppUp4:CustFacade( 6459): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6459): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6459): begin check event
I/AppUp4:CustModeStarterReceiver( 6459): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6459): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6459): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6459): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6459): handleAsyncCustNotification do not startCustService
I/ActivityManager(  953): Killing 6232:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6477): Quickset Services start...
,I/UEI.SmartControl( 6477): Manufacture = LGE
D/UEI.SmartControl( 6477): File observer start...
E/UEI.SmartControl( 6477): IR Port is disabled: false
D/UEI.SmartControl( 6477): Starting file observer...
D/UEI.SmartControl( 6477): Extracting JNI libs...
D/UEI.SmartControl( 6477): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_6232/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6477): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6477): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6477): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/LgeMiscReceiver( 3192): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3192): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3192): networkInfo.isConnected() = false
,I/UEI.SmartControl( 6477): --- Selecting new region: 2
I/UEI.SmartControl( 6477): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6477): Platform has CIR...
D/UEI.SmartControl( 6477): NO CIR support, need to check package...
I/UEI.SmartControl( 6477): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6477): QS Service created
D/MobileConnectivityChangeReceiver( 5831): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5831): onReceive CONNECTIVITY_CHANGE networkType=1
,E/UEI.SmartControl( 6477): QS start get config
V/DownloadManager( 3221): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3221): DownloadService onCreate
I/NotificationManager( 3221): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3221): in removeSpuriousFiles
V/DownloadManager( 3221): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@8a5e45e on behalf of 3221
,I/DownloadManager( 3221): in trimDatabase
V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@38eb103f on behalf of 3221
D/UEI.SmartControl( 6477): Loading JNI Libs...
,D/UEI.SmartControl( 6477):  configuring local db...
I/ActivityManager(  953): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6500 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3221): DownloadService onStartCommand
,I/art     (  303): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 290us total 26.938ms
I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 21.219ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 334us total 20.810ms
V/DownloadManager( 3221): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@33e7e86a on behalf of 3221
,V/DownloadManager( 3221): DownloadService onDestroy
,I/ActivityManager(  953): Killing 6141:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 6477):  ---- Has DB8: true
,D/UEI.SmartControl( 6477): QS start statue = true Error code = 0
D/UEI.SmartControl( 6477): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6477): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6477): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6477): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6477): IrrcClient ++ 
D/irrcClient( 6477): getIrrcService ++ 
D/irrcClient( 6477): getIrrcService -- 
D/irrcClient( 6477): IrrcClient -- 
W/irrc_jni( 6477): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6477): Services init done
,I/UEI.SmartControl( 6477): Device manager: loading config....
D/UEI.SmartControl( 6477): Config is loaded...
D/UEI.SmartControl( 6477):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6477): Notify AllClients services are ready: 0
,W/libprocessgroup(  953): failed to open /acct/uid_10106/pid_6141/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6477): QS Service init finished
,D/UEI.SmartControl( 6477): QS Service version name: 0.1.73
D/UEI.SmartControl( 6477): QS Service version code: 1073
D/UEI.SmartControl( 6477): Service requested: Control
D/UEI.SmartControl( 6477): Service.onUnbind: IControl
D/UEI.SmartControl( 6477): Service.onDestroy
D/UEI.SmartControl( 6477): Shutdown IRRCPlayer... 
D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:43
,D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
,D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:43
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/irrc_jni( 6477): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6477): ~IrrcClient ++ 
D/irrcClient( 6477): ~IrrcClient -- 
W/irrc_jni( 6477): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6477): Blaster closed
D/UEI.SmartControl( 6477): Blaster closed
D/UEI.SmartControl( 6477): Shut down QS...
D/UEI.SmartControl( 6477): Stopped file observer...
I/UEI.SmartControl( 6477): QS lib stop result = true
D/UEI.SmartControl( 6477): QS shutdown complete
D/UEI.SmartControl( 6477): QS Service created
,E/UEI.SmartControl( 6477): QS start get config
,I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6526 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/UEI.SmartControl( 6477):  configuring local db...
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6477):  ---- Has DB8: true
,D/UEI.SmartControl( 6477): QS start statue = true Error code = 0
D/UEI.SmartControl( 6477): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6477): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6477): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6477): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6477): IrrcClient ++ 
D/irrcClient( 6477): getIrrcService ++ 
D/irrcClient( 6477): getIrrcService -- 
D/irrcClient( 6477): IrrcClient -- 
W/irrc_jni( 6477): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6477): Services init done
I/UEI.SmartControl( 6477): Device manager: loading config....
,D/UEI.SmartControl( 6477): QS Service init finished
D/UEI.SmartControl( 6477): QS Service version name: 0.1.73
D/UEI.SmartControl( 6477): QS Service version code: 1073
D/UEI.SmartControl( 6477): Service requested: Control
D/UEI.SmartControl( 6477): Config is loaded...
D/UEI.SmartControl( 6477):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6477): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6477): Request IControl service: devices are loaded...
,I/ActivityManager(  953): Killing 6364:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10081/pid_6364/cgroup.procs: No such file or directory
,E/ActivityThread( 6477): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@10c94167 that was originally bound here
E/ActivityThread( 6477): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@10c94167 that was originally bound here
E/ActivityThread( 6477): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6477): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6477): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6477): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6477): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6477): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6477): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6477): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6477): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6477): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6477): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6477): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6477): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6477): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6477): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6477): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6477): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6477): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6477): Internal service binding...
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Babel_SMS( 6526): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6526): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6526): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6526): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6526): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6526): MmsConfig.loadFromResources
E/Babel_SMS( 6526): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6526): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6526): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6526): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6526): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6526): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6526): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6526): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6526): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6526): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6526): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6526): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6526): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6526): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6526): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6526): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6526): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6526): found sensor: Motion Accel, handle=46
I/art     ( 6526): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 6526): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6526): startup - clean
I/art     ( 6526): CheckpointMarkThreadRoots callback created = 0xb042d860
I/Babel   ( 6526): deleted: false for 0
,I/ActivityManager(  953): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6563 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6526): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6526): Unsupported mime audio/adpcm
W/AudioCapabilities( 6526): Unsupported mime audio/g726
W/AudioCapabilities( 6526): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6526): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6526): Unsupported mime video/mjpg
,W/VideoCapabilities( 6526): Unsupported mime video/theora
,W/AudioCapabilities( 6526): Unsupported mime audio/evrc
,W/AudioCapabilities( 6526): Unsupported mime audio/qcelp
W/VideoCapabilities( 6526): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6526): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6526): Unsupported mime audio/qcelp
W/AudioCapabilities( 6526): Unsupported mime audio/evrc
W/VideoCapabilities( 6526): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6526): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6526): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6526): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6526): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6526): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6526): onServiceConnected
W/Babel   ( 6526): Attempted to change video mute state without an active call.
,I/ActivityManager(  953): Process com.android.vending (pid 6082) has died
,D/CAR.SERVICE( 6332): mConnectedToCar = false, abort
I/NotificationManager( 6526): com.google.android.talk: cancel(10436) by com.google.android.talk
E/ActivityThread( 6332): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@30e4c410 that was originally bound here
E/ActivityThread( 6332): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@30e4c410 that was originally bound here
E/ActivityThread( 6332): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6332): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6332): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6332): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6332): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6332): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6332): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6332): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6332): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6332): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6332): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6332): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6332): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6332): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6332): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6332): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6332): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2606674b that was originally bound here
E/ActivityThread( 6332): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2606674b that was originally bound here
E/ActivityThread( 6332): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6332): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6332): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6332): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6332): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6332): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6332): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6332): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6332): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6332): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6332): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6332): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6332): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6332): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6332): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6332): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6332): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6332): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  953): Unbind failed: could not find connection for android.os.BinderProxy@3465418e
D/libc-netbsd( 6526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6526): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6526): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6526): propertyValue:false
D/AlertService( 6303): Beginning updateAlertNotification
,I/Babel   ( 6526): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  953): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6585 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6585): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6585): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3e06764e
,D/CalendarProvider2( 6585): [getOrCreateCalendarAlarmManager]
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6563): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/CalendarProvider2( 6585): Created com.android.providers.calendar.CalendarAlarmManager@2788b78b(com.android.providers.calendar.CalendarProvider2@3e06764e)
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6563): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/AlertService( 6303): No fired or scheduled alerts
I/NotificationManager( 6303): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6303): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(14) by com.android.calendar
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 6563): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6563):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6563):   adb logcat -s GAv4
I/NotificationManager( 6303): com.android.calendar: cancel(15) by com.android.calendar
W/ContextImpl( 6563): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/NotificationManager( 6303): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6303): com.android.calendar: cancel(18) by com.android.calendar
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/NotificationManager( 6303): com.android.calendar: cancel(19) by com.android.calendar
W/ContextImpl( 6563): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/NotificationManager( 6303): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6303): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/ActivityManager(  953): Killing 6332:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_6332/cgroup.procs: No such file or directory
,W/GAv4    ( 6563): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/AlarmScheduler( 6303): No events found starting within 1 week.
,W/GAv4    ( 6563): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6563): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  953): Killing 6303:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10013/pid_6303/cgroup.procs: No such file or directory
,I/art     (  953): Explicit concurrent mark sweep GC freed 19091(895KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.881ms total 150.943ms
,I/WebViewFactory( 6563): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6563): Time to load native libraries: 1 ms (timestamps 1387-1388)
I/LibraryLoader( 6563): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6563): Binding Chromium to main looper Looper (main, tid 1) {961cec5}
I/LibraryLoader( 6563): Expected native library version number "",actual native library version number ""
I/chromium( 6563): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6563): Initializing chromium process, singleProcess=true
W/art     ( 6563): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6563): ApplicationContext is null in ApplicationStatus
,W/chromium( 6563): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6563): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6563): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6563): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6563): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6563): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6563): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6563): Remote Branch: 
I/Adreno-EGL( 6563): Local Patches: 
I/Adreno-EGL( 6563): Reconstruct Branch: 
I/NSApplication( 6563): Starting up...
,V/AudioPolicyService(  282): registerClient() client 0xb57e7560, uid 10079
W/AudioManagerAndroid( 6563): Requires BLUETOOTH permission
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  953): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6654 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 6402:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10021/pid_6402/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6673 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 6431:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_6431/cgroup.procs: No such file or directory
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5686): SYNC; picasa accounts
,D/NetworkLogImpl( 5686): Loaded NetworkSpeedPredictor
I/iu.Environment( 5686): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  953): Killing 6459:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/iu.UploadsManager( 5686): num queued entries: 0
I/iu.UploadsManager( 5686): num updated entries: 0
I/iu.SyncManager( 5686): NEXT; no task
W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_6459/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6700 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6700): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6700): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6700): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6700): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6700): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6700): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/ActivityThread( 6700): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6700): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39615204: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6700): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6700): GMSCore installation verified
,I/ConfigStore( 6700): Config Database version: 1
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/MediaRouter( 6700): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6700): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6700): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  953): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6741 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/UEI.SmartControl( 6477): file observer is disposed!
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/GHttpClientFactory( 6700): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6700): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  953): Killing 5831:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 6741): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6741): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6741): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  953): failed to open /acct/uid_10038/pid_5831/cgroup.procs: No such file or directory
I/NotificationManager( 6700): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6741): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6741): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6741): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  953): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6776 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6741): JNI_OnLoad()
I/HubEmail( 6741): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6741): registerNatives()
I/HubEmail( 6741): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6741): registerNativeMethods()
I/HubEmail( 6741): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6741): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  953): Killing 6500:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/UEI.SmartControl( 6477): Internal timer expired: 2
,W/libprocessgroup(  953): failed to open /acct/uid_10051/pid_6500/cgroup.procs: No such file or directory
,W/Settings( 6741): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 6477): Service.onUnbind: IControl
D/UEI.SmartControl( 6477): Service.onDestroy
D/UEI.SmartControl( 6477): Shutdown IRRCPlayer... 
W/irrc_jni( 6477): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6477): ~IrrcClient ++ 
D/irrcClient( 6477): ~IrrcClient -- 
W/irrc_jni( 6477): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6477): Blaster closed
D/UEI.SmartControl( 6477): Blaster closed
D/UEI.SmartControl( 6477): Shut down QS...
I/UEI.SmartControl( 6477): QS lib stop result = true
D/UEI.SmartControl( 6477): QS shutdown complete
D/LGDMClient( 6776): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6776): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6776): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6776): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6776): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6776): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6805 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6776): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6776): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6776): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6776): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6776): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  953): Killing 6477:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_6477/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6805): onCreate
,W/AppUp4:DB( 6805):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6805):  setFingerPrint start
I/AppUp4:DB( 6805):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6805):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6805):  SDK version = 0
I/AppUp4:DB( 6805):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6805): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6805): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6805): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6805): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6805): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6805): onReceive
I/AppUp4:CustModeStarterReceiver( 6805): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6805): Context : android.app.ReceiverRestrictedContext@3da4b068
D/AppUp4:CustFacade( 6805): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6805): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6805): begin check event
I/AppUp4:CustModeStarterReceiver( 6805): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6805): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6805): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6805): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6805): handleAsyncCustNotification do not startCustService
I/ActivityManager(  953): Killing 6526:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10061/pid_6526/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3192): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3192): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3192): networkInfo.isConnected() = false
,I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6831 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5470): 
,D/PhoneMonitor( 6831): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6831): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6831): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  953): Killing 6563:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5470): 
W/libprocessgroup(  953): failed to open /acct/uid_10079/pid_6563/cgroup.procs: No such file or directory
,V/DownloadManager( 3221): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3221): DownloadService onCreate
I/NotificationManager( 3221): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3221): in removeSpuriousFiles
,V/DownloadManager( 3221): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@6de2df8 on behalf of 3221
,I/DownloadManager( 3221): in trimDatabase
V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@246b52d1 on behalf of 3221
,I/ActivityManager(  953): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6857 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/PhoneMonitor( 6831): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6831): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6831): [parse] Load xml
,V/TelephonyAutoProfiling( 6831): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6831): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 22.755ms
V/DownloadManager( 3221): DownloadService onStartCommand
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.881ms
I/CheckinService( 5686): Checkin interval check for package: unspecified last checkin: 1455113483304 min interval config: 0 actual interval: 26767
V/DownloadManager( 3221): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6831): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@27c431a4 on behalf of 3221
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 21.661ms
V/DownloadManager( 3221): DownloadService onDestroy
I/CheckinService( 5686): Checking schedule, now: 1455113510135 next: 1455113513259
,I/CheckinService( 5686): active receiver: disabled
I/ActivityManager(  953): Killing 6585:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_6585/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:50
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:50
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6883 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6883): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6883): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6883): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6883): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6883): MmsConfig.loadFromResources
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/Babel_SMS( 6883): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6883): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6883): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6883): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6883): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6883): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6883): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6883): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6883): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6883): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6883): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6883): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6883): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6883): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6883): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6883): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6883): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6883): found sensor: Motion Accel, handle=46
,W/Settings( 6883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6883): startup - clean
I/Babel   ( 6883): deleted: false for 0
,I/art     ( 6883): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/art     ( 6883): CheckpointMarkThreadRoots callback created = 0xb042d8d0
,I/ActivityManager(  953): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6922 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6883): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6883): Unsupported mime audio/adpcm
W/AudioCapabilities( 6883): Unsupported mime audio/g726
W/AudioCapabilities( 6883): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6883): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6883): Unsupported mime video/mjpg
W/VideoCapabilities( 6883): Unsupported mime video/theora
,W/AudioCapabilities( 6883): Unsupported mime audio/evrc
,W/AudioCapabilities( 6883): Unsupported mime audio/qcelp
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6883): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6883): Unsupported mime audio/qcelp
I/jxcore-log( 5470): Test app app.js loaded
I/jxcore-log( 5470): 
W/AudioCapabilities( 6883): Unsupported mime audio/evrc
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33c87aff added. We now have 1 listener(s)
W/VideoCapabilities( 6883): Unsupported mime video/mp4v-esdp
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
I/jxcore-log( 5470): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5470): 
I/VideoCapabilities( 6883): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
,I/chromium( 5470): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6883): onServiceConnected
,W/Babel   ( 6883): Attempted to change video mute state without an active call.
I/NotificationManager( 6883): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6883): propertyValue:false
I/GAv4    ( 6922): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6922):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6922):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6922): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6922): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6922): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 6883): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  953): Killing 6654:com.android.chrome/u0a48 (adj 15): empty #11
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6922): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6922): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6922): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6922): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  953): failed to open /acct/uid_10048/pid_6654/cgroup.procs: No such file or directory
,I/WebViewFactory( 6922): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/CheckinService( 5686): Done disabling old GoogleServicesFramework version
,I/art     (  953): Explicit concurrent mark sweep GC freed 19406(936KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.449ms total 157.028ms
,I/LibraryLoader( 6922): Time to load native libraries: 2 ms (timestamps 7570-7572)
I/LibraryLoader( 6922): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6922): Binding Chromium to main looper Looper (main, tid 1) {961cec5}
I/LibraryLoader( 6922): Expected native library version number "",actual native library version number ""
I/chromium( 6922): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6922): Initializing chromium process, singleProcess=true
,W/art     ( 6922): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6922): ApplicationContext is null in ApplicationStatus
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/chromium( 6922): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6922): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6922): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6922): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6922): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6922): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6922): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6922): Remote Branch: 
I/Adreno-EGL( 6922): Local Patches: 
I/Adreno-EGL( 6922): Reconstruct Branch: 
,V/AudioPolicyService(  282): registerClient() client 0xb57e7540, uid 10079
,W/AudioManagerAndroid( 6922): Requires BLUETOOTH permission
I/NSApplication( 6922): Starting up...
I/ActivityManager(  953): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6991 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 6673:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10086/pid_6673/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7010 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 6700:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10081/pid_6700/cgroup.procs: No such file or directory
W/ResourcesManager( 7010): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  953): Killing 6741:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10021/pid_6741/cgroup.procs: No such file or directory
,I/AppUp4:CustModeStarterReceiver( 6805): onReceive
I/AppUp4:CustModeStarterReceiver( 6805): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6805): Context : android.app.ReceiverRestrictedContext@3da4b068
D/AppUp4:CustFacade( 6805): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6805): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6805): begin check event
I/AppUp4:CustModeStarterReceiver( 6805): Event For Nothing, skip.
I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7036 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 6883): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7036): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7036): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6883): Installed default security provider GmsCore_OpenSSL
,I/AppConfig( 7036): Total System Memory = 906309632
I/GalleryUtils( 7036): Application Heap = 96 MB
I/AppConfig( 7036): App Tier : NOT_DEF
D/SystemHelper( 7036): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7063 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7063): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7063): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7063): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7063): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7063): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7063): BUILD Country: EU
I/SystemConfig( 7063): BUILD Operator: OPEN
,I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7085 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 6776:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_6776/cgroup.procs: No such file or directory
I/SystemConfig( 7063): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7063): existFile = false
I/SystemConfig( 7063): canReadFile = false
I/SystemConfig( 7063): systemFeature RCS result false
D/SystemConfig( 7063): refreshRcsSupport() :false
,I/LockScreenSettings( 7085): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7085): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7085): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7085): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7085): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7085): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1946): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7106 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 6831:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1946): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
W/libprocessgroup(  953): failed to open /acct/uid_10038/pid_6831/cgroup.procs: No such file or directory
,D/Finsky  ( 7106): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7106): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7106): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7106): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7106): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 7106): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7106): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7106): Skipping gmscore version check
V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@1af91ac2 on behalf of 7106
I/ActivityManager(  953): Killing 6857:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10051/pid_6857/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5686): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  953): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7162 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5686): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7106): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 5686): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 7106): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7162): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3570e439:true
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7195 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7162): Create singleton instance
,D/UEI.SmartControl( 7195): Quickset Services start...
,I/UEI.SmartControl( 7195): Manufacture = LGE
D/UEI.SmartControl( 7195): File observer start...
E/UEI.SmartControl( 7195): IR Port is disabled: false
,D/UEI.SmartControl( 7195): Starting file observer...
D/UEI.SmartControl( 7195): Extracting JNI libs...
D/UEI.SmartControl( 7195): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7162): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7195): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7195): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7195): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  953): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7219 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UEI.SmartControl( 7195): --- Selecting new region: 2
I/UEI.SmartControl( 7195): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7195): Platform has CIR...
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 31.142ms
,D/UEI.SmartControl( 7195): NO CIR support, need to check package...
I/UEI.SmartControl( 7195): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7195): QS Service created
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.908ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 20.874ms
,W/ResourcesManager( 7219): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/UEI.SmartControl( 7195): QS start get config
D/CalendarProvider2( 7219): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3e06764e
,D/UEI.SmartControl( 7195): Loading JNI Libs...
,D/UEI.SmartControl( 7195):  configuring local db...
D/CalendarProvider2( 7219): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7219): Created com.android.providers.calendar.CalendarAlarmManager@2788b78b(com.android.providers.calendar.CalendarProvider2@3e06764e)
D/CalendarProviderBroadcastReceiver( 7219): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7219): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 7219): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7219): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7219): [getOrCreateCalendarAlarmManager]
,I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7242 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/CalendarProvider2( 7219): [IntentService] Release Lock
,D/CalendarProvider2( 7219): CalendarProviderIntentService.onDestroy()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7195):  ---- Has DB8: true
,D/UEI.SmartControl( 7195): QS start statue = true Error code = 0
D/UEI.SmartControl( 7195): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7195): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7195): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7195): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7195): IrrcClient ++ 
D/irrcClient( 7195): getIrrcService ++ 
D/irrcClient( 7195): getIrrcService -- 
D/irrcClient( 7195): IrrcClient -- 
W/irrc_jni( 7195): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7195): Services init done
I/UEI.SmartControl( 7195): Device manager: loading config....
D/UEI.SmartControl( 7195): QS Service init finished
D/UEI.SmartControl( 7195): QS Service version name: 0.1.73
D/UEI.SmartControl( 7195): QS Service version code: 1073
D/UEI.SmartControl( 7195): Service requested: Control
D/UEI.SmartControl( 7195): Config is loaded...
,D/UEI.SmartControl( 7195): -----IControl: 11
D/UEI.SmartControl( 7195): Caller: com.lge.qremote
D/UEI.SmartControl( 7195): ------------ IControl registerCallback...
I/UEI.SmartControl( 7195): Registering callback...
D/UEI.SmartControl( 7195): -----IControl: 19
D/UEI.SmartControl( 7195): Internal service binding...
D/UEI.SmartControl( 7195): Caller: com.lge.qremote
I/UEI.SmartControl( 7195): Registering Services Ready callback...
I/UEI.SmartControl( 7195): Notify client services are ready...
,D/UEI.SmartControl( 7195): -----IControl: 8
D/UEI.SmartControl( 7195): Caller: com.lge.qremote
I/ActivityManager(  953): Killing 6991:com.android.chrome/u0a48 (adj 15): empty #11
,D/UEI.SmartControl( 7195):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7195): Notify AllClients services are ready: 0
I/ActivityManager(  953): Killing 6922:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,I/MusicStore( 7242): Database version: 120
,W/libprocessgroup(  953): failed to open /acct/uid_10048/pid_6991/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_10079/pid_6922/cgroup.procs: No such file or directory
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7242): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Icing   ( 5686): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7242): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7242): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Icing   ( 5686): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/ResourcesManager( 7242): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7242): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7242): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7242): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7242): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39615204: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7242): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7242): GMSCore installation verified
I/ConfigStore( 7242): Config Database version: 1
,I/MediaRouter( 7242): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7242): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7242): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  953): Killing 6805:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_6805/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7242): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  953): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7281 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/ResourcesManager( 7281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7281): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7281): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AlarmManager(  953): RTC_WAKEUP set : Alarm{3c6e7f66 type 0 when 1455113513259 com.google.android.gms} when 1455113513259
V/AlarmManager(  953): RTC_WAKEUP set : Alarm{5db354 type 0 when 1455113515814 com.android.vending} when 1455113515814
I/art     (  953): Explicit concurrent mark sweep GC freed 22980(1087KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.104ms total 173.005ms
,I/GHttpClientFactory( 7242): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7242): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 7242): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7281): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7281): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 7106): [885] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7106): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  953): Killing 7036:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10023/pid_7036/cgroup.procs: No such file or directory
,D/eas_req ( 7281): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  953): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7315 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7281): JNI_OnLoad()
I/HubEmail( 7281): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7281): registerNatives()
I/HubEmail( 7281): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7281): registerNativeMethods()
I/HubEmail( 7281): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7281): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7281): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  953): Killing 7063:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10018/pid_7063/cgroup.procs: No such file or directory
,D/LGDMClient( 7315): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7315): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7315): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7315): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7315): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7315): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7345 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7315): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7315): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7315): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7315): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7315): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  953): Killing 7085:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 7345): onCreate
W/AppUp4:DB( 7345):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7345):  setFingerPrint start
I/AppUp4:DB( 7345):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/libprocessgroup(  953): failed to open /acct/uid_10069/pid_7085/cgroup.procs: No such file or directory
,I/AppUp4:DB( 7345):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7345):  SDK version = 0
I/AppUp4:DB( 7345):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7345): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7345): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7345): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7345): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7345): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7345): onReceive
I/AppUp4:CustModeStarterReceiver( 7345): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7345): Context : android.app.ReceiverRestrictedContext@3da4b068
D/AppUp4:CustFacade( 7345): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7345): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7345): begin check event
I/AppUp4:CustModeStarterReceiver( 7345): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7345): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7345): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7345): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7345): handleAsyncCustNotification do not startCustService
I/ActivityManager(  953): Killing 7010:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10086/pid_7010/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3192): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3192): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3192): networkInfo.isConnected() = true
,D/PhoneState( 3192): setPdpRejectCasuse : false
I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7364 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7364): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7364): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7364): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  953): Killing 7162:com.lge.qremote/u0a106 (adj 15): empty #11
D/PhoneMonitor( 7364): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7364): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7364): [parse] Load xml
V/TelephonyAutoProfiling( 7364): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 7364): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7364): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  953): failed to open /acct/uid_10106/pid_7162/cgroup.procs: No such file or directory
,V/DownloadManager( 3221): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3221): DownloadService onCreate
I/NotificationManager( 3221): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3221): in removeSpuriousFiles
V/DownloadManager( 3221): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@1643b0d3 on behalf of 3221
I/DownloadManager( 3221): in trimDatabase
V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@30e4c410 on behalf of 3221
I/ActivityManager(  953): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7386 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3221): DownloadService onStartCommand
V/DownloadManager( 3221): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5686): Checkin interval check for package: unspecified last checkin: 1455113483304 min interval config: 0 actual interval: 33416
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@348e872f on behalf of 3221
,I/CheckinService( 5686): Checking schedule, now: 1455113516739 next: 1455113513259
I/CheckinService( 5686): active receiver: enabled
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/DownloadManager( 3221): DownloadService onDestroy
I/CheckinService( 5686): Preparing to send checkin request
,I/EventLogService( 5686): Accumulating logs since 1455113474499
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:56
,D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:56
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  953): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7406 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinRequestBuilder( 5686): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5686): Failed to find provider info for com.google.android.wearable.settings
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7406): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7406): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7406):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7406):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7406): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7406): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 7406): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 7406): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7406): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7406): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  953): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7457 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7457): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/WebViewFactory( 7406): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ResourcesManager( 7457): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LibraryLoader( 7406): Time to load native libraries: 4 ms (timestamps 3281-3285)
I/LibraryLoader( 7406): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7406): Binding Chromium to main looper Looper (main, tid 1) {961cec5}
,I/LibraryLoader( 7406): Expected native library version number "",actual native library version number ""
,I/chromium( 7406): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/MultiDex( 7457): VM with version 2.1.0 has multidex support
I/MultiDex( 7457): install
I/MultiDex( 7457): VM has multidex support, MultiDex support library is disabled.
I/BrowserStartupController( 7406): Initializing chromium process, singleProcess=true
,W/art     ( 7406): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7406): ApplicationContext is null in ApplicationStatus
W/chromium( 7406): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7406): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7406): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7406): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7406): Remote Branch: 
I/Adreno-EGL( 7406): Local Patches: 
I/Adreno-EGL( 7406): Reconstruct Branch: 
I/art     ( 5549): Explicit concurrent mark sweep GC freed 1711(61KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 554us total 28.451ms
,V/JNIHelp ( 7457): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/AudioPolicyService(  282): registerClient() client 0xb57eac20, uid 10079
,W/AudioManagerAndroid( 7406): Requires BLUETOOTH permission
I/NSApplication( 7406): Starting up...
,W/ActivityThread( 7457): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7457): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19e9a655: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7457): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7457): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7457): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  953): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7496 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7457): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7457): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  953): Process com.google.android.music:main (pid 7242) has died
,D/NativeLibraryUtils( 7457): Install completed successfully. count=14 extracted=0
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7525 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 7195:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_7195/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Killing 7219:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/ResourcesManager( 7525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_7219/cgroup.procs: No such file or directory
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=1561213720
I/ActivityManager(  953): Killing 7106:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10036/pid_7106/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7550 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.572ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.008ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.636ms
,I/art     ( 7457): CheckpointMarkThreadRoots callback created = 0xb042ff30
,I/art     ( 7457): CheckpointMarkThreadRoots callback created = 0xb042ff20
W/ResourcesManager( 7550): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b908b86:true
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7568 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7550): Create singleton instance
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/AudioManager( 7550): getMode name:com.lge.qremote
,I/AudioManager( 7550): getMode name:com.lge.qremote
,I/dex2oat ( 7574): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7589 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 114851724179; DSPS: 3854944; Offset : -2797962070
,I/dex2oat ( 7574): dex2oat took 118.737ms (threads: 4)
,I/Adreno-EGL( 7457): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7457): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7457): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7457): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7457): Remote Branch: 
I/Adreno-EGL( 7457): Local Patches: 
I/Adreno-EGL( 7457): Reconstruct Branch: 
,I/art     (  953): Explicit concurrent mark sweep GC freed 18033(858KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.419ms total 211.719ms
,D/UEI.SmartControl( 7568): Quickset Services start...
,I/UEI.SmartControl( 7568): Manufacture = LGE
D/UEI.SmartControl( 7568): File observer start...
E/UEI.SmartControl( 7568): IR Port is disabled: false
D/UEI.SmartControl( 7568): Starting file observer...
D/UEI.SmartControl( 7568): Extracting JNI libs...
D/UEI.SmartControl( 7568): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7568): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7568): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7568): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7568): --- Selecting new region: 2
I/UEI.SmartControl( 7568): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7568): Platform has CIR...
D/UEI.SmartControl( 7568): NO CIR support, need to check package...
I/UEI.SmartControl( 7568): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7568): QS Service created
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/UEI.SmartControl( 7568): QS start get config
,D/UEI.SmartControl( 7568): Loading JNI Libs...
,D/UEI.SmartControl( 7568):  configuring local db...
I/Gmail   ( 7589): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7589): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7589): Error finding the version of the Email provider.....
E/Gmail   ( 7589): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7589): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7589): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7589): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7589): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7589): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7589): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7589): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7589): We do not support migrating this version of the Email provider.
I/Gmail   ( 7589): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  953): Killing 7281:com.lge.email/u0a21 (adj 15): empty #11
,D/UEI.SmartControl( 7568):  ---- Has DB8: true
,D/UEI.SmartControl( 7568): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7568): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7568): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7568): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7568): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7568): IrrcClient ++ 
D/irrcClient( 7568): getIrrcService ++ 
,D/irrcClient( 7568): getIrrcService -- 
D/irrcClient( 7568): IrrcClient -- 
W/irrc_jni( 7568): IRRCPlayer_nativeInit -- 
W/libprocessgroup(  953): failed to open /acct/uid_10021/pid_7281/cgroup.procs: No such file or directory
W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/UEI.SmartControl( 7568): Device manager: loading config....
,D/UEI.SmartControl( 7568): Services init done
D/WearableService( 1735): callingUid 10006, callindPid: 1735
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5686): Restart initialization of location
I/Gmail   ( 7589): Observing account changes for notifications
,D/UEI.SmartControl( 7568): QS Service init finished
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7568): QS Service version name: 0.1.73
D/UEI.SmartControl( 7568): QS Service version code: 1073
D/UEI.SmartControl( 7568): Service requested: Control
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7568): Config is loaded...
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1735): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UEI.SmartControl( 7568): Request IControl service: devices are loaded...
,I/WVCdm   (  282): CdmEngine::OpenSession
D/UEI.SmartControl( 7568):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7568): Notify AllClients services are ready: 0
I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7643 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7568): -----IControl: 11
,W/GCoreFlp( 1735): No location to return for getLastLocation()
D/UEI.SmartControl( 7568): Caller: com.lge.qremote
W/FusedLocationProvider( 1735): location=null
D/UEI.SmartControl( 7568): ------------ IControl registerCallback...
D/UEI.SmartControl( 7568): Internal service binding...
I/UEI.SmartControl( 7568): Registering callback...
D/UEI.SmartControl( 7568): -----IControl: 19
D/UEI.SmartControl( 7568): Caller: com.lge.qremote
I/UEI.SmartControl( 7568): Registering Services Ready callback...
I/UEI.SmartControl( 7568): Notify client services are ready...
,D/UEI.SmartControl( 7568): -----IControl: 8
D/UEI.SmartControl( 7568): Caller: com.lge.qremote
I/ActivityManager(  953): Killing 7345:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Gmail   ( 7589): notifyAccountChanged
,I/Gmail   ( 7589): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7589): getAccountsCursor
I/Gmail   ( 7589): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7589): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7589): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  953): Killing 7315:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_7345/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_7315/cgroup.procs: No such file or directory
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicWidget( 2630): mDelayedStopHandler : unbind
,I/MusicBrowser( 2015): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2015): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2015): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/WeatherService( 2715): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:12:0
D/WeatherService( 2715): 2 : TimeTick Intent And Screen On
D/WeatherService( 2715): 2 : SDK version : 21
W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/MusicBrowser( 2015): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2015): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdateStart : false
D/MusicBrowser( 2015): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
,D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2715): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2715): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2715): 2 : Fixed theme : optimus
D/WeatherReflect( 2715): 2 : Map key string is -2
I/MusicBrowser( 2015): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2015): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  953):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@23cf07f1com.lge.music.MediaPlaybackService$6@28f7ffd6
D/MusicBrowser( 2015): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
D/lim     ( 2715): 2 : time = 15:12
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/WeatherReflect( 2715): Model Name : LG-D722
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/WeatherTheme( 2715): 2 : Different view - status_min_formatted : 11 != 12
D/WeatherTheme( 2715): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2715): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/MusicBrowser( 2015): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@34486b14
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/[SystemUI]Clock( 1374): called onTimeUpdated()
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2715): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/MusicBrowser( 2015): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/MusicBrowser( 2015): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2015): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2015): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2015): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2015): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2015): [MediaPlaybackService.java:6706:stop()] oooooo 
D/Weather4x2_optimus( 2715): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2715): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2715): forecast size is 0
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/MediaPlayer[Native]( 2015): reset
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2715): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2715): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2715): setTouchIntent, appWidgetId: 2
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/Theme_WeatherAncestor_optimus( 2715): url is : null
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2715): 2 : update view, appWidgetId: 2
D/WeatherService( 2715): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:12:0
,V/MediaPlayer[Native]( 2015): setListener
V/MediaPlayer[Native]( 2015): disconnect
V/MediaPlayer[Native]( 2015): destructor
,V/AudioFlinger(  282): releasing 19 from 2015 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2015): disconnect
D/MusicBrowser( 2015): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2015): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2015): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2015): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2015): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2015): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2015): [SmartShareManagerClient] unregisterListener: 923750999
W/SmartShareClient( 2015): [SmartShareManagerClient] unregisterListener invalid listener: 923750999
I/SmartShareClient( 2015): [SmartShareManagerClient] terminate service: 2015/MediaPlaybackService/861383002
,D/Finsky  ( 7643): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
E/HomeCloudIF( 2015): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2015): [SmartShareManagerClient] unbindService context:android.app.Application@22e6c144
V/CloudHub( 2015): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2015): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2015): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2015): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2015): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/Gmail   ( 7589): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CloudHub( 2015): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29982
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/WVCdm   (  282): CdmEngine::CloseSession
,D/Finsky  ( 7643): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7643): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7643): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7643): com.android.vending: cancel(-1050172287) by com.android.vending
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  282): PrepareKeyRequest: nonce=1380234497
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/Finsky  ( 7643): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7643): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Ads     ( 7643): Skipping gmscore version check
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@961cec5 on behalf of 7643
I/ActivityManager(  953): Killing 7386:com.lge.drmservice/u0a51 (adj 15): empty #11
D/Finsky  ( 7643): [973] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/libprocessgroup(  953): failed to open /acct/uid_10051/pid_7386/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7550): getMode name:com.lge.qremote
,I/NotificationManager(  953): android: cancelAsUser(2) by android
I/AudioManager( 7550): getMode name:com.lge.qremote
D/Finsky  ( 7643): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/CheckinService( 5686): Checkin interval check for package: unspecified last checkin: 1455113483304 min interval config: 0 actual interval: 37248
,D/LocationInitializer( 5686): Restart initialization of location
,D/Finsky  ( 7643): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1735): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7550): getMode name:com.lge.qremote
W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
W/ContextImpl( 3584): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/libc-netbsd( 7643): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7643): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7643): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7643): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 7550): getMode name:com.lge.qremote
,I/AudioManager( 7550): getMode name:com.lge.qremote
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7643): propertyValue:false
I/AudioManager( 7550): getMode name:com.lge.qremote
,I/ActivityManager(  953): Killing 7406:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10079/pid_7406/cgroup.procs: No such file or directory
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
I/Adreno-EGL( 7457): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7457): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7457): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7457): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7457): Remote Branch: 
I/Adreno-EGL( 7457): Local Patches: 
I/Adreno-EGL( 7457): Reconstruct Branch: 
,I/Adreno-EGL( 7457): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7457): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7457): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7457): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7457): Remote Branch: 
I/Adreno-EGL( 7457): Local Patches: 
I/Adreno-EGL( 7457): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5686): Classify the device as Phone.
,D/libc-netbsd( 5686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5686): propertyValue:false
D/libc-netbsd( 5686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5686): Sending checkin request (9715 bytes)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 5686): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5686): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5686): Classify the device as Phone.
,I/CheckinTask( 5686): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5686): Checking schedule, now: 1455113523631 next: 1455640772626
I/CheckinService( 5686): active receiver: disabled
,I/CheckinService( 5686): Checking schedule, now: 1455113523666 next: 1455640772626
I/CheckinService( 5686): active receiver: disabled
,D/CheckinService( 5686): Recording last checkin time for package unspecified as 1455113523677
,V/SetupWizard( 7364): Connected to Gservices successfully
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  953): Explicit concurrent mark sweep GC freed 21517(1032KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.141ms total 150.374ms
,I/GAv4-SVC( 5686): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 7589): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 7568): Internal timer expired: 1
,I/ActivityManager(  953): Killing 7525:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  953): Killing 7496:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  953): failed to open /acct/uid_10086/pid_7525/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_10048/pid_7496/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1830): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  953): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
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
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationManager( 6883): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7775 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7775): onCreate
,W/AppUp4:DB( 7775):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7775):  setFingerPrint start
,I/AppUp4:DB( 7775):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7775):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7775):  SDK version = 0
I/AppUp4:DB( 7775):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7775): AppBoxApplication onCreate()
I/NotificationService(  953): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  953): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/AppUp4:CustModeStarterReceiver( 7775): onReceive
I/AppUp4:CustModeStarterReceiver( 7775): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7775): Context : android.app.ReceiverRestrictedContext@48d1505
D/AppUp4:CustFacade( 7775): isCustomizationCompleted : false
V/BackupManagerService(  953): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  953): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@234efbaf
D/AppUp4:CustFacade( 7775): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7775): begin check event
I/AppUp4:CustModeStarterReceiver( 7775): Event For Nothing, skip.
W/ResourcesManager(  953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7797 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourceType(  953): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  953): Process com.android.vending (pid 7643) has died
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7797): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/ResourcesManager( 7797): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LocationProviderProxy(  953): applying state to connected service
,I/AppConfig( 7797): Total System Memory = 906309632
,I/GalleryUtils( 7797): Application Heap = 96 MB
I/AppConfig( 7797): App Tier : NOT_DEF
D/SystemHelper( 7797): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7817 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7817): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/SystemConfig( 7817): BUILD Country: EU
I/SystemConfig( 7817): BUILD Operator: OPEN
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7842 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 2015:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  282): 2015 died, releasing its sessions
V/AudioFlinger(  282):  pid 1752 @ 0
V/AudioFlinger(  282):  pid 3192 @ 1
V/AudioFlinger(  282):  pid 3192 @ 2
,W/libprocessgroup(  953): failed to open /acct/uid_10028/pid_2015/cgroup.procs: No such file or directory
,I/SystemConfig( 7817): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7817): existFile = false
I/SystemConfig( 7817): canReadFile = false
I/SystemConfig( 7817): systemFeature RCS result false
D/SystemConfig( 7817): refreshRcsSupport() :false
I/LockScreenSettings( 7842): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7842): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7842): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7842): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7842): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7842): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7869 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 7589:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10053/pid_7589/cgroup.procs: No such file or directory
,W/ResourcesManager( 7869): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1946): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7901 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1946): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,I/ActivityManager(  953): Killing 7364:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10038/pid_7364/cgroup.procs: No such file or directory
,D/Finsky  ( 7901): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 7901): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7901): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7901): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7901): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3221): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3221): created cursor android.database.sqlite.SQLiteCursor@3d03401a on behalf of 7901
D/Finsky  ( 7901): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7901): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7901): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7901): Skipping gmscore version check
D/PackageBroadcastService( 5686): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5686): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7901): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5686): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 5686): Explicit concurrent mark sweep GC freed 41458(2MB) AllocSpace objects, 22(352KB) LOS objects, 25% free, 13MB/18MB, paused 837us total 101.279ms
,W/SQLiteConnectionPool( 5686): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 5686): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5686): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  953): Killing 7568:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7550): android.os.DeadObjectException
,W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_7568/cgroup.procs: No such file or directory
W/ActivityManager(  953): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7550): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7550): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7550): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7550): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7550): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7550): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7550): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7550): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7550): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7550): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7550): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7550): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7550): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7550): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7550): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7550): android.os.DeadObjectException
W/System.err( 7550): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7550): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7550): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7550): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7550): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7550): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7550): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7550): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7550): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7550): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7550): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7550): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7550): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7550): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7550): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7968 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7968): Quickset Services start...
,I/UEI.SmartControl( 7968): Manufacture = LGE
,D/UEI.SmartControl( 7968): File observer start...
E/UEI.SmartControl( 7968): IR Port is disabled: false
D/UEI.SmartControl( 7968): Starting file observer...
D/UEI.SmartControl( 7968): Extracting JNI libs...
D/UEI.SmartControl( 7968): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7968): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7968): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7968): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7968): --- Selecting new region: 2
,I/UEI.SmartControl( 7968): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7968): Platform has CIR...
,D/UEI.SmartControl( 7968): NO CIR support, need to check package...
I/UEI.SmartControl( 7968): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7968): QS Service created
E/UEI.SmartControl( 7968): QS start get config
,D/UEI.SmartControl( 7968): Loading JNI Libs...
,D/UEI.SmartControl( 7968):  configuring local db...
D/UEI.SmartControl( 7968):  ---- Has DB8: true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7968): QS start statue = true Error code = 0
D/UEI.SmartControl( 7968): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7968): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7968): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7968): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7968): IrrcClient ++ 
D/irrcClient( 7968): getIrrcService ++ 
D/irrcClient( 7968): getIrrcService -- 
D/irrcClient( 7968): IrrcClient -- 
W/irrc_jni( 7968): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7968): Services init done
I/UEI.SmartControl( 7968): Device manager: loading config....
D/UEI.SmartControl( 7968): QS Service init finished
D/UEI.SmartControl( 7968): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7968): QS Service version code: 1073
D/UEI.SmartControl( 7968): Config is loaded...
,D/UEI.SmartControl( 7968): Service requested: Control
D/UEI.SmartControl( 7968): -----IControl: 11
I/ActivityManager(  953): Killing 7457:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
D/UEI.SmartControl( 7968): Caller: com.lge.qremote
D/UEI.SmartControl( 7968): ------------ IControl registerCallback...
I/UEI.SmartControl( 7968): Registering callback...
D/UEI.SmartControl( 7968): -----IControl: 19
D/UEI.SmartControl( 7968): Caller: com.lge.qremote
I/UEI.SmartControl( 7968): Registering Services Ready callback...
I/UEI.SmartControl( 7968): Notify client services are ready...
D/UEI.SmartControl( 7968): -----IControl: 8
D/UEI.SmartControl( 7968): Caller: com.lge.qremote
,D/UEI.SmartControl( 7968):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7968): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7968): Internal service binding...
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_7457/cgroup.procs: No such file or directory
,I/AudioManager( 7550): getMode name:com.lge.qremote
I/AudioManager( 7550): getMode name:com.lge.qremote
,I/AudioManager( 7550): getMode name:com.lge.qremote
,D/charger_monitor(  493): init target 500000
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/charger_monitor(  493): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController(  953): battery changed pluggedType: 2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  953): Killing 6883:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10061/pid_6883/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7968): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 134852918860; DSPS: 4510343; Offset : -2797957886
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{29b66ce4 type 2 when 148035 com.google.android.gms} when 148035
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 39449(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 13MB/22MB, paused 1.336ms total 102.892ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1735): Vacuum at: now=1455113552523 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  953): ALS enabled for SRE
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29200 ms ago)
,D/qdlights(  953): set_light_backlight: 254
,D/qdlights(  953): set_light_backlight: 251
D/qdlights(  953): set_light_backlight: 248
,D/qdlights(  953): set_light_backlight: 244
,D/qdlights(  953): set_light_backlight: 241
,D/qdlights(  953): set_light_backlight: 238
,D/qdlights(  953): set_light_backlight: 234
,D/qdlights(  953): set_light_backlight: 231
,D/qdlights(  953): set_light_backlight: 228
,D/qdlights(  953): set_light_backlight: 224
,D/qdlights(  953): set_light_backlight: 221
,D/qdlights(  953): set_light_backlight: 218
,D/qdlights(  953): set_light_backlight: 214
,D/qdlights(  953): set_light_backlight: 211
,D/qdlights(  953): set_light_backlight: 208
,D/qdlights(  953): set_light_backlight: 204
,D/qdlights(  953): set_light_backlight: 201
,D/qdlights(  953): set_light_backlight: 198
,D/qdlights(  953): set_light_backlight: 194
,D/qdlights(  953): set_light_backlight: 191
,D/qdlights(  953): set_light_backlight: 188
,D/qdlights(  953): set_light_backlight: 184
,D/qdlights(  953): set_light_backlight: 181
,D/qdlights(  953): set_light_backlight: 178
,D/qdlights(  953): set_light_backlight: 174
,D/qdlights(  953): set_light_backlight: 171
,D/qdlights(  953): set_light_backlight: 168
,D/qdlights(  953): set_light_backlight: 164
,D/qdlights(  953): set_light_backlight: 161
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  953): set_light_backlight: 158
,D/qdlights(  953): set_light_backlight: 154
,D/qdlights(  953): set_light_backlight: 151
,D/qdlights(  953): set_light_backlight: 148
,D/qdlights(  953): set_light_backlight: 144
,D/qdlights(  953): set_light_backlight: 141
,D/qdlights(  953): set_light_backlight: 138
,D/qdlights(  953): set_light_backlight: 134
,D/qdlights(  953): set_light_backlight: 131
,D/qdlights(  953): set_light_backlight: 128
,D/qdlights(  953): set_light_backlight: 124
,D/qdlights(  953): set_light_backlight: 121
,D/qdlights(  953): set_light_backlight: 118
,D/qdlights(  953): set_light_backlight: 114
,D/qdlights(  953): set_light_backlight: 111
,D/qdlights(  953): set_light_backlight: 108
,D/qdlights(  953): set_light_backlight: 104
,D/qdlights(  953): set_light_backlight: 101
,D/qdlights(  953): set_light_backlight: 98
,D/qdlights(  953): set_light_backlight: 94
,D/qdlights(  953): set_light_backlight: 91
,D/qdlights(  953): set_light_backlight: 88
,D/qdlights(  953): set_light_backlight: 84
,D/qdlights(  953): set_light_backlight: 81
,D/qdlights(  953): set_light_backlight: 78
,D/qdlights(  953): set_light_backlight: 74
,D/qdlights(  953): set_light_backlight: 71
,D/qdlights(  953): set_light_backlight: 68
,D/qdlights(  953): set_light_backlight: 64
,D/qdlights(  953): set_light_backlight: 61
,D/qdlights(  953): set_light_backlight: 58
,D/qdlights(  953): set_light_backlight: 54
,D/qdlights(  953): set_light_backlight: 51
,D/qdlights(  953): set_light_backlight: 48
,D/qdlights(  953): set_light_backlight: 44
,D/qdlights(  953): set_light_backlight: 41
,D/qdlights(  953): set_light_backlight: 38
,D/qdlights(  953): set_light_backlight: 34
,D/qdlights(  953): set_light_backlight: 31
,D/qdlights(  953): set_light_backlight: 28
,D/qdlights(  953): set_light_backlight: 24
,D/qdlights(  953): set_light_backlight: 21
,D/qdlights(  953): set_light_backlight: 18
,D/qdlights(  953): set_light_backlight: 14
,D/qdlights(  953): set_light_backlight: 11
,D/qdlights(  953): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 154853591560; DSPS: 5165725; Offset : -2797958187
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  953): ALS enabled for SRE
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36193 ms ago)
I/PowerManagerService(  953): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  953): ALS enabled for SRE
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36206 ms ago)
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  953): Sleeping (uid 1000)...
D/LPWGController(  953): [updateScreenState] screen on = false
D/LPWGController(  953): disable proximity sensor
,D/LPWGController(  953): enable proximity sensor
I/SensorManager(  953): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@30a79105] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  953): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  953): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  953): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  953): activate: handle is 48, enable
V/sensors_hal_Ctx(  953): activate sensors is 1400000000000
D/sensors_hal_Thresh(  953): enable: handle=48
I/sensors_hal_SAM(  953): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  953): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  953): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  953): enable: Received response: 0
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36249 ms ago)
I/Adreno-EGL(  953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  953): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  953): Build Date: 03/02/15 Mon
I/Adreno-EGL(  953): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  953): Remote Branch: 
I/Adreno-EGL(  953): Local Patches: 
I/Adreno-EGL(  953): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1058 us)
,I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  953): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  953): processInd: handle 48, count=1
V/sensors_hal_Thresh(  953): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  953): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  953): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  953): poll: count: 256
I/sensors_hal_Ctx(  953): poll: released wakelock sensor_ind
D/sensors_hal_Util(  953): waitForResponse: timeout=0
D/LPWGController(  953): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  953): current mode = 1  value = 1 1
I/LPWGController(  953): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  953): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  953): set_light_backlight: 0
,I/SensorManager(  953): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  953): activate: handle is 46, disable
,V/sensors_hal_Ctx(  953): activate sensors is 1000000000000
D/sensors_hal_LP2(  953): enable: handle=46
D/sensors_hal_LP2(  953): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  953): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  953): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  953): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  953): Display changed displayId=0
,D/DSDPConnection( 1752): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  953): Excessive delay in setPowerMode(): 187ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  953): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/WifiServerServiceExt(  953): sendKtScanInterval  mRtspPlay : false
I/WifiServerServiceExt(  953): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 953
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
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
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1830): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1806): lockStatus = 0
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
D/NfcService( 1788): Discovery configuration equal, not updating.
D/Ulp_jni (  953): JNI:system_update. Event-0
D/SplitWindow(  953): check instance of lgWin Window{2b6e5c68 u0 SearchPanel}
,D/InputDispatcher(  953): Window went away: Window{330da908 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:12:41
,D/WeatherService( 2715): 2 : ACTION screen on
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:12:41
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): ACTION_SCREEN_ON
D/AppCleanupService( 4090): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 953
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
,D/WifiController(  953): CMD_SCREEN_OFF 
D/WifiController(  953): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1830): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1806): clear
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
I/LEDService( 1806): updateLightsLocked : turn on led
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
,I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
I/ActivityManager(  953): Process com.android.contacts (pid 7817) has died
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,E/NxpNfcJni( 1788): getReconnectState = 0x0
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
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
,I/Sensors (  429): sns_pwr.c(301):releasing wakelock
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/art     (  953): Explicit concurrent mark sweep GC freed 46342(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 5.719ms total 163.373ms
,D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:12:42
D/WeatherService( 2715): 2 : ACTION screen off
D/WeatherService( 2715): 2 : TimeTick Receiver Unregister
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:12:42
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): ACTION_SCREEN_OFF
D/AppCleanupService( 4090): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4090): AppUsageStatsSaveTask
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{3e953881 type 2 when 162069 com.android.systemui} when 162069
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1752): getCallState : 0
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 174854274574; DSPS: 5821108; Offset : -2797975203
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=294030630, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{6afdd67 type 2 when 182964 android} when 182964
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=294030630 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  493): init target 500000
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{1300d714 type 2 when 188128 com.google.android.gms} when 188128
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 6704 seconds from now (1455113592573)
,D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
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
,I/System.out( 1735): propertyValue:false
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  953): android: cancelAsUser(2) by android
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 194855047222; DSPS: 6476493; Offset : -2797965651
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 214855812995; DSPS: 7131878; Offset : -2797962582
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 234856489082; DSPS: 7787260; Offset : -2797958169
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  493): init target 500000
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 254857172772; DSPS: 8442643; Offset : -2797976252
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 274857844430; DSPS: 9098025; Offset : -2797976060
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5470): TAP version 13
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # multiplex can send data
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 1 String should be length:200
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # enqueue and run in order
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 2 firstPromise setTimeout
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 3 firstPromise result
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 4 firstPromise testValue
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 5 secondPromise setTimeout
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 6 secondPromise result
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 7 secondPromise testValue
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 8 thirdPromise in promise
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 9 thirdPromise result
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 10 thirdPromise testValue
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # basic
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 11 sane
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # another
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 12 sane
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 13 should be equal
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 14 null
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 15 (unnamed assert)
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 16 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 17 should not throw
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 18 (unnamed assert)
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 19 (unnamed assert)
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 20 should not throw
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 21 should be equal
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 22 should be equal
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 23 should be equal
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # failed to get mobile documents path
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 24 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 25 should be equal
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 26 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 27 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # #init should register the networkChanged event
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 28 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #startBroadcasting should throw on null device name
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 29 should throw
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 30 should throw
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 31 should throw
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 32 should throw
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #startBroadcasting should throw on negative port
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 33 should throw
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # #startBroadcasting should throw on too large port
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 34 should throw
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 35 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 36 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 37 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 38 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 39 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 40 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 41 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 42 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 43 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 44 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 45 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 46 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 47 should be equal
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 48 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 49 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 50 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 51 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 52 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 53 should be equal
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #start should fail if called twice in a row
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 54 specific error should be received
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 55 specific error should be returned
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 56 error should be null
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 57 error should be null
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 58 error should be null
I/jxcore-log( 5470): 
I/jxcore-log( 5470): ok 59 error should be null
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 60 error should be null
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 61 error should be null
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): ok 62 specific error should be returned
I/jxcore-log( 5470): 
I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5470): 
,I/jxcore-log( 5470): # teardown
I/jxcore-log( 5470): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21040cc added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113697719.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113697719.5470","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113697719.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113697719.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113697719.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113697719.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
,D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6983615c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6983615c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113697719.5470, mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/bt-btif ( 1990): BTA_JvCreateRecordByUser
D/LGWifiP2pService(  953): add a new client
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/jxcore-log( 5470): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
,D/LGBluetoothServiceAdapter( 1990): [BTUI] createSocketChannel FD=87 mFd=85
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
I/bt-btif ( 1990): BTA_JvRfcommStartServer
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
D/LGWifiP2pService(  953): discovery change broadcast true
D/LGWifiP2pService(  953): InactiveState{ when=-19ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-19ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5470): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
I/wpa_supplicant( 2757): p2p0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  953): remove client information from framework
D/WfdsMonitor( 1806): Event [CTRL-EVENT-SCAN-STARTED ]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/LGWifiP2pService(  953): InactiveState{ when=-13ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36669db8 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
,D/LGWifiP2pService(  953): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113697942.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113697942.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113697942.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1990): [BTUI] createSocketChannel FD=88 mFd=87
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113697942.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113697942.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113697942.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113697942.5470, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/jxcore-log( 5470): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8e9d2a60 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1990): BTA_JvDeleteRecord
I/bt-btif ( 1990): BTA_JvRfcommStopServer
D/LGWifiP2pService(  953): P2pEnabledState{ when=-5ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8e9d2a60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  953): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
,D/LGWifiP2pService(  953): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/LGWifiP2pService(  953): InactiveState{ when=-4ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5470): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Adverti,se TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3dd64 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698030.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698030.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698030.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698030.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698030.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698030.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bc43cb6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bc43cb6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698030.5470, mode: WIFI
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  953): discovery change broadcast true
I/jxcore-log( 5470): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
I/bt-btif ( 1990): BTA_JvDeleteRecord
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/bt-btif ( 1990): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.interna,l.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/LGWifiP2pService(  953): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
I/jxcore-log( 5470): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23936bd0 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698080.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698080.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698080.5470, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698080.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698080.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698080.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@557ef56c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@557ef56c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698080.5470, mode: WIFI
D/LGWifiP2pService(  953): discovery change broadcast true
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5470): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
I/bt-btif ( 1990): BTA_JvDeleteRecord
I/bt-btif ( 1990): BTA_JvRfcommStopServer
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): remove client information from framework
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
I/jxcore-log( 5470): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c8b74fc added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698132.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698132.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698132.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698132.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698132.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698132.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@77e64970 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@77e64970 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698132.5470, mode: WIFI
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5470): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
,I/io.jxcore.node.ConnectionHelper( 5470): stop
D/LGWifiP2pService(  953): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
I/bt-btif ( 1990): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
I/bt-btif ( 1990): BTA_JvRfcommStopServer
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  953): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_,STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
I/jxcore-log( 5470): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1098e4e8 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698183.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698183.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698183.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698183.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698183.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698183.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4a4d4b64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4a4d4b64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698183.5470, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  953): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5470): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
I/bt-btif ( 1990): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1990): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
D/LGWifiP2pService(  953): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothConnector( 5470): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/LGWifiP2pService(  953): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5470): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178b6794 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btc,onnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698237.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698237.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698237.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698237.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698237.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698237.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7e0d31e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7e0d31e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698237.5470, mode: WIFI
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/io.jxcore.node.ConnectionHelper( 5470): start: OK
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  953): discovery change broadcast true
I/jxcore-log( 5470): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
I/bt-btif ( 1990): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
I/bt-btif ( 1990): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/LGWifiP2pService(  953): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/LGWifiP2pService(  953): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5470): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
D/LGWifiP2pService(  953): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms ,what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14816900 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698292.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698292.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
,I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698292.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698292.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698292.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698292.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b296e22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2b296e22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698292.5470, mode: WIFI
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  953): discovery change broadcast true
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 5470): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
I/bt-btif ( 1990): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
I/bt-btif ( 1990): BTA_JvRfcommStopServer
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/LGWifiP2pService(  953): remove client information from framework
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successf,ully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5470): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c14152c added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth,.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698348.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698348.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698348.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698348.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698348.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698348.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7041e71e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7041e71e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698348.5470, mode: WIFI
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  953): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5470): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
I/bt-btif ( 1990): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
I/bt-btif ( 1990): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/LGWifiP2pService(  953): InactiveState{, when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  953): remove client information from framework
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5470): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11435818 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterP,roperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(281624935)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@12d64975
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698400.5470
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698400.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5470): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698400.5470, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): bind: Binding a new listener
I/bt-btif ( 1990): BTA_JvCreateRecordByUser
I/bt-btif ( 1990): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455113698400.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: {"pi":"F8:95:C7:87:85:54","pn":"1455113698400.5470","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455113698400.5470","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4aad5074 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4aad5074 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState add service
D/LGWifiP2pService(  953): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/io.jxcore.node.ConnectionHelper( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455113698400.5470, mode: WIFI
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5470): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 5470): 
I/wpa_supplicant( 2757): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1806): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): onServerStopped
D/LGWifiP2pService(  953): discovery change broadcast true
I/bt-btif ( 1990): BTA_JvDeleteRecord
I/bt-btif ( 1990): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5470): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5470): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5470): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery started successfully
D/LGWifiP2pService(  953): Inactive,State{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  953): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5470): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): release: No more listeners, de-initializing...
D/LGWifiP2pService(  953): remove client information from framework
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2757): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5470): setState: NOT_STARTED
D/WfdsMonitor( 1806): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5470): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 5470): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  953): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5470): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 5470): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5470): P2P device discovery stopped successfully
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5470): Service requests cleared successfully
,I/jxcore-log( 5470): # setup
I/jxcore-log( 5470): 
I/Netd    (  278): M: Get netlink event, ifname: p2p0 action: 4
,I/wpa_supplicant( 2757): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService(  953): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService(  953):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService(  953):  primary type: 3-0050F204-5
D/LGWifiP2pService(  953):  secondary type: null
D/LGWifiP2pService(  953):  wps: 128
D/LGWifiP2pService(  953):  grpcapab: 9
D/LGWifiP2pService(  953):  devcapab: 4
D/LGWifiP2pService(  953):  status: 3
D/LGWifiP2pService(  953):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService(  953):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService(  953):  primary type: 3-0050F204-5
D/LGWifiP2pService(  953):  secondary type: null
D/LGWifiP2pService(  953):  wps: 128
D/LGWifiP2pService(  953):  grpcapab: 9
D/LGWifiP2pService(  953):  devcapab: 4
D/LGWifiP2pService(  953):  status: 3
D/LGWifiP2pService(  953):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1806): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
,D/LGWifiP2pService(  953): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1806): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  953): No p2p device connected
D/LGWifiP2pService(  953): InactiveState{ when=-4ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-4ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=-4ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 294858624840; DSPS: 9753410; Offset : -2797958902
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  493): init target 500000
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 314859457696; DSPS: 10408798; Offset : -2797981606
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 334860432637; DSPS: 11064190; Offset : -2797981664
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  953): remove c3faac1
D/LocationManagerService(  953): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  953): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  953): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  953): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=294030630, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,I/ActivityManager(  953): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8171 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 440us total 63.818ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 400us total 31.175ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 398us total 32.554ms
,I/DigitalAppWidgetProvider( 8171): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8171): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@48d1505
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=294030630 [*alarm*], flags=0x0
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 354861113672; DSPS: 11719572; Offset : -2797972225
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/wpa_supplicant( 2757): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/WfdsMonitor( 1806): Event [P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5]
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService(  953):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService(  953):  primary type: null
D/LGWifiP2pService(  953):  secondary type: null
D/LGWifiP2pService(  953):  wps: 0
D/LGWifiP2pService(  953):  grpcapab: 0
D/LGWifiP2pService(  953):  devcapab: 0
D/LGWifiP2pService(  953):  status: 4
D/LGWifiP2pService(  953):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService(  953):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService(  953):  primary type: null
D/LGWifiP2pService(  953):  secondary type: null
D/LGWifiP2pService(  953):  wps: 0
D/LGWifiP2pService(  953):  grpcapab: 0
D/LGWifiP2pService(  953):  devcapab: 0
D/LGWifiP2pService(  953):  status: 4
D/LGWifiP2pService(  953):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1806): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService(  953): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  953): No p2p device connected
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 374861857309; DSPS: 12374956; Offset : -2797960750
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 394862596000; DSPS: 13030340; Offset : -2797954428
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 414863264221; DSPS: 13685722; Offset : -2797957594
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 434864012130; DSPS: 14341107; Offset : -2797972858
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 454864753321; DSPS: 14996491; Offset : -2797964376
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 474865414459; DSPS: 15651873; Offset : -2797974364
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 494866164972; DSPS: 16307257; Offset : -2797958017
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 514866908610; DSPS: 16962642; Offset : -2797975314
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 534867558342; DSPS: 17618023; Offset : -2797966894
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 554868229637; DSPS: 18273405; Offset : -2797966804
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 574868889004; DSPS: 18928787; Offset : -2797978849
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 594869617433; DSPS: 19584171; Offset : -2797982972
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 614870393416; DSPS: 20239556; Offset : -2797969747
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 634871044815; DSPS: 20894937; Offset : -2797959477
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 654871777307; DSPS: 21550321; Offset : -2797960605
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 674872536362; DSPS: 22205706; Offset : -2797962900
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 694873272969; DSPS: 22861090; Offset : -2797958716
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 714874000044; DSPS: 23516474; Offset : -2797963828
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 734874746912; DSPS: 24171859; Offset : -2797980446
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 754875401904; DSPS: 24827240; Offset : -2797966272
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 774876146636; DSPS: 25482625; Offset : -2797984219
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 794876906889; DSPS: 26138009; Offset : -2797956388
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 814877566204; DSPS: 26793391; Offset : -2797968589
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 834878365780; DSPS: 27448777; Offset : -2797962783
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 854879042855; DSPS: 28104159; Offset : -2797956756
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 874879703420; DSPS: 28759541; Offset : -2797967760
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 894880715497; DSPS: 29414934; Offset : -2797962607
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 914881466999; DSPS: 30070319; Offset : -2797973941
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 934882117982; DSPS: 30725700; Offset : -2797964087
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=294030630, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{e23a4c9 type 2 when 951965 com.android.bluetooth} when 951965
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=294030630 [*alarm*], flags=0x0
,W/bt-smp  ( 1990): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1990): Plain text(LSB ~ MSB) = b9 be 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1990): Encrypted text(LSB ~ MSB) = 7b e4 93 c5 96 0a 27 1a 50 e9 29 f6 39 13 c5 5a 
,W/bt-btm  ( 1990): Stopping oneshot timer
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 954882820838; DSPS: 31381083; Offset : -2797962744
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 974883503487; DSPS: 32036466; Offset : -2797981686
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=294030630, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{1dd897ce type 2 when 993328 com.google.android.gms} when 993328
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=294030630 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 994884226969; DSPS: 32691849; Offset : -2797960475
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1014884983055; DSPS: 33347234; Offset : -2797967145
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1034885661016; DSPS: 34002616; Offset : -2797960492
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1054886392831; DSPS: 34658000; Offset : -2797962011
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1074887065688; DSPS: 35313382; Offset : -2797959942
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1094887838754; DSPS: 35968768; Offset : -2797980334
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1114888567860; DSPS: 36624152; Offset : -2797983753
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1134889292748; DSPS: 37279535; Offset : -2797960613
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1154890428627; DSPS: 37934933; Offset : -2797984663
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1174891094192; DSPS: 38590314; Offset : -2797960201
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1194891911371; DSPS: 39245701; Offset : -2797966319
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1214892592146; DSPS: 39901083; Offset : -2797957010
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  953): User[0] Flushing usage stats to disk
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1234893587138; DSPS: 40556476; Offset : -2797969566
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1254894330671; DSPS: 41211860; Offset : -2797958194
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1274895166393; DSPS: 41867248; Offset : -2797976939
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8318): 
D/AndroidRuntime( 8318): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8318): CheckJNI is OFF
D/AndroidRuntime( 8318): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  953): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  953): Killing 5470:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  953): Skipping PackageSetting{29c3c465 com.example.hello/10317} due to missing metadata
I/WindowState(  953): WIN DEATH: Window{18e44dfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  953): Focus left window: Window{18e44dfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  953): Window went away: Window{18e44dfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/bt-btif ( 1990): BTA_JvDeleteRecord
I/bt-btif ( 1990): BTA_JvRfcommStopServer
I/ActivityManager(  953):   Force finishing activity ActivityRecord{19bae8a9 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  953): Display changed displayId=0
D/DSDPConnection( 1752): Display #0 changed.
W/ActivityManager(  953): Spurious death for ProcessRecord{2acd96ef 5470:com.test.thalitest/u0a316}, curProc for 5470: null
I/ActivityManager(  953): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  953):   Force finishing activity ActivityRecord{19bae8a9 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  953): Duplicate finish request for ActivityRecord{19bae8a9 u0 com.test.thalitest/.MainActivity t222 f}
I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 1946): Explicit concurrent mark sweep GC freed 23553(1322KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.727ms total 86.035ms
I/QCNEJ   ( 1830): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3584): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3584): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3584): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3584): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3584): 	at android.os.Handler.handleCallback(Handler.java:739)
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
W/System.err( 3584): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3584): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3584): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3584): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3584): 	at java.lang.reflect.Method.invoke(Method.java:372)
I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3584): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3584): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 5686): Explicit concurrent mark sweep GC freed 2290(152KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 1.409ms total 73.371ms
I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  953): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8350 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
I/Activity( 1880): Activity.onPostResume() called 
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     (  953): Explicit concurrent mark sweep GC freed 61203(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 3.672ms total 206.281ms
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/art     (  953): WaitForGcToComplete blocked for 193.039ms for cause Explicit
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
D/administrator(  953): Handling package changes for user 0
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/WindowManager(  953): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework](  953): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/InputDispatcher(  953): Focus entered window: Window{2a46394a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  953): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  953): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  953): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27584db4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 8350): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8350): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8350): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1374): handleShortcutListChanged...
I/[SystemUI]NavigationThemeResource( 1374): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/InputMethodManagerService(  953): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/InputMethodManagerService(  953): Got RemoteException sending setActive(false) notification to pid 5470 uid 10316
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  953): Timeline: Activity_windows_visible id: ActivityRecord{2d9c69d2 u0 com.lge.launcher2/.Launcher t221} time:1293196
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService(  953): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  953): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  953): removeObsoleteFile: deleting file=222_task.xml
I/LGEmail ( 8350): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1606): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/LGEmail ( 8350): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/art     (  953): Explicit concurrent mark sweep GC freed 7113(406KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.921ms total 382.139ms
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/AndroidRuntime( 8318): Shutting down VM
I/PackageChangeReceiver( 8350): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AppUp4:PreloadHelper( 7775): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  953): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8378 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  953): Killing 7797:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  953): failed to open /acct/uid_10023/pid_7797/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SharedPreferencesImpl( 1880): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
