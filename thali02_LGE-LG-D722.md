#### Test 50388019f33194e_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  847): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3877 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  847): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3894 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3490:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_3490/cgroup.procs: No such file or directory
I/ActivityManager(  847): Waited long enough for: ServiceRecord{3f95d7c7 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
--------- beginning of main
V/AppCleanupService( 3877): registerAlarm
,D/AppCleanupService( 3877): noticeInterval = 2678400000
D/AppCleanupService( 3877): notiDateStr = 2015-12-20 22:35:42
D/AppCleanupService( 3877): noticeStart = 2015-12-20 22:35:42
D/AppCleanupService( 3877): noticeStart = 1450647342000
D/AppUsageDbAdapter( 3877): initPreloadedAppToTheDB() : row count = 127
E/UpdateRequestReceiver( 3894): ignoring update request
E/UpdateRequestReceiver( 3894): ignoring update request
E/UpdateRequestReceiver( 3894): ignoring update request
E/UpdateRequestReceiver( 3894): ignoring update request
E/UpdateRequestReceiver( 3894): ignoring update request
E/UpdateRequestReceiver( 3894): ignoring update request
I/ActivityManager(  847): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3929 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3642:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3642/cgroup.procs: No such file or directory
D/SIMObserver( 3929): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 3929): handle ACTION_BOOT_COMPLETED
I/ActivityManager(  847): Killing 3678:com.android.managedprovisioning/u0a111 (adj 15): empty #11
D/AndroidRuntime( 3915): 
D/AndroidRuntime( 3915): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3915): CheckJNI is OFF
W/libprocessgroup(  847): failed to open /acct/uid_10111/pid_3678/cgroup.procs: No such file or directory
E/QcrilMsgTunnelAutoboot( 2305): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1780): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1780): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  847): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=3967 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 3967): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  847): Waited long enough for: ServiceRecord{1a4caed8 u0 com.lge.sizechangable.weather/.service.WeatherService}
I/MultiDex( 3967): VM with version 2.1.0 has multidex support
I/MultiDex( 3967): install
I/MultiDex( 3967): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 3915): Calling main entry com.android.commands.am.Am
I/ActivityManager(  847): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{252116bf #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{252116bf #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  847): AppWindowTokenEx init.. 
D/ContextHelper(  847): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  847): Focus left window: Window{4d3858c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3915): Shutting down VM
I/[LGHome]EVENT( 1906): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  847): check instance of lgWin Window{29e40624 u0 Starting com.example.hello}
I/ActivityManager(  847): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3990 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1906): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1965): Closing mic
I/MicrophoneInputStream( 1965): mic_close com.google.android.apps.gsa.speech.audio.u@9e4fab7
V/AudioRecord( 1965): stop()
D/AudioRecord( 1965): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb42a4000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/[LGHome]EVENT( 1906): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  847): Starting window displayed
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2284ebbb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  278): stop_input_stream: exit: status(0)
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
D/BarTransitions( 1374): draw background and invalidate : color = 15000000
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{31ef518e type 2 when 53409 com.android.providers.calendar} when 53409
D/BarTransitions( 1374): draw background and invalidate : color = 1c1a1a1a
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1965): stop()
V/AudioRecord( 1965): stop()
V/AudioRecord( 1965): stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioSystem( 3154): ioConfigChanged() event 4, ioHandle 17
,V/AudioSystem( 2711): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): releasing 16 from 1965 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem(  847): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1780): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1965): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb42a4000 exiting
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioPolicyService(  278): AudioCommandThread() waking up
I/HotwordRecognitionRnr( 1965): Hotword detection finished
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1965, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1965): Stopping hotword detection.
D/ContextHelper( 3990): convertTheme. context->name=com.example.hello themeResourceId=16973833
V/JNIHelp ( 3967): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/WebViewFactory( 3990): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3990): Time to load native libraries: 2 ms (timestamps 3635-3637)
I/LibraryLoader( 3990): Expected native library version number "",actual native library version number ""
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
W/ActivityThread( 3967): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3967): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@40efaf6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3967): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 3967): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 3967): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WebViewChromiumFactoryProvider( 3990): Binding Chromium to main looper Looper (main, tid 1) {3f4f0b5e}
I/LibraryLoader( 3990): Expected native library version number "",actual native library version number ""
I/chromium( 3990): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3990): Initializing chromium process, singleProcess=true
W/art     ( 3990): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3990): ApplicationContext is null in ApplicationStatus
W/chromium( 3990): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3990): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3990): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3990): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3990): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3990): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3990): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3990): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3990): Remote Branch: 
I/Adreno-EGL( 3990): Local Patches: 
I/Adreno-EGL( 3990): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb57e9480, uid 10030
D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37674054:true
D/NativeLibraryUtils( 3967): Install completed successfully. count=13 extracted=0
D/BluetoothAdapter( 3990): 696024938: getState() :  mService = null. Returning STATE_OFF
W/InstanceID/Rpc( 3967): Found 10006
D/FileApkUtils( 3967): Spent 85ms computing apk sha1.
D/FileApkUtils( 3967): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 3967): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 3967): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 3967): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 54056186494; DSPS: 1863016; Offset : -2808447516
W/art     ( 3990): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3967): Suspending all threads took: 29.821ms
W/AwContents( 3990): onDetachedFromWindow called when already detached. Ignoring
D/GmsModuleFndr( 3967): Beginning GMS chimera module scan
D/SystemWebViewEngine( 3990): CordovaWebView is running on device made by: LGE
,W/art     ( 3990): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3990): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 3990): Activity.onPostResume() called 
,D/OpenGLRenderer( 3990): Render dirty regions requested: true
I/OpenGLRenderer( 3990): Initialized EGL, version 1.4
D/OpenGLRenderer( 3990): Enabling debug mode 0
,D/GmsModuleFndr( 3967): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 3967): Beginning module configuration check
D/ChimeraCfgMgr( 3967): Module APKs unchanged, check complete
D/GCM     ( 3967): COMPAT: Multi user not supported
D/GCM     ( 1991): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/Atlas   ( 3990): Validating map...
D/SplitWindow(  847): check instance of lgWin Window{37592f8f u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3990): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/GCoreUlr( 3967): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1762): DispatchingService.onCreate()
D/InputDispatcher(  847): Focus entered window: Window{37592f8f u0 com.example.hello/com.example.hello.MainActivity}
I/CheckinService( 3967): Checkin interval check for package: unspecified last checkin: 1449218666795 min interval config: 0 actual interval: 56566377
,I/CheckinService( 3967): Disabling old GoogleServicesFramework version
,I/art     ( 3967): CheckpointMarkThreadRoots callback created = 0xaaf5d770
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  847): Displayed com.example.hello/.MainActivity: +1s142ms
,I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{3abf118c u0 com.example.hello/.MainActivity t220} time:54414
D/SystemUpdateService( 3967): onCreate
I/Timeline( 3990): Timeline: Activity_idle id: android.os.BinderProxy@386b971a time:54422
I/art     ( 3967): CheckpointMarkThreadRoots callback created = 0xaae47e20
,I/art     ( 3967): Background partial concurrent mark sweep GC freed 14964(1056KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 10MB/16MB, paused 10.494ms total 108.166ms
D/SystemUpdateService( 3967): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 3967): Handling intent: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1762): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 3967): Suspending all threads took: 24.393ms
D/AuthZenEventHandler( 3967): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     ( 3967): Background sticky concurrent mark sweep GC freed 138(7KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/16MB, paused 33.773ms total 67.894ms
I/SystemUpdateService( 3967): cancelUpdate (empty URL)
I/SystemUpdateService( 3967): active receiver: disabled
,I/art     ( 3967): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3967): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/NotificationManager( 3967): com.google.android.gms: cancel(2130838130) by com.google.android.gms
,W/BindingManager( 3990): Cannot call determinedVisibility() - never saw a connection for the pid: 3990
I/NotificationManager( 3967): com.google.android.gms: cancel(2130838131) by com.google.android.gms
,W/BaseAppContext( 3967): Using Auth Proxy for data requests.
I/chromium( 3990): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/CheckinService( 3967): Checking schedule, now: 1449275233532 next: 1449745915752
I/CheckinService( 3967): active receiver: disabled
D/ChimeraCfgMgr( 3967): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1762): Explicit concurrent mark sweep GC freed 14709(969KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 11MB/18MB, paused 3.922ms total 120.828ms
D/JsMessageQueue( 3990): Set native->JS mode to OnlineEventsBridgeMode
,I/AuthZen ( 3967): Fetching signing key...
,E/AndroidProtocolHandler( 3990): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/ChimeraCfgMgr( 3967): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AuthZen ( 3967): Signing key fetched successfully!
D/SystemUpdateService( 3967): onDestroy
W/BaseAppContext( 3967): Using Auth Proxy for data requests.
I/GCoreUlr( 1762): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/NotificationManager( 3967): com.google.android.gms: cancel(10436) by com.google.android.gms
W/GCoreFlp( 1762): No location to return for getLastLocation()
W/FusedLocationProvider( 3967): location=null
V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1762): Unbound from all location providers
D/a       ( 3967): Opening database auth.proximity.permit_store...
W/GCoreFlp( 1762): No location to return for getLastLocation()
W/FusedLocationProvider( 3967): location=null
D/AuthZenTransactionCache( 3967): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 3967): Clearing transaction cache
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 3967): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 3967): [KidAccountFixer] No network connection
W/Auth    ( 1991): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 3967): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 1991): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/art     ( 1991): Explicit concurrent mark sweep GC freed 5280(335KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 4.603ms total 101.505ms
,I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4104 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/GCoreUlr( 1762): DispatchingService.onDestroy()
I/GCoreUlr( 1762): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1762): Unbound from all location providers
,W/ResourcesManager( 4104): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/jxcore_app_log( 3990): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426131456
D/JX-Cordova( 3990): jxcore cordova android initializing
,W/jxcore-log( 3990): Initializing JXcore engine
,W/jxcore-log( 3990): JXcore engine is ready
W/jxcore-log( 3990): Starting JXcore engine
,I/Babel_SMS( 4104): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4104): MmsConfig.loadMmsSettings
I/Babel_SMS( 4104): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4104): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4104): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4104): MmsConfig.loadFromResources
E/Babel_SMS( 4104): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4104): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/m.example.hello( 3990): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7294]" dev="sockfs" ino=7294 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3990): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3990): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5910]" dev="sockfs" ino=5910 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3990): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3990): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3990): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[16784]" dev="sockfs" ino=16784 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/SensorManager( 4104): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4104): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4104): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4104): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4104): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4104): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4104): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4104): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4104): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4104): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4104): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4104): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4104): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4104): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4104): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4104): found sensor: Motion Accel, handle=46
,W/art     ( 4104): Suspending all threads took: 9.186ms
,W/Settings( 4104): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  847): Waited long enough for: ServiceRecord{1d30b6cb u0 com.google.android.gms/.gcm.GcmService}
I/Babel_Crash( 4104): startup - clean
I/art     ( 4104): CheckpointMarkThreadRoots callback created = 0xb042d860
I/Babel   ( 4104): deleted: false for 0
,I/art     ( 4104): CheckpointMarkThreadRoots callback created = 0xb042d850
W/jxcore-log( 3990): Platform android
W/jxcore-log( 3990): 
,W/jxcore-log( 3990): Process ARCH arm
W/jxcore-log( 3990): 
W/AudioCapabilities( 4104): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4104): Unsupported mime audio/adpcm
W/AudioCapabilities( 4104): Unsupported mime audio/g726
W/AudioCapabilities( 4104): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4104): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4104): Unsupported mime video/mjpg
I/jxcore-log( 3990): JXcore Cordova bridge is ready!
I/jxcore-log( 3990): 
W/jxcore-log( 3990): JXcore engine is started
I/Choreographer( 3990): Skipped 30 frames!  The application may be doing too much work on its main thread.
,W/VideoCapabilities( 4104): Unsupported mime video/theora
,W/AudioCapabilities( 4104): Unsupported mime audio/evrc
,W/AudioCapabilities( 4104): Unsupported mime audio/qcelp
W/VideoCapabilities( 4104): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4104): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4104): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4104): Unsupported mime audio/evrc
E/jxcore-log( 3990): >> LGE-LG-D722
E/jxcore-log( 3990): 
I/jxcore-log( 3990): Total memory 906309632
I/jxcore-log( 3990): 
I/jxcore-log( 3990): Free memory 30560256
I/jxcore-log( 3990): 
I/jxcore-log( 3990): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3990): 
I/jxcore-log( 3990): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3990): 
,W/VideoCapabilities( 4104): Unsupported mime video/mp4v-esdp
I/jxcore-log( 3990): userPath [ 'www' ]
I/jxcore-log( 3990): 
I/jxcore-log( 3990): Size 720 1196
I/jxcore-log( 3990): 
I/jxcore-log( 3990): Screen Brightness 255
I/jxcore-log( 3990): 
E/jxcore-log( 3990): Dummy Error Log.
E/jxcore-log( 3990): 
,I/VideoCapabilities( 4104): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4104): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4104): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4104): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4104): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4104): onServiceConnected
W/Babel   ( 4104): Attempted to change video mute state without an active call.
,I/NotificationManager( 4104): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  847): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4131 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 3705:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10034/pid_3705/cgroup.procs: No such file or directory
,W/CursorWrapperInner( 3746): Cursor finalized without prior close()
,I/art     (  847): Explicit concurrent mark sweep GC freed 23083(1148KB) AllocSpace objects, 9(333KB) LOS objects, 33% free, 22MB/34MB, paused 1.750ms total 196.567ms
,W/ResourcesManager( 4131): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4131): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4131): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/jxcore-log( 3990): getBuffer is called!!!!
I/jxcore-log( 3990): 
,W/System  ( 4131): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4131): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 4131): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4131): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 4131): CheckpointMarkThreadRoots callback created = 0xb042dbf0
E/YouTube MDX( 4131): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4131): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4131): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 4131): CheckpointMarkThreadRoots callback created = 0xb4958de0
,W/art     ( 4131): Suspending all threads took: 6.933ms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4131): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4178): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads946379517.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads946379517.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4178): dex2oat took 123.204ms (threads: 4)
,I/NotificationManager( 4131): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4131): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4131): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4131): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4131): Found 10006
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4131): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4228 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 4131): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  847): Killing 3726:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_3726/cgroup.procs: No such file or directory
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4228): getAccountsCursor
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4228): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4228): Observing account changes for notifications
E/Gmail   ( 4228): Error finding the version of the Email provider.....
E/Gmail   ( 4228): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4228): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4228): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4228): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4228): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4228): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4228): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4228): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4228): We do not support migrating this version of the Email provider.
I/Gmail   ( 4228): getAccountsCursor
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4228): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3fb37758 that was originally bound here
E/ActivityThread( 4228): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3fb37758 that was originally bound here
E/ActivityThread( 4228): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4228): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4228): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4228): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4228): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4228): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4228): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4228): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4228): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4228): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4228): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4228): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4228): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4228): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4228): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4228): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  847): Unbind failed: could not find connection for android.os.BinderProxy@333a046e
I/SearchBackgroundTaskFac( 1965): refreshing internal icing corpora
,I/SearchBackgroundTaskFac( 1965): Checking for language pack updates
,I/VelvetNetworkClient( 1965): Network connection not availble
I/ActivityManager(  847): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4281 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/VelvetNetworkClient( 1965): Network connection not availble
,I/VelvetNetworkClient( 1965): Network connection not availble
I/GservicesUpdateTask( 1965): Updating Gservices keys
I/UpdateIcingCorporaServi( 1965): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/Gmail   ( 4228): notifyAccountChanged
I/Gmail   ( 4228): getAccountsCursor
V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4228): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  847): Killing 3746:com.lge.cloudhub/u0a49 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10049/pid_3746/cgroup.procs: No such file or directory
,I/Gmail   ( 4228): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4228): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4228): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/art     ( 1965): Suspending all threads took: 7.501ms
V/[BNRBootReceiver]( 4281): boot receiver action = android.intent.action.BOOT_COMPLETED
V/[BNRBootReceiver]( 4281): set property sys.lge.bnrd = 1
,V/[BNRBootReceiver]( 4281): End of BootComplted IF
V/[BNRBootReceiver]( 4281): Boot Receiver Return
V/[BNRBootCompletedThread]( 4281): run
W/linker  ( 4324): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4324): BNRD > wait starting [4324-3058102400] <
E/bnrd    ( 4324): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4281): End of BNRProcess
V/[BNRBootCompletedThread]( 4281): End of BNRViaWifiProcess
,V/[BNRBootCompletedThread]( 4281): End of SpriteProcess
V/[BNRBootCompletedThread]( 4281): exit
,I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4331 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3763:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
I/art     ( 1965): WaitForGcToComplete blocked for 138.456ms for cause DisableMovingGc
I/art     ( 1965): WaitForGcToComplete blocked for 137.696ms for cause DisableMovingGc
,I/art     ( 1965): WaitForGcToComplete blocked for 139.682ms for cause DisableMovingGc
I/art     ( 1965): WaitForGcToComplete blocked for 128.834ms for cause DisableMovingGc
I/art     ( 1965): WaitForGcToComplete blocked for 126.182ms for cause DisableMovingGc
W/libprocessgroup(  847): failed to open /acct/uid_10054/pid_3763/cgroup.procs: No such file or directory
,I/NotificationManager( 1965): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/UpdateIcingCorporaServi( 1965): UpdateCorporaTask done [took 386 ms] updated apps [took 385 ms] 
,I/Gmail   ( 4228): getAccountsCursor
,V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 1965): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    (  847): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Sear,ch.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1831): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/LibraryLoader( 1965): Time to load native libraries: 5 ms (timestamps 8864-8869)
I/LibraryLoader( 1965): Expected native library version number "",actual native library version number ""
W/art     ( 1965): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/Finsky  ( 4331): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolEx,ecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/art     ( 1965): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1965): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1965): java.io.IOException: NetworkError
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1965): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1965): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHe,lper( 1965): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/Finsky  ( 4331): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4331): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4331): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4331): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3176): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3176): created cursor android.database.sqlite.SQLiteCursor@cc790be on behalf of 4331
D/Volley  ( 4331): [448] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4331): [441] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4331): Skipping gmscore version check
I/ActivityManager(  847): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4394 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  847): Killing 3784:com.lge.lgfota.permission/1000 (adj 15): empty #11
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.927ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.135ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.998ms
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3784/cgroup.procs: No such file or directory
,D/Finsky  ( 4331): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4331): [1] Libraries$2.run: Finished loading 1 libraries.
W/ResourcesManager( 4394): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/Finsky  ( 4331): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4331): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4394): [App][onCreate()] 4.40.21
,I/ActivityManager(  847): Waited long enough for: ServiceRecord{24a02067 u0 com.android.mms/.service.SwitchedService}
,D/AccountManager( 4394): setSyncFrequency
,I/ActivityManager(  847): Killing 3821:com.lge.hiddenmenu/1000 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3821/cgroup.procs: No such file or directory
,W/ContextImpl( 4394): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/WeatherAncestor( 2705): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:27:18
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:27:18
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdateStart : false
D/ReminderService( 4394): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/LocationReminderManager( 4394): [connect] Request location client connection.
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2705): 2 : buildUpdate, appWidgetId: 2
,V/UserPresentBroadcastReceiver( 1762): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/WeatherTheme( 2705): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2705): 2 : Fixed theme : optimus
,W/ContextImpl( 4394): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,D/WeatherReflect( 2705): 2 : Map key string is -2
,D/lim     ( 2705): 2 : time = 01:27
I/WeatherReflect( 2705): Model Name : LG-D722
D/WeatherTheme( 2705): 2 : exactly same view!
D/WeatherTheme( 2705): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LocationReminderManager( 4394): location cilent is connected.
,I/art     (  847): Explicit concurrent mark sweep GC freed 23576(1095KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.105ms total 146.672ms
,I/ActivityManager(  847): Killing 3840:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/LocationReminderManager( 4394): [removeAllReminders]
W/GeofencerStateMachine( 1762): Ignoring removeGeofence because network location is disabled.
,D/LocationReminderManager( 4394): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4394): [removeAllReminders] Failed to remove reminder
D/WearableService( 1762): callingUid 10006, callindPid: 1762
W/libprocessgroup(  847): failed to open /acct/uid_10069/pid_3840/cgroup.procs: No such file or directory
,E/MDM     ( 1762): [92] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/GCoreFlp( 1762): No location to return for getLastLocation()
W/GCoreFlp( 1762): No location to return for getLastLocation()
D/GCM     ( 1991): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 3967): Restart initialization of location
D/AuthorizationBluetoothService( 1991): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1991): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1991): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 3967): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4449 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     ( 1991): Explicit concurrent mark sweep GC freed 20224(1455KB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 11MB/19MB, paused 1.113ms total 66.711ms
,W/GCoreFlp( 1762): No location to return for getLastLocation()
,W/FusedLocationProvider( 1991): location=null
D/LGDMClient( 4449): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4449): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4449): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/LGDMClient( 4449): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3154): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3154): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  847): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4479 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4479): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b377caf:true
,D/BluetoothAdapter( 4479): 696024938: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4479): 696024938: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4500 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 4479): Create singleton instance
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  847): Message: 2
,D/WifiServiceImplEx(  847): setWifiEnabled: false pid=3990, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  847): setWifiEnabled: false pid=3990, uid=10030
I/jxcore-log( 3990): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 3990): 
I/jxcore-log( 3990): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3990): 
,D/UEI.SmartControl( 4500): Quickset Services start...
,I/UEI.SmartControl( 4500): Manufacture = LGE
I/AudioManager( 4479): getMode name:com.lge.qremote
D/UEI.SmartControl( 4500): File observer start...
E/UEI.SmartControl( 4500): IR Port is disabled: false
D/UEI.SmartControl( 4500): Starting file observer...
D/UEI.SmartControl( 4500): Extracting JNI libs...
D/UEI.SmartControl( 4500): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4479): getMode name:com.lge.qremote
,D/LGDMClient( 4449): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4449): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 4449): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/AudioManager( 4479): getMode name:com.lge.qremote
,D/LGDMClient( 4449): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4524 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/UEI.SmartControl( 4500): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4500): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 4500): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 4500): --- Selecting new region: 2
I/UEI.SmartControl( 4500): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 4500): Platform has CIR...
D/UEI.SmartControl( 4500): NO CIR support, need to check package...
I/UEI.SmartControl( 4500): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4500): QS Service created
E/UEI.SmartControl( 4500): QS start get config
,W/ResourcesManager( 4524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4524): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4524): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 4500): Loading JNI Libs...
,D/UEI.SmartControl( 4500):  configuring local db...
D/AndroidRuntime( 4522): 
D/AndroidRuntime( 4522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4522): CheckJNI is OFF
I/LGEmail ( 4524): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4524): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 4524): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  847): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4567 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3858:com.lge.springcleaning/1000 (adj 15): empty #11
D/UEI.SmartControl( 4500):  ---- Has DB8: true
D/UEI.SmartControl( 4500): QS start statue = true Error code = 0
,D/UEI.SmartControl( 4500): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4500): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4500): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4500): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4500): IrrcClient ++ 
D/irrcClient( 4500): getIrrcService ++ 
,D/irrcClient( 4500): getIrrcService -- 
D/irrcClient( 4500): IrrcClient -- 
W/irrc_jni( 4500): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4500): Services init done
I/UEI.SmartControl( 4500): Device manager: loading config....
,D/UEI.SmartControl( 4500): Config is loaded...
D/AndroidRuntime( 4522): Calling main entry com.android.commands.pm.Pm
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3858/cgroup.procs: No such file or directory
D/UEI.SmartControl( 4500): QS Service init finished
D/UEI.SmartControl( 4500): QS Service version name: 0.1.73
D/UEI.SmartControl( 4500): QS Service version code: 1073
D/UEI.SmartControl( 4500): Service requested: Control
,D/UEI.SmartControl( 4500): Internal service binding...
D/UEI.SmartControl( 4500): -----IControl: 11
D/UEI.SmartControl( 4500): Caller: com.lge.qremote
D/UEI.SmartControl( 4500): ------------ IControl registerCallback...
I/UEI.SmartControl( 4500): Registering callback...
D/UEI.SmartControl( 4500): -----IControl: 19
,D/UEI.SmartControl( 4500): Caller: com.lge.qremote
I/UEI.SmartControl( 4500): Registering Services Ready callback...
I/UEI.SmartControl( 4500): Notify client services are ready...
D/UEI.SmartControl( 4500): -----IControl: 8
D/UEI.SmartControl( 4500): Caller: com.lge.qremote
D/UEI.SmartControl( 4500):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4500): Notify AllClients services are ready: 0
I/ActivityManager(  847): Killing 3929:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  847): Killing 3894:com.google.android.configupdater/u0a3 (adj 15): empty #12
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3929/cgroup.procs: No such file or directory
,W/PackageSettings(  847): Skipping PackageSetting{1e8c1f54 com.test.thalitest/10316} due to missing metadata
W/libprocessgroup(  847): failed to open /acct/uid_10003/pid_3894/cgroup.procs: No such file or directory
I/ActivityManager(  847): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  847): Killing 3990:com.example.hello/u0a30 (adj 0): stop com.example.hello
,I/WindowState(  847): WIN DEATH: Window{37592f8f u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  847): Focus left window: Window{37592f8f u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  847): Window went away: Window{37592f8f u0 com.example.hello/com.example.hello.MainActivity}
W/ActivityManager(  847): Force removing ActivityRecord{3abf118c u0 com.example.hello/.MainActivity t220}: app died, no saved state
,I/ActivityManager(  847): Force stopping com.example.hello appid=10030 user=0: pkg removed
,W/ActivityManager(  847): Spurious death for ProcessRecord{1f3b85a2 3990:com.example.hello/u0a30}, curProc for 3990: null
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1762): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1867): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/System.err( 3445): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3445): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3445): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3445): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3445): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3445): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3445): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3445): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3445): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3445): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1906): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1906): [Launcher.java:776:onResume()]onResume
,D/administrator(  847): Handling package changes for user 0
,I/ActivityManager(  847): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4590 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4609 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]LGActivityUtil( 1906): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  847): Killing 4104:com.google.android.talk/u0a61 (adj 15): empty #11
I/LockScreenSettings( 4590): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_4104/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1906): [Launcher.java:929:onResume()]onResume end
I/Activity( 1906): Activity.onPostResume() called 
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2284ebbb,  pkg=WindowManager.LayoutParams
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  847): Focus entered window: Window{4d3858c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1906): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1906): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1906): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1906): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1906): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     ( 1814): CheckpointMarkThreadRoots callback created = 0xaaf21c20
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1374): handleShortcutListChanged...
I/AppUp4:AppBoxCP( 4609): onCreate
I/[LGHome]EVENT( 1906): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
,I/PhoneWindow( 1906): [setNavigationBarColor] color=0x 0
W/AppUp4:DB( 4609):  [AppBoxDatabaseHelper] construct
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/InputMethodManagerService(  847): Got RemoteException sending setActive(false) notification to pid 3990 uid 10030
I/AppUp4:DB( 4609):  setFingerPrint start
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/AppUp4:DB( 4609):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4609):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4609):  SDK version = 0
I/AppUp4:DB( 4609):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4609): AppBoxApplication onCreate()
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/ActivityManager(  847): Killing 4131:com.google.android.youtube/u0a100 (adj 15): empty #11
,I/art     ( 1814): CheckpointMarkThreadRoots callback created = 0xaaea8a00
I/HotwordRecognitionRnr( 1965): Starting hotword detection.
,I/MicrophoneInputStream( 1965): mic_starting com.google.android.apps.gsa.speech.audio.u@324fc50d
V/AudioRecord( 1965): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1965): set(): mSessionId 22
V/AudioPolicyManager(  278): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  278): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  278): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  278): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  278): adev_open_input_stream: exit
V/AudioFlinger(  278): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  278): openInput_l() created record thread: ID 23 thread 0xb42a4000
V/AudioSystem(  278): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  847): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1965): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3154): ioConfigChanged() event 3, ioHandle 23
,V/AudioSystem( 1780): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2711): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1374): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
I/Timeline( 1906): Timeline: Activity_idle id: android.os.BinderProxy@29ed18fc time:62459
I/AudioFlinger(  278): AudioFlinger's thread 0xb42a4000 ready to run
D/audio_hw_primary(  278): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
D/audio_hw_primary(  278): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioFlinger(  278): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  278): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  278): acquiring 22 from 1965, for -1
V/AudioFlinger(  278):  added new entry for 22
V/AudioRecord( 1965): start, sync event 0 trigger session 0
V/AudioRecord( 1965): mAudioRecord->start()
V/AudioFlinger(  278): RecordHandle::start()
V/AudioFlinger(  278): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  278): startInput() module primary->input primary(23)
V/AudioPolicyManager(  278): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  278): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  278): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  278): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  278): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  278): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  278): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  278): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  278): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger::PatchPanel(  278): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  278): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  278): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  278): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  278): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  278): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  278): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  278): setPar,ameters(): io 23, keyvalue hotword_active=1, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioFlinger(  278): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2284ebbb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): AudioPolicyManager::startInput() input source = 1999
V/msm8974_platform(  278): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  278): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  278): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  278): start_input_stream: usecase(7)
E/audio_hw_primary(  278): select_devices: enter and usecase(7)
V/msm8974_platform(  278): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  278): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  278): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  278): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  278): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  278): enable_snd_device: enter  144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  278): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  278): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  278): ACDB -> send_adm_topology
D/ACDB-LOADER(  278): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  278): ACDB -> send_asm_topology
D/ACDB-LOADER(  278): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  278): ACDB -> send_audtable
D/ACDB-LOADER(  278): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  278): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  278): ACDB -> send_audvoltable
D/ACDB-LOADER(  278): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  278): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  278): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  278): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  278): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  278): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  278): enable_audio_route: exit
D/audio_hw_primary(  278): select_devices: done
V/audio_hw_primary(  278): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  278): start_input_stream: exit
,D/KeyguardModel( 1374): handleShortcutListChanged...
W/libprocessgroup(  847): failed to open /acct/uid_10100/pid_4131/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Killing 4228:com.google.android.gm/u0a53 (adj 15): empty #11
I/NotificationService(  847): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  847): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  847): Explicit concurrent mark sweep GC freed 19937(1210KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.929ms total 419.280ms
,W/libprocessgroup(  847): failed to open /acct/uid_10053/pid_4228/cgroup.procs: No such file or directory
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/TaskPersister(  847): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1965): mic_started com.google.android.apps.gsa.speech.audio.u@324fc50d
I/HotwordWorker( 1965): onReady
,D/BarTransitions( 1374): draw background and invalidate : color = e8000000
D/BarTransitions( 1374): draw background and invalidate : color = e5dcdcdc
I/ActivityManager(  847): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4632 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AndroidRuntime( 4522): Shutting down VM
,W/ResourcesManager( 4632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4632): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4632): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1906): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{f74dfb u0 com.lge.launcher2/.Launcher t219} time:62847
,W/OpenGLRenderer( 1906): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1906): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/LCardEmulationManager( 1814): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1814): getDefaultRoute
I/ActivityManager(  847): Waited long enough for: ServiceRecord{109c65c5 u0 com.lge.mlt/.MltMonitorService}
,I/AppConfig( 4632): Total System Memory = 906309632
I/GalleryUtils( 4632): Application Heap = 96 MB
I/AppConfig( 4632): App Tier : NOT_DEF
D/SystemHelper( 4632): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  847): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4653 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  847): Killing 4281:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4281/cgroup.procs: No such file or directory
,W/ResourcesManager( 4653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4653): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4653): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4653): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4653): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.

```
