#### Test 50242285e132180_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 2321): Module APKs unchanged, check complete
D/GCM     ( 2321): COMPAT: Multi user not supported
D/GCM     ( 2119): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 2321): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1794): DispatchingService.onCreate()
I/CheckinService( 2321): Checkin interval check for package: unspecified last checkin: 1449484456781 min interval config: 0 actual interval: 16631747
,I/CheckinService( 2321): Disabling old GoogleServicesFramework version
D/SystemUpdateService( 2321): onCreate
D/SystemUpdateService( 2321): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AuthZen ( 2321): Handling intent: android.intent.action.BOOT_COMPLETED
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthZenEventHandler( 2321): Handling event: android.intent.action.BOOT_COMPLETED
I/art     ( 1794): Explicit concurrent mark sweep GC freed 15792(1014KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 11MB/18MB, paused 3.380ms total 106.491ms
I/SystemUpdateService( 2321): cancelUpdate (empty URL)
I/SystemUpdateService( 2321): active receiver: disabled
I/NotificationManager( 2321): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 2321): com.google.android.gms: cancel(2130838131) by com.google.android.gms
I/GCoreUlr( 1794): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/CheckinService( 2321): Checking schedule, now: 1449501088814 next: 1450011705706
I/CheckinService( 2321): active receiver: disabled
W/BaseAppContext( 2321): Using Auth Proxy for data requests.
D/AndroidRuntime( 4037): 
D/AndroidRuntime( 4037): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4037): CheckJNI is OFF
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/SystemUpdateService( 2321): onDestroy
I/AuthZen ( 2321): Fetching signing key...
I/art     ( 2119): Explicit concurrent mark sweep GC freed 6178(358KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/18MB, paused 14.400ms total 126.743ms
I/AuthZen ( 2321): Signing key fetched successfully!
W/BaseAppContext( 2321): Using Auth Proxy for data requests.
D/a       ( 2321): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 2321): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2321): Clearing transaction cache
I/art     (  861): Explicit concurrent mark sweep GC freed 14789(721KB) AllocSpace objects, 6(285KB) LOS objects, 33% free, 22MB/33MB, paused 1.896ms total 155.660ms
I/NotificationManager( 2321): com.google.android.gms: cancel(10436) by com.google.android.gms
W/GCoreFlp( 1794): No location to return for getLastLocation()
W/FusedLocationProvider( 2321): location=null
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1794): No location to return for getLastLocation()
W/FusedLocationProvider( 2321): location=null
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1794): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1794): Unbound from all location providers
W/Kids    ( 2321): [AbstractKidsOperation] Invalid device state 3
W/Auth    ( 2119): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/Kids    ( 2321): [KidAccountFixer] No network connection
D/AndroidRuntime( 4037): Calling main entry com.android.commands.am.Am
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
I/ActivityManager(  861): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/GmsCoreStatsServiceLauncher( 2321): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{2a3ae3c9 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{2a3ae3c9 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  861): AppWindowTokenEx init.. 
D/InputDispatcher(  861): Focus left window: Window{5a77ffb u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4037): Shutting down VM
D/ContextHelper(  861): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/[LGHome]EVENT( 1979): [Launcher.java:986:onPause()]onPause
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 54889693369; DSPS: 1897149; Offset : -3015731614
D/SplitWindow(  861): check instance of lgWin Window{48bfa0b u0 Starting com.example.hello}
I/ActivityManager(  861): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4085 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1979): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 2054): Closing mic
I/MicrophoneInputStream( 2054): mic_close com.google.android.apps.gsa.speech.audio.u@291dd4be
V/AudioRecord( 2054): stop()
D/AudioRecord( 2054): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
D/PersistentNotificationBroadcastReceiver( 2119): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb431e000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
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
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb431e000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4103 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/GCoreUlr( 1794): DispatchingService.onDestroy()
I/GCoreUlr( 1794): Stopping handler for UlrDispSvcFast
I/[LGHome]EVENT( 1979): [Launcher.java:5214:onStop()]onStop
V/AudioRecord( 2054): stop()
V/AudioRecord( 2054): stop()
V/AudioRecord( 2054): stop()
V/AudioFlinger(  282): releasing 16 from 2054 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 2054): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2714): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  861): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1413): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3147): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb431e000 exiting
V/AudioSystem( 1824): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 2054, calling pid 282
I/WindowStateAnimator(  861): Starting window displayed
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29310419,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1413): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1413): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1413):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1413): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1413): draw background and invalidate : color = a000000
I/GCoreUlr( 1794): Unbound from all location providers
D/BarTransitions( 1413): draw background and invalidate : color = f0e0e0e
I/HotwordRecognitionRnr( 2054): Hotword detection finished
,I/HotwordRecognitionRnr( 2054): Stopping hotword detection.
D/ContextHelper( 4085): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/ResourcesManager( 4103): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/WebViewFactory( 4085): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4085): Time to load native libraries: 2 ms (timestamps 5276-5278)
I/LibraryLoader( 4085): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4085): Binding Chromium to main looper Looper (main, tid 1) {17fdfdc1}
I/LibraryLoader( 4085): Expected native library version number "",actual native library version number ""
I/chromium( 4085): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4085): Initializing chromium process, singleProcess=true
W/art     ( 4085): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4085): ApplicationContext is null in ApplicationStatus
W/chromium( 4085): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4085): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4085): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4085): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4085): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4085): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4085): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4085): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4085): Remote Branch: 
I/Adreno-EGL( 4085): Local Patches: 
I/Adreno-EGL( 4085): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb551c800, uid 10030
D/BluetoothAdapter( 4085): 870181568: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d42c7f5:true
I/Babel_SMS( 4103): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4103): MmsConfig.loadMmsSettings
I/Babel_SMS( 4103): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4103): MmsConfig.loadFromDatabase
E/Babel_SMS( 4103): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4103): MmsConfig.loadFromResources
E/Babel_SMS( 4103): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4103): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 4085): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4085): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4085): CordovaWebView is running on device made by: LGE
D/SensorManager( 4103): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4103): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4103): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4103): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4103): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4103): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4103): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4103): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4103): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4103): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4103): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4103): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4103): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4103): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4103): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4103): found sensor: Motion Accel, handle=46
W/art     ( 4085): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4085): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 4103): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/Activity( 4085): Activity.onPostResume() called 
,W/Settings( 4103): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4103): startup - clean
D/OpenGLRenderer( 4085): Render dirty regions requested: true
I/OpenGLRenderer( 4085): Initialized EGL, version 1.4
D/OpenGLRenderer( 4085): Enabling debug mode 0
,I/art     ( 4103): CheckpointMarkThreadRoots callback created = 0xb042d7f0
D/Atlas   ( 4085): Validating map...
,D/SplitWindow(  861): check instance of lgWin Window{15731b63 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 4085): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  861): Focus entered window: Window{15731b63 u0 com.example.hello/com.example.hello.MainActivity}
,I/Babel   ( 4103): deleted: false for 0
,W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 4085): Timeline: Activity_idle id: android.os.BinderProxy@3738d76d time:55936
,I/ActivityManager(  861): Displayed com.example.hello/.MainActivity: +1s55ms
I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{22f06ace u0 com.example.hello/.MainActivity t220} time:55937
W/AudioCapabilities( 4103): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4103): Unsupported mime audio/adpcm
W/AudioCapabilities( 4103): Unsupported mime audio/g726
W/AudioCapabilities( 4103): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4103): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4103): Unsupported mime video/mjpg
W/VideoCapabilities( 4103): Unsupported mime video/theora
,W/AudioCapabilities( 4103): Unsupported mime audio/evrc
,W/AudioCapabilities( 4103): Unsupported mime audio/qcelp
W/VideoCapabilities( 4103): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4103): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 4103): Unsupported mime audio/qcelp
W/AudioCapabilities( 4103): Unsupported mime audio/evrc
W/BindingManager( 4085): Cannot call determinedVisibility() - never saw a connection for the pid: 4085
,W/VideoCapabilities( 4103): Unsupported mime video/mp4v-esdp
I/chromium( 4085): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/VideoCapabilities( 4103): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4103): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4103): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4103): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4103): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4103): onServiceConnected
,W/Babel   ( 4103): Attempted to change video mute state without an active call.
I/NotificationManager( 4103): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/JsMessageQueue( 4085): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  861): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4171 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Waited long enough for: ServiceRecord{13935127 u0 com.google.android.gms/.gcm.GcmService}
,E/AndroidProtocolHandler( 4085): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ResourcesManager( 4171): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4171): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/CursorWrapperInner( 3761): Cursor finalized without prior close()
,V/JNIHelp ( 4171): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4171): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4171): Installed default security provider GmsCore_OpenSSL
,D/jxcore_app_log( 4085): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1623086080
D/JX-Cordova( 4085): jxcore cordova android initializing
,W/jxcore-log( 4085): Initializing JXcore engine
,W/jxcore-log( 4085): JXcore engine is ready
W/jxcore-log( 4085): Starting JXcore engine
W/m.example.hello( 4085): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6314]" dev="sockfs" ino=6314 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4085): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4085): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8772]" dev="sockfs" ino=8772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4085): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4085): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4085): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20658]" dev="sockfs" ino=20658 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/ResourcesManager( 4171): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4171): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4171): CheckpointMarkThreadRoots callback created = 0xb042d5c0
E/YouTube MDX( 4171): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 4171): CheckpointMarkThreadRoots callback created = 0xb4958de0
D/libc-netbsd( 4171): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4171): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4214): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1747891035.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads1747891035.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/jxcore-log( 4085): Platform android
W/jxcore-log( 4085): 
W/jxcore-log( 4085): Process ARCH arm
W/jxcore-log( 4085): 
,I/jxcore-log( 4085): JXcore Cordova bridge is ready!
I/jxcore-log( 4085): 
,W/jxcore-log( 4085): JXcore engine is started
I/dex2oat ( 4214): dex2oat took 118.699ms (threads: 4)
,E/jxcore-log( 4085): >> LGE-LG-D722
E/jxcore-log( 4085): 
,I/jxcore-log( 4085): Total memory 906309632
I/jxcore-log( 4085): 
I/jxcore-log( 4085): Free memory 26750976
I/jxcore-log( 4085): 
I/jxcore-log( 4085): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4085): 
I/jxcore-log( 4085): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4085): 
I/jxcore-log( 4085): userPath [ 'www' ]
I/jxcore-log( 4085): 
I/jxcore-log( 4085): Size 720 1196
I/jxcore-log( 4085): 
,I/jxcore-log( 4085): Screen Brightness 255
I/jxcore-log( 4085): 
E/jxcore-log( 4085): Dummy Error Log.
E/jxcore-log( 4085): 
,I/NotificationManager( 4171): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4171): Found 10006
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  861): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4264 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 4171): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  861): Killing 3761:com.lge.cloudhub/u0a49 (adj 15): empty #11
,I/jxcore-log( 4085): getBuffer is called!!!!
I/jxcore-log( 4085): 
,W/libprocessgroup(  861): failed to open /acct/uid_10049/pid_3761/cgroup.procs: No such file or directory
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4264): getAccountsCursor
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4264): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  861): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 4264): Error finding the version of the Email provider.....
E/Gmail   ( 4264): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4264): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4264): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4264): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4264): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4264): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4264): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4264): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4264): getAccountsCursor
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4264): Observing account changes for notifications
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4264): notifyAccountChanged
,I/Gmail   ( 4264): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/VelvetNetworkClient( 2054): Network connection not availble
I/Gmail   ( 4264): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4264): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     (  861): Explicit concurrent mark sweep GC freed 15917(790KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 2.204ms total 173.708ms
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4264): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/VelvetNetworkClient( 2054): Network connection not availble
I/Gmail   ( 4264): getAccountsCursor
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityThread( 4264): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@23e99caa that was originally bound here
E/ActivityThread( 4264): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@23e99caa that was originally bound here
E/ActivityThread( 4264): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4264): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4264): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4264): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4264): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4264): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4264): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4264): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4264): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4264): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4264): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4264): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4264): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4264): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4264): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  861): Unbind failed: could not find connection for android.os.BinderProxy@29b76a68
I/ActivityManager(  861): Killing 3780:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10054/pid_3780/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4316 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/Gmail   ( 4264): getAccountsCursor
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 2054): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,V/[BNRBootReceiver]( 4316): boot receiver action = android.intent.action.BOOT_COMPLETED
V/[BNRBootReceiver]( 4316): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4316): End of BootComplted IF
V/[BNRBootReceiver]( 4316): Boot Receiver Return
V/[BNRBootCompletedThread]( 4316): run
,W/linker  ( 4334): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4334): BNRD > wait starting [4334-3058102400] <
E/bnrd    ( 4334): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4316): End of BNRProcess
,V/[BNRBootCompletedThread]( 4316): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4316): End of SpriteProcess
V/[BNRBootCompletedThread]( 4316): exit
,I/ActivityManager(  861): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4340 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  861): Killing 3801:com.lge.lgfota.permission/1000 (adj 15): empty #11
I/LibraryLoader( 2054): Time to load native libraries: 1 ms (timestamps 8927-8928)
I/LibraryLoader( 2054): Expected native library version number "",actual native library version number ""
W/art     ( 2054): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3801/cgroup.procs: No such file or directory
,W/art     ( 2054): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 4340): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/PowerService( 1905): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1413): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1413): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1413): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1413): On Skip Timer : true
,I/ActivityManager(  861): Killing 3850:com.lge.hiddenmenu/1000 (adj 15): empty #11
,D/Finsky  ( 4340): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3850/cgroup.procs: No such file or directory
,W/Settings( 4340): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4340): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4340): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3168): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3168): created cursor android.database.sqlite.SQLiteCursor@36a970a1 on behalf of 4340
D/Volley  ( 4340): [441] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4340): [448] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4340): Skipping gmscore version check
,I/ActivityManager(  861): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4398 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  861): Killing 3871:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 25.525ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 335us total 28.514ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.365ms
,W/libprocessgroup(  861): failed to open /acct/uid_10014/pid_3871/cgroup.procs: No such file or directory
D/Finsky  ( 4340): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4340): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4340): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 4398): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/Finsky  ( 4340): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4398): [App][onCreate()] 4.40.21
,I/ActivityManager(  861): Waited long enough for: ServiceRecord{3525771 u0 com.android.mms/.service.SwitchedService}
,D/AccountManager( 4398): setSyncFrequency
,W/ContextImpl( 4398): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/WeatherAncestor( 2708): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:11:34
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
D/WeatherAncestor( 2708): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:11:34
D/WeatherService( 2708): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2708): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
D/WeatherService( 2708): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2708): 2 : buildUpdate, appWidgetId: 2
D/ReminderService( 4398): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
,D/LocationReminderManager( 4398): [connect] Request location client connection.
V/UserPresentBroadcastReceiver( 1794): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/WeatherTheme( 2708): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 2708): 2 : Fixed theme : optimus
D/WeatherReflect( 2708): 2 : Map key string is -2
D/lim     ( 2708): 2 : time = 16:11
I/WeatherReflect( 2708): Model Name : LG-D722
,W/ContextImpl( 4398): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
D/WeatherTheme( 2708): 2 : exactly same view!
D/WeatherTheme( 2708): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/LocationReminderManager( 4398): location cilent is connected.
,I/ActivityManager(  861): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4434 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/LocationReminderManager( 4398): [removeAllReminders]
,W/GeofencerStateMachine( 1794): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  861): Killing 3888:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/LocationReminderManager( 4398): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4398): [removeAllReminders] Failed to remove reminder
,W/libprocessgroup(  861): failed to open /acct/uid_10069/pid_3888/cgroup.procs: No such file or directory
,D/LGDMClient( 4434): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
W/GCoreFlp( 1794): No location to return for getLastLocation()
D/LGDMClient( 4434): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/GCoreFlp( 1794): No location to return for getLastLocation()
W/ContextImpl( 4434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 4434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4434): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/LGDMClient( 4434): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  861): Killing 3916:com.lge.springcleaning/1000 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3916/cgroup.procs: No such file or directory
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,I/ActivityManager(  861): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4457 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4457): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2161535b:true
,D/BluetoothAdapter( 4457): 262911229: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4457): 262911229: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4481 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4457): Create singleton instance
,D/UEI.SmartControl( 4481): Quickset Services start...
,I/UEI.SmartControl( 4481): Manufacture = LGE
D/UEI.SmartControl( 4481): File observer start...
E/UEI.SmartControl( 4481): IR Port is disabled: false
D/UEI.SmartControl( 4481): Starting file observer...
D/UEI.SmartControl( 4481): Extracting JNI libs...
D/UEI.SmartControl( 4481): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4457): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,I/AudioManager( 4457): getMode name:com.lge.qremote
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4481): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,D/UEI.SmartControl( 4481): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4481): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,D/LGDMClient( 4434): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4434): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/AudioManager( 4457): getMode name:com.lge.qremote
,D/LGDMClient( 4434): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/UEI.SmartControl( 4481): --- Selecting new region: 2
D/LGDMClient( 4434): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
I/UEI.SmartControl( 4481): -- Running on KitKat(19) and above! JNI will be used.
V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{d7f7d09 type 2 when 55969 com.google.android.talk} when 55969
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{fc92f type 0 when 1449501095514 com.google.android.gms} when 1449501095514
D/UEI.SmartControl( 4481): Platform has CIR...
,D/UEI.SmartControl( 4481): NO CIR support, need to check package...
I/UEI.SmartControl( 4481): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4481): QS Service created
D/WearableService( 1794): callingUid 10006, callindPid: 1794
,I/iu.UploadsManager( 2321): End new media; added: 0, uploading: 0, time: 55 ms
E/UEI.SmartControl( 4481): QS start get config
E/MDM     ( 1794): [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GCM     ( 2119): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 2321): Restart initialization of location
D/AuthorizationBluetoothService( 2119): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 2119): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 2321): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/UEI.SmartControl( 4481): Loading JNI Libs...
,D/UEI.SmartControl( 4481):  configuring local db...
I/ActivityManager(  861): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4518 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/GCoreFlp( 1794): No location to return for getLastLocation()
W/FusedLocationProvider( 2119): location=null
,W/ResourcesManager( 4518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4518): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4518): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 4518): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4518): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/UEI.SmartControl( 4481):  ---- Has DB8: true
,D/UEI.SmartControl( 4481): QS start statue = true Error code = 0
D/UEI.SmartControl( 4481): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4481): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4481): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4481): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4481): IrrcClient ++ 
D/irrcClient( 4481): getIrrcService ++ 
D/irrcClient( 4481): getIrrcService -- 
D/irrcClient( 4481): IrrcClient -- 
W/irrc_jni( 4481): IRRCPlayer_nativeInit -- 
,I/ActivityManager(  861): Process com.google.android.talk (pid 4103) has died
D/UEI.SmartControl( 4481): Services init done
I/UEI.SmartControl( 4481): Device manager: loading config....
D/UEI.SmartControl( 4481): QS Service init finished
D/UEI.SmartControl( 4481): Config is loaded...
D/UEI.SmartControl( 4481): QS Service version name: 0.1.73
,D/UEI.SmartControl( 4481): QS Service version code: 1073
D/UEI.SmartControl( 4481): Service requested: Control
D/UEI.SmartControl( 4481): -----IControl: 11
D/UEI.SmartControl( 4481): Caller: com.lge.qremote
D/UEI.SmartControl( 4481): ------------ IControl registerCallback...
D/UEI.SmartControl( 4481): Internal service binding...
I/UEI.SmartControl( 4481): Registering callback...
D/UEI.SmartControl( 4481): -----IControl: 19
D/UEI.SmartControl( 4481): Caller: com.lge.qremote
I/UEI.SmartControl( 4481): Registering Services Ready callback...
I/UEI.SmartControl( 4481): Notify client services are ready...
,D/UEI.SmartControl( 4481): -----IControl: 8
D/UEI.SmartControl( 4481): Caller: com.lge.qremote
,D/UEI.SmartControl( 4481):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4481): Notify AllClients services are ready: 0
,I/PackageChangeReceiver( 4518): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  861): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4543 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 3954:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10003/pid_3954/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4566 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 3985:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3985/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4566): onCreate
,W/AppUp4:DB( 4566):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4566):  setFingerPrint start
,I/AppUp4:DB( 4566):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4566):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4566):  SDK version = 0
I/AppUp4:DB( 4566):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4566): AppBoxApplication onCreate()
,I/ActivityManager(  861): Killing 4171:com.google.android.youtube/u0a100 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10100/pid_4171/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4586 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4586): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4586): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 4586): Total System Memory = 906309632
,I/GalleryUtils( 4586): Application Heap = 96 MB
I/AppConfig( 4586): App Tier : NOT_DEF
D/SystemHelper( 4586): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  861): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4605 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4264:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10053/pid_4264/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  861): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  861): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  861): Message: 2
,D/WifiServiceImplEx(  861): setWifiEnabled: false pid=4085, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  861): setWifiEnabled: false pid=4085, uid=10030
I/jxcore-log( 4085): ****TEST TOOK:  5063  ms ****
I/jxcore-log( 4085): 
I/jxcore-log( 4085): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4085): 
I/art     (  861): Explicit concurrent mark sweep GC freed 21477(974KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.068ms total 146.752ms
,W/ResourcesManager( 4605): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4605): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4605): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4605): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4605): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 4605): BUILD Country: EU
I/SystemConfig( 4605): BUILD Operator: OPEN
,I/ActivityManager(  861): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4632 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  861): Killing 4316:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4316/cgroup.procs: No such file or directory
,I/SystemConfig( 4605): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4605): existFile = false
I/SystemConfig( 4605): canReadFile = false
I/SystemConfig( 4605): systemFeature RCS result false
D/SystemConfig( 4605): refreshRcsSupport() :false
,D/AndroidRuntime( 4623): 
D/AndroidRuntime( 4623): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4623): CheckJNI is OFF
I/LockScreenSettings( 4632): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4632): New app installed broadcast received ..
,I/LockScreenSettings( 4632): Number of installed packages  1
I/ActivityManager(  861): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4340:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10036/pid_4340/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 4650): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4650): uri : package:com.example.hello
,I/ActivityManager(  861): Killing 4398:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4398/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 2321): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2321): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4623): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  861): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  861): Killing 4085:com.example.hello/u0a30 (adj 0): stop com.example.hello
,I/WindowState(  861): WIN DEATH: Window{15731b63 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  861): Focus left window: Window{15731b63 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  861): Window went away: Window{15731b63 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  861): Skipping PackageSetting{3cbd70f com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  861): Force removing ActivityRecord{22f06ace u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  861): Spurious death for ProcessRecord{20cd7721 4085:com.example.hello/u0a30}, curProc for 4085: null
,I/ActivityManager(  861): Force stopping com.example.hello appid=10030 user=0: pkg removed
I/ActivityManager(  861): Waited long enough for: ServiceRecord{3a2ac31c u0 com.lge.mlt/.MltMonitorService}
,D/KeyguardModel( 1413): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1794): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1941): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/System.err( 3449): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3449): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3449): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3449): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3449): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3449): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3449): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3449): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3449): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3449): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2321): Module APK com.google.android.play.games already loaded
W/System.err( 3449): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3449): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1979): [Launcher.java:5203:onStart()]onStart
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/KeyguardModel( 1413): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1413): createShortcutInfo...
I/PeopleContactsSync( 2321): CP2 sync disabled
I/[SystemUI]QSlideListController( 1413): onReceive = android.intent.action.PACKAGE_REMOVED
,D/KeyguardModel( 1413): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1413): createShortcutInfo...
I/[LGHome]EVENT( 1979): [Launcher.java:776:onResume()]onResume
W/ResourceType( 1413): No package identifier when getting value for resource number 0x00000000
D/AsyncTaskServiceImpl( 2321): Submit a task: h
,W/PackageManager( 1413): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1413): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1413): createShortcutInfo...
,I/[LGHome]LGActivityUtil( 1979): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/ResourceType( 1413): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1413): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/[LGHome]EVENT( 1979): [Launcher.java:929:onResume()]onResume end
I/Activity( 1979): Activity.onPostResume() called 
D/administrator(  861): Handling package changes for user 0
D/h       ( 2321): Processing package: com.example.hello
D/KeyguardModel( 1413): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1413): createShortcutInfo...
W/ResourceType( 1413): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1413): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,W/h       ( 2321): Failed to find package com.example.hello
D/KeyguardModel( 1413): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1413): createShortcutInfo...
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29310419,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  861): Focus entered window: Window{5a77ffb u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/[LGHome]LGWallpaperInfo( 1979): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1979): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
E/Vision  ( 2321): Failed to find package com.example.hello
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1413): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1413): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1979): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1979): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1979): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/art     ( 1887): CheckpointMarkThreadRoots callback created = 0xaaf23c00
I/[LGHome]EVENT( 1979): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1979): [setNavigationBarColor] color=0x 0
I/ActivityManager(  861): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4700 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 2321): Storage manager: low false usage 1.61MB avail 2.05GB capacity 3.45GB
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.258ms
,I/art     ( 1887): CheckpointMarkThreadRoots callback created = 0xaaf490d0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.874ms
,D/KeyguardModel( 1413): handleShortcutListChanged...
,D/KeyguardModel( 1413): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1413): createShortcutInfo...
D/KeyguardModel( 1413): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1413): createShortcutInfo...
W/ResourceType( 1413): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1413): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1413): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1413): createShortcutInfo...
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.366ms
W/ResourceType( 1413): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1413): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1413): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1413): createShortcutInfo...
,W/ResourceType( 1413): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1413): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/KeyguardModel( 1413): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1413): createShortcutInfo...
D/KeyguardModel( 1413): handleShortcutListChanged...
W/InputMethodManagerService(  861): Got RemoteException sending setActive(false) notification to pid 4085 uid 10030
,W/art     ( 2321): Suspending all threads took: 29.052ms
,W/Icing   ( 2321): Received bad json for section weights override -- ignoring.
W/Icing   ( 2321): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 2321): Received bad json for section weights override -- ignoring.
,W/Icing   ( 2321): Received bad json for corpus context scoring override -- ignoring.
I/art     ( 2321): Background sticky concurrent mark sweep GC freed 20423(1771KB) AllocSpace objects, 25(400KB) LOS objects, 14% free, 12MB/14MB, paused 34.779ms total 160.440ms
I/art     ( 2321): WaitForGcToComplete blocked for 78.343ms for cause Explicit
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/HotwordRecognitionRnr( 2054): Starting hotword detection.
,I/MicrophoneInputStream( 2054): mic_starting com.google.android.apps.gsa.speech.audio.u@154372f7
V/AudioRecord( 2054): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
,V/AudioRecord( 2054): set(): mSessionId 22
I/Timeline( 1979): Timeline: Activity_idle id: android.os.BinderProxy@23df4157 time:63805
V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  282): openInput_l() created record thread: ID 23 thread 0xb384d000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  861): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioSystem( 1413): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1824): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 2714): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2054): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3147): ioConfigChanged() event 3, ioHandle 23
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29310419,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  282): openRecord() lSessionId: 22 input 23
I/AudioFlinger(  282): AudioFlinger's thread 0xb384d000 ready to run
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): getOrphanEffectChain_l session 22 index -2
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioFlinger(  282): acquiring 22 from 2054, for -1
V/AudioFlinger(  282):  added new entry for 22
V/AudioRecord( 2054): start, sync event 0 trigger session 0
V/AudioRecord( 2054): mAudioRecord->start()
V/AudioFlinger(  282): RecordHandle::start()
V/AudioFlinger(  282): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  282): startInput() module primary->input primary(23)
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  282): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  282): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  282): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  282): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  282): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  282): ThreadBase::setP,arameters() input_source=6;routing=-2147483644
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb384d000
V/AudioFlinger::PatchPanel(  282): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  282): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  282): setParameters(): io 23, keyvalue hotword_active=1, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb384d000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  282): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  282): start_input_stream: usecase(7)
E/audio_hw_primary(  282): select_devices: enter and usecase(7)
V/msm8974_platform(  282): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  282): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  282): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  282): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  282): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  282): enable_snd_device: enter  144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  282): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  282): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  282): ACDB -> send_adm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_asm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_audtable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  282): ACDB -> send_audvoltable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  282): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  282): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AFE_CAL
I/MicrophoneInputStream( 2054): mic_started com.google.android.apps.gsa.speech.audio.u@154372f7
V/audio_hw_primary(  282): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  282): start_input_stream: exit
I/NotificationService(  861): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  861): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  861): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1413): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1413): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1413): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1413):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1413): , Keyguard show=false, IME shown=false, Panel expanded=false
I/art     ( 2321): Explicit concurrent mark sweep GC freed 3929(254KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 12MB/20MB, paused 1.849ms total 124.726ms
,D/BarTransitions( 1413): draw background and invalidate : color = ef000000
D/BarTransitions( 1413): draw background and invalidate : color = efe6e6e6
W/BaseAppContext( 2321): Using Auth Proxy for data requests.
W/BaseAppContext( 2321): Using Auth Proxy for data requests.
,I/HotwordWorker( 2054): onReady
I/art     ( 2119): Explicit concurrent mark sweep GC freed 9872(613KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.734ms total 64.680ms
,W/BaseAppContext( 2321): Using Auth Proxy for data requests.
,I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{56ef31f u0 com.lge.launcher2/.Launcher t219} time:64071
W/BaseAppContext( 2321): Using Auth Proxy for data requests.
W/BaseAppContext( 2321): Using Auth Proxy for data requests.
,W/BaseAppContext( 2321): Using Auth Proxy for data requests.
,I/art     (  861): Explicit concurrent mark sweep GC freed 16762(1126KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 10.501ms total 641.880ms
,W/ResourcesManager(  861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AndroidRuntime( 4623): Shutting down VM
I/[LGHome]EVENT( 1979): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1979): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1979): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[SystemUI]QPairHandler( 1413): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1941): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1413): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1413): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1413): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1413): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,D/administrator(  861): Handling package changes for user 0
,W/OpenGLRenderer( 1979): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1979): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/LCardEmulationManager( 1887): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1887): getDefaultRoute
,I/NotificationService(  861): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  861): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  861): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  861): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  861): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1ab0c7dd
I/Icing   ( 2321): updateResources: need to parse f{com.google.android.gms}
,D/LCardEmulationManager( 1887): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1887): getDefaultRoute
,W/ResourceType(  861): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/SharedPreferencesImpl( 2321): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
E/SQLiteDatabase( 2321): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2321): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 2321): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 2321): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2321): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2321): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 2321): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteDatabase( 2321): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
E/SQLiteDatabase( 2321): 	at android.content.ContentProvider.query(ContentProvider.java:984)
E/SQLiteDatabase( 2321): 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
E/SQLiteDatabase( 2321): 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
E/SQLiteDatabase( 2321): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
E/SQLiteDatabase( 2321): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 2321): 	at android.content.ContentResolver.query(ContentResolver.java:490)
E/SQLiteDatabase( 2321): 	at android.content.ContentResolver.query(ContentResolver.java:434)
E/SQLiteDatabase( 2321): 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:84)
E/SQLiteDatabase( 2321): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3545)
E/SQLiteDatabase( 2321): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/SQLiteDatabase( 2321): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/SQLiteDatabase( 2321): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/SQLiteDatabase( 2321): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2321): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2321): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 2321): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2321): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/,SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteOpenHelper( 2321): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteOpenHelper( 2321): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 2321): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 2321): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 2321): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteOpenHelper( 2321): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
E/SQLiteOpenHelper( 2321): 	at android.content.ContentProvider.query(ContentProvider.java:984)
E/SQLiteOpenHelper( 2321): 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
E/SQLiteOpenHelper( 2321): 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
E/SQLiteOpenHelper( 2321): 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
E/SQLiteOpenHelper( 2321): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteOpenHelper( 2321): 	at android.content.ContentResolver.query(ContentResolver.java:490)
E/SQLiteOpenHelper( 2321): 	at android.content.ContentResolver.query(ContentResolver.java:434)
E/SQLiteOpenHelper( 2321): 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:84)
E/SQLiteOpenHelper( 2321): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3545)
E/SQLiteOpenHelper( 2321): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/SQLiteOpenHelper( 2321): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/SQLiteOpenHelper( 2321): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/SQLiteOpenHelper( 2321): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2321): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2321): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 2321): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,W/SQLiteOpenHelper( 2321): Opened games_3a3529a.db in read-only mode
I/[LGHome]EVENT( 1979): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
--------- beginning of crash
E/AndroidRuntime( 2321): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2321): Process: com.google.android.gms, PID: 2321
E/AndroidRuntime( 2321): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:307)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:882)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/AndroidRuntime( 2321): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 2321): 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
E/AndroidRuntime( 2321): 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
E/AndroidRuntime( 2321): 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
E/AndroidRuntime( 2321): 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1665)
E/AndroidRuntime( 2321): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1586)
E/AndroidRuntime( 2321): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2321): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2321): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 2321): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak

```
