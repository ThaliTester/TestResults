#### Test 50388019385b4d9_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/libprocessgroup(  837): failed to open /acct/uid_10034/pid_3685/cgroup.procs: No such file or directory
--------- beginning of main
E/QcrilMsgTunnelAutoboot( 2308): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1762): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1762): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  837): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3948 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  837): Waited long enough for: ServiceRecord{acf7162 u0 com.lge.sizechangable.weather/.service.WeatherService}
,W/ResourcesManager( 3948): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ActivityManager(  837): enqueue in BackgroundQueue #59 Intent=Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 (has extras) }
V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{142b1919 type 2 when 52936 com.android.providers.calendar} when 52936
D/AndroidRuntime( 3968): 
D/AndroidRuntime( 3968): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3968): CheckJNI is OFF
I/Babel_SMS( 3948): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3948): MmsConfig.loadMmsSettings
I/Babel_SMS( 3948): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 3948): MmsConfig.loadFromDatabase
E/Babel_SMS( 3948): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3948): MmsConfig.loadFromResources
E/Babel_SMS( 3948): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3948): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/AndroidRuntime( 3968): Calling main entry com.android.commands.am.Am
D/SensorManager( 3948): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 3948): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 3948): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 3948): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 3948): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 3948): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 3948): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 3948): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 3948): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 3948): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 3948): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 3948): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 3948): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 3948): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 3948): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 3948): found sensor: Motion Accel, handle=46
I/art     ( 3948): CheckpointMarkThreadRoots callback created = 0xb042d880
I/ActivityManager(  837): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  837): setTaskToReturnTo : TaskRecord{234b2dd5 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  837): setTaskToReturnTo : TaskRecord{234b2dd5 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/art     ( 3948): CheckpointMarkThreadRoots callback created = 0xb042d860
D/WindowStateEx(  837): AppWindowTokenEx init.. 
D/ContextHelper(  837): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  837): Focus left window: Window{2526e8e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3968): Shutting down VM
I/[LGHome]EVENT( 1888): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  837): check instance of lgWin Window{3d363453 u0 Starting com.example.hello}
I/ActivityManager(  837): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4002 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/Settings( 3948): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[LGHome]EVENT( 1888): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/Babel_Crash( 3948): startup - clean
I/HotwordDetector( 1947): Closing mic
I/MicrophoneInputStream( 1947): mic_close com.google.android.apps.gsa.speech.audio.u@3b30324
V/AudioRecord( 1947): stop()
D/AudioRecord( 1947): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
I/Babel   ( 3948): deleted: false for 0
I/[LGHome]EVENT( 1888): [Launcher.java:5214:onStop()]onStop
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a5a000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/WindowStateAnimator(  837): Starting window displayed
I/SystemUI[Framework](  837): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  837): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  837): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  837): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a0e9b95,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1383): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1383): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1383):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1383): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1383): draw background and invalidate : color = e000000
D/BarTransitions( 1383): draw background and invalidate : color = 100f0f0f
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
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a5a000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
,V/AudioRecord( 1947): stop()
V/AudioRecord( 1947): stop()
V/AudioRecord( 1947): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  837): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 2643): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1383): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb3a5a000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioSystem( 3134): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioFlinger(  282): removeClient_l() pid 1947, calling pid 282
V/AudioSystem( 1762): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): releasing 16 from 1947 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1947): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1947): Stopping hotword detection.
I/HotwordRecognitionRnr( 1947): Hotword detection finished
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
D/ContextHelper( 4002): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 4002): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/AudioCapabilities( 3948): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 3948): Unsupported mime audio/adpcm
W/AudioCapabilities( 3948): Unsupported mime audio/g726
W/AudioCapabilities( 3948): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 3948): Unsupported mime audio/wma-voice
W/VideoCapabilities( 3948): Unsupported mime video/mjpg
W/VideoCapabilities( 3948): Unsupported mime video/theora
I/LibraryLoader( 4002): Time to load native libraries: 2 ms (timestamps 3777-3779)
I/LibraryLoader( 4002): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4002): Binding Chromium to main looper Looper (main, tid 1) {1d97d0c}
W/AudioCapabilities( 3948): Unsupported mime audio/evrc
I/LibraryLoader( 4002): Expected native library version number "",actual native library version number ""
I/chromium( 4002): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/AudioCapabilities( 3948): Unsupported mime audio/qcelp
W/VideoCapabilities( 3948): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 3948): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 3948): Unsupported mime audio/qcelp
W/AudioCapabilities( 3948): Unsupported mime audio/evrc
I/BrowserStartupController( 4002): Initializing chromium process, singleProcess=true
W/art     ( 4002): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4002): ApplicationContext is null in ApplicationStatus
W/VideoCapabilities( 3948): Unsupported mime video/mp4v-esdp
W/chromium( 4002): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/VideoCapabilities( 3948): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 3948): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3948): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3948): Unrecognized profile 2130706433 for video/avc
W/chromium( 4002): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/VideoCapabilities( 3948): Unrecognized profile 2130706433 for video/avc
E/libEGL  ( 4002): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4002): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4002): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4002): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4002): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4002): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4002): Remote Branch: 
I/Adreno-EGL( 4002): Local Patches: 
I/Adreno-EGL( 4002): Reconstruct Branch: 
I/vclib   ( 3948): onServiceConnected
W/Babel   ( 3948): Attempted to change video mute state without an active call.
I/NotificationManager( 3948): com.google.android.talk: cancel(10436) by com.google.android.talk
V/AudioPolicyService(  282): registerClient() client 0xb381c8e0, uid 10317
D/BluetoothAdapter( 4002): 1014653275: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  837): Message: 20
D/BluetoothManagerService(  837): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36fe8fd:true
I/ActivityManager(  837): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4035 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  837): Killing 3706:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10051/pid_3706/cgroup.procs: No such file or directory
,I/Scheduler( 1743): Use legacy PeriodicScheduler
,W/art     ( 4002): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4002): onDetachedFromWindow called when already detached. Ignoring
,W/InstanceID/Rpc( 1743): Found 10006
,D/SystemWebViewEngine( 4002): CordovaWebView is running on device made by: LGE
W/art     ( 4002): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4002): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 4035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Activity( 4002): Activity.onPostResume() called 
,D/OpenGLRenderer( 4002): Render dirty regions requested: true
I/OpenGLRenderer( 4002): Initialized EGL, version 1.4
D/OpenGLRenderer( 4002): Enabling debug mode 0
,D/Atlas   ( 4002): Validating map...
,D/SplitWindow(  837): check instance of lgWin Window{1d2cf31c u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 4002): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/JNIHelp ( 4035): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/InputDispatcher(  837): Focus entered window: Window{1d2cf31c u0 com.example.hello/com.example.hello.MainActivity}
W/InputMethodManagerService(  837): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  837): Displayed com.example.hello/.MainActivity: +1s210ms
I/Timeline(  837): Timeline: Activity_windows_visible id: ActivityRecord{36b799ea u0 com.example.hello/.MainActivity t220} time:54591
I/Timeline( 4002): Timeline: Activity_idle id: android.os.BinderProxy@3a2a3528 time:54598
W/System  ( 4035): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4035): Installed default security provider GmsCore_OpenSSL
W/BindingManager( 4002): Cannot call determinedVisibility() - never saw a connection for the pid: 4002
,I/chromium( 4002): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/art     ( 4035): Suspending all threads took: 8.742ms
,W/ResourcesManager( 4035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/JsMessageQueue( 4002): Set native->JS mode to OnlineEventsBridgeMode
I/art     ( 4035): CheckpointMarkThreadRoots callback created = 0xb042dbe0
E/AndroidProtocolHandler( 4002): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 4035): CheckpointMarkThreadRoots callback created = 0xb4958de0
,I/ActivityManager(  837): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=4089 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/YouTube MDX( 4035): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4035): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/dex2oat ( 4088): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1044683776.jar --oat-fd=29 --oat-location=/data/data/com.google.android.youtube/cache/ads-1044683776.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/libc-netbsd( 4035): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 4089): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4089): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/MultiDex( 4089): VM with version 2.1.0 has multidex support
I/MultiDex( 4089): install
I/MultiDex( 4089): VM has multidex support, MultiDex support library is disabled.
,I/dex2oat ( 4088): dex2oat took 181.694ms (threads: 4)
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 55345415296; DSPS: 1911717; Offset : -2999337681
,D/jxcore_app_log( 4002): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426609152
D/JX-Cordova( 4002): jxcore cordova android initializing
,V/JNIHelp ( 4089): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/CursorWrapperInner( 3723): Cursor finalized without prior close()
,W/ActivityThread( 4089): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4089): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2eb25264: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4089): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 4089): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4089): com.google.android.gms: cancel(39789) by com.google.android.gms
W/jxcore-log( 4002): Initializing JXcore engine
W/jxcore-log( 4002): JXcore engine is ready
,W/jxcore-log( 4002): Starting JXcore engine
I/NotificationManager( 4035): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4035): Found 10006
,W/m.example.hello( 4002): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6588]" dev="sockfs" ino=6588 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4002): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4002): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8538]" dev="sockfs" ino=8538 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 4002): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4002): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4002): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[16758]" dev="sockfs" ino=16758 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4035): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/NativeLibraryUtils( 4089): Install completed successfully. count=14 extracted=0
,W/jxcore-log( 4002): Platform android
W/jxcore-log( 4002): 
W/jxcore-log( 4002): Process ARCH arm
W/jxcore-log( 4002): 
,I/ActivityManager(  837): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4166 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 4002): JXcore Cordova bridge is ready!
I/jxcore-log( 4002): 
W/jxcore-log( 4002): JXcore engine is started
,I/NotificationManager( 4035): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,E/jxcore-log( 4002): >> LGE-LG-D722
E/jxcore-log( 4002): 
,I/jxcore-log( 4002): Total memory 906309632
I/jxcore-log( 4002): 
I/jxcore-log( 4002): Free memory 22683648
I/jxcore-log( 4002): 
I/jxcore-log( 4002): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4002): 
I/jxcore-log( 4002): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4002): 
I/jxcore-log( 4002): userPath [ 'www' ]
I/jxcore-log( 4002): 
,I/jxcore-log( 4002): Size 720 1196
I/jxcore-log( 4002): 
I/jxcore-log( 4002): Screen Brightness 255
I/jxcore-log( 4002): 
E/jxcore-log( 4002): Dummy Error Log.
E/jxcore-log( 4002): 
I/ActivityManager(  837): Killing 3746:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
I/ActivityManager(  837): Killing 3723:com.lge.cloudhub/u0a49 (adj 15): empty #12
,W/libprocessgroup(  837): failed to open /acct/uid_10054/pid_3746/cgroup.procs: No such file or directory
,W/libprocessgroup(  837): failed to open /acct/uid_10049/pid_3723/cgroup.procs: No such file or directory
W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4166): getAccountsCursor
,I/art     (  837): Explicit concurrent mark sweep GC freed 16143(786KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 1.730ms total 148.351ms
,W/ActivityManager(  837): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4166): Observing account changes for notifications
I/jxcore-log( 4002): getBuffer is called!!!!
I/jxcore-log( 4002): 
,W/GAV2    ( 4166): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4166): Error finding the version of the Email provider.....
E/Gmail   ( 4166): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4166): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4166): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4166): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4166): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4166): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4166): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4166): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4166): getAccountsCursor
V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4166): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d192296 that was originally bound here
E/ActivityThread( 4166): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d192296 that was originally bound here
E/ActivityThread( 4166): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4166): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4166): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4166): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4166): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4166): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4166): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4166): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4166): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4166): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4166): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4166): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4166): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4166): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4166): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4166): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  837): Unbind failed: could not find connection for android.os.BinderProxy@3e8859e0
,I/ActivityManager(  837): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4225 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 24.011ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 22.295ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 22.291ms
,I/Gmail   ( 4166): notifyAccountChanged
,I/Gmail   ( 4166): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  837): Killing 3770:com.lge.lgfota.permission/1000 (adj 15): empty #11
I/Gmail   ( 4166): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4166): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4166): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_3770/cgroup.procs: No such file or directory
,V/[BNRBootReceiver]( 4225): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4225): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4225): End of BootComplted IF
V/[BNRBootReceiver]( 4225): Boot Receiver Return
V/[BNRBootCompletedThread]( 4225): run
W/linker  ( 4254): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/bnrd    ( 4254): BNRD > wait starting [4254-3058102400] <
E/bnrd    ( 4254): /data/data/.bnr_fifo_req
V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/[BNRBootCompletedThread]( 4225): End of BNRProcess
,V/[BNRBootCompletedThread]( 4225): End of BNRViaWifiProcess
I/ActivityManager(  837): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4259 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  837): Killing 3828:com.lge.hiddenmenu/1000 (adj 15): empty #11
V/[BNRBootCompletedThread]( 4225): End of SpriteProcess
V/[BNRBootCompletedThread]( 4225): exit
W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_3828/cgroup.procs: No such file or directory
,I/WebViewFactory( 1947): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/NotificationManager( 1947): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4166): getAccountsCursor
V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LibraryLoader( 1947): Time to load native libraries: 12 ms (timestamps 7421-7433)
,I/LibraryLoader( 1947): Expected native library version number "",actual native library version number ""
I/Gmail   ( 4166): getAccountsCursor
W/art     ( 1947): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1743): Explicit concurrent mark sweep GC freed 19655(1356KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 12MB/21MB, paused 1.946ms total 96.290ms
,W/art     ( 1947): Attempt to remove local handle scope entry from IRT, ignoring
D/Finsky  ( 4259): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/libc-netbsd( 1743): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1743): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1743): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1743): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  837): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/Auth    ( 1743): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1947): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1947): java.io.IOException: NetworkError
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1947): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/libc-netbsd( 1743): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1743): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Auth    ( 1743): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1947): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1947): java.io.IOException: NetworkError
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1947): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1947): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1947): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/Finsky  ( 4259): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4259): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4259): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4259): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3155): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3155): created cursor android.database.sqlite.SQLiteCursor@153e8a1f on behalf of 4259
D/Volley  ( 4259): [451] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4259): [458] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 4259): Skipping gmscore version check
D/Finsky  ( 4259): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4259): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4259): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4259): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/FileApkUtils( 4089): Spent 62ms computing apk sha1.
D/FileApkUtils( 4089): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4089): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4089): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4089): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 4089): Reading stored module config
D/GmsModuleFndr( 4089): Beginning GMS chimera module scan
,W/InstanceID/Rpc( 4089): Found 10006
,D/ChimeraCfgMgr( 4089): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 4089): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 4089): Got an BootCompleted event.
D/BootCompletedReceiver( 4089): Will NOT schedule AdAttestation signal task because it's disabled.
,I/art     ( 3787): Explicit concurrent mark sweep GC freed 8474(433KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.029ms total 47.542ms
D/GmsModuleFndr( 4089): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 4089): Beginning module configuration check
D/PowerService( 1814): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1383): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1383): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1383): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1383): On Skip Timer : true
D/ChimeraCfgMgr( 4089): Module APKs unchanged, check complete
I/art     ( 4089): CheckpointMarkThreadRoots callback created = 0xaae7b680
,D/GCM     ( 4089): COMPAT: Multi user not supported
I/art     ( 4089): CheckpointMarkThreadRoots callback created = 0xb042d6b0
,D/GCM     ( 1743): COMPAT: Multi user not supported
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/GCoreUlr( 4089): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 4089): Checkin interval check for package: unspecified last checkin: 1450156498802 min interval config: 0 actual interval: 32793685
I/CheckinService( 4089): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 4089): onCreate
D/SystemUpdateService( 4089): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 4089): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 4089): cancelUpdate (empty URL)
,I/SystemUpdateService( 4089): active receiver: disabled
I/NotificationManager( 4089): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/art     ( 3787): Explicit concurrent mark sweep GC freed 2553(101KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.109ms total 34.802ms
I/NotificationManager( 4089): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,D/AuthZenEventHandler( 4089): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     ( 4089): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4089): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/GCM     ( 1743): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1743): DispatchingService.onCreate()
W/BaseAppContext( 4089): Using Auth Proxy for data requests.
D/libc-netbsd( 1743): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1743): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1743): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1743): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  837): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/CheckinService( 4089): Checking schedule, now: 1450189292714 next: 1450683747767
I/CheckinService( 4089): active receiver: disabled
,E/BaseAppContext( 4089): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/AuthZen ( 4089): Fetching signing key...
,I/GCoreUlr( 1743): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/AuthZen ( 4089): Signing key fetched successfully!
W/BaseAppContext( 4089): Using Auth Proxy for data requests.
,W/Auth    ( 1743): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/a       ( 4089): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4089): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 4089): Clearing transaction cache
D/SystemUpdateService( 4089): onDestroy
D/PersistentNotificationBroadcastReceiver( 1743): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/NotificationManager( 4089): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/GCoreFlp( 1743): No location to return for getLastLocation()
W/FusedLocationProvider( 1743): location=null
W/GCoreFlp( 1743): No location to return for getLastLocation()
W/FusedLocationProvider( 1743): location=null
,I/GCoreUlr( 1743): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  837): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4382 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  837): Killing 3846:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10069/pid_3846/cgroup.procs: No such file or directory
,I/art     (  837): Explicit concurrent mark sweep GC freed 23483(1155KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 1.949ms total 145.630ms
I/GCoreUlr( 1743): Unbound from all location providers
I/GCoreUlr( 1743): Place inference reporting - stopped
,I/GCoreUlr( 1743): DispatchingService.onDestroy()
I/GCoreUlr( 1743): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1743): Unbound from all location providers
I/GCoreUlr( 1743): Place inference reporting - stopped
,W/ResourcesManager( 4382): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/App     ( 4382): [App][onCreate()] 4.40.23
,I/ActivityManager(  837): Waited long enough for: ServiceRecord{aaac905 u0 com.android.mms/.service.SwitchedService}
,D/AccountManager( 4382): setSyncFrequency
,W/ContextImpl( 4382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/ReminderService( 4382): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
,D/LocationReminderManager( 4382): [connect] Request location client connection.
I/ActivityManager(  837): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4410 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ContextImpl( 4382): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  837): Killing 3864:com.lge.springcleaning/1000 (adj 15): empty #11
,D/LocationReminderManager( 4382): location cilent is connected.
,D/LocationReminderManager( 4382): [removeAllReminders]
,W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_3864/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1743): Ignoring removeGeofence because network location is disabled.
D/LocationReminderManager( 4382): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4382): [removeAllReminders] Failed to remove reminder
D/LGDMClient( 4410): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4410): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/WeatherAncestor( 2634): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:21:33
D/UpdateThreadPoolManager( 2634): 2 : This is isUpdating : false
D/WeatherAncestor( 2634): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:21:33
D/WeatherService( 2634): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  837): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2634): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2634): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2634): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2634): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2634): 2 : This is isUpdating : false
D/WeatherService( 2634): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2634): 2 : buildUpdate, appWidgetId: 2
V/UserPresentBroadcastReceiver( 1743): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/LGDMClient( 4410): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,D/WeatherTheme( 2634): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2634): 2 : Fixed theme : optimus
,I/art     ( 1743): Explicit concurrent mark sweep GC freed 16143(1117KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 13MB/21MB, paused 19.338ms total 124.387ms
D/WeatherReflect( 2634): 2 : Map key string is -2
,W/GCoreFlp( 1743): No location to return for getLastLocation()
,W/GCoreFlp( 1743): No location to return for getLastLocation()
D/LGDMClient( 4410): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/lim     ( 2634): 2 : time = 15:21
I/WeatherReflect( 2634): Model Name : LG-D722
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,D/WeatherTheme( 2634): 2 : exactly same view!
D/WeatherTheme( 2634): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  837): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2634): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2634): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2634): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  837): Killing 3898:com.google.android.configupdater/u0a3 (adj 15): empty #11
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,W/libprocessgroup(  837): failed to open /acct/uid_10003/pid_3898/cgroup.procs: No such file or directory
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,I/ActivityManager(  837): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4444 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  837): Message: 20
D/BluetoothManagerService(  837): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2088de30:true
,D/BluetoothAdapter( 4444): 824663544: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4444): 824663544: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  837): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4465 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{115349eb type 2 when 60540 com.google.android.gms} when 60540
V/LGMDMManager( 4444): Create singleton instance
,D/UEI.SmartControl( 4465): Quickset Services start...
,I/UEI.SmartControl( 4465): Manufacture = LGE
D/UEI.SmartControl( 4465): File observer start...
E/UEI.SmartControl( 4465): IR Port is disabled: false
D/UEI.SmartControl( 4465): Starting file observer...
D/UEI.SmartControl( 4465): Extracting JNI libs...
D/UEI.SmartControl( 4465): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4444): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
I/AudioManager( 4444): getMode name:com.lge.qremote
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4465): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4465): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4465): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3134): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3134): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4410): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
,D/LGDMClient( 4410): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/UEI.SmartControl( 4465): --- Selecting new region: 2
I/UEI.SmartControl( 4465): -- Running on KitKat(19) and above! JNI will be used.
D/LGDMClient( 4410): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/AudioManager( 4444): getMode name:com.lge.qremote
D/UEI.SmartControl( 4465): Platform has CIR...
D/LGDMClient( 4410): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
D/UEI.SmartControl( 4465): NO CIR support, need to check package...
I/UEI.SmartControl( 4465): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4465): QS Service created
I/AudioManager( 4444): getMode name:com.lge.qremote
,E/UEI.SmartControl( 4465): QS start get config
,I/ActivityManager(  837): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4499 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/UEI.SmartControl( 4465): Loading JNI Libs...
,D/UEI.SmartControl( 4465):  configuring local db...
,W/ResourcesManager( 4499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4499): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4499): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 4499): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/BluetoothManagerService(  837): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  837): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  837): Message: 2
D/LGEmail ( 4499): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/WifiServiceImplEx(  837): setWifiEnabled: false pid=4002, uid=10317, package= com.example.hello, App Lable : HelloWorld
,D/WifiService(  837): setWifiEnabled: false pid=4002, uid=10317
I/jxcore-log( 4002): ****TEST TOOK:  5064  ms ****
I/jxcore-log( 4002): 
D/UEI.SmartControl( 4465):  ---- Has DB8: true
I/jxcore-log( 4002): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4002): 
D/UEI.SmartControl( 4465): QS start statue = true Error code = 0
D/UEI.SmartControl( 4465): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 4465): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4465): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4465): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4465): IrrcClient ++ 
D/irrcClient( 4465): getIrrcService ++ 
D/irrcClient( 4465): getIrrcService -- 
D/irrcClient( 4465): IrrcClient -- 
,W/irrc_jni( 4465): IRRCPlayer_nativeInit -- 
I/UEI.SmartControl( 4465): Device manager: loading config....
D/UEI.SmartControl( 4465): Services init done
D/UEI.SmartControl( 4465): QS Service init finished
D/UEI.SmartControl( 4465): Config is loaded...
,D/UEI.SmartControl( 4465): QS Service version name: 0.1.73
D/UEI.SmartControl( 4465): QS Service version code: 1073
D/UEI.SmartControl( 4465): Service requested: Control
D/UEI.SmartControl( 4465): Internal service binding...
D/UEI.SmartControl( 4465): -----IControl: 11
D/UEI.SmartControl( 4465): Caller: com.lge.qremote
D/UEI.SmartControl( 4465): ------------ IControl registerCallback...
I/UEI.SmartControl( 4465): Registering callback...
D/UEI.SmartControl( 4465): -----IControl: 19
,D/UEI.SmartControl( 4465): Caller: com.lge.qremote
I/UEI.SmartControl( 4465): Registering Services Ready callback...
I/UEI.SmartControl( 4465): Notify client services are ready...
D/UEI.SmartControl( 4465): -----IControl: 8
D/UEI.SmartControl( 4465): Caller: com.lge.qremote
I/ActivityManager(  837): Killing 3948:com.google.android.talk/u0a61 (adj 15): empty #11
D/UEI.SmartControl( 4465):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 4465): Notify AllClients services are ready: 0
I/ActivityManager(  837): Killing 3928:com.lge.eula/1000 (adj 15): empty #12
,W/libprocessgroup(  837): failed to open /acct/uid_10061/pid_3948/cgroup.procs: No such file or directory
,W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_3928/cgroup.procs: No such file or directory
,I/PackageChangeReceiver( 4499): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  837): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4531 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  837): Killing 4035:com.google.android.youtube/u0a100 (adj 15): empty #11
D/AndroidRuntime( 4527): 
D/AndroidRuntime( 4527): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4527): CheckJNI is OFF
W/libprocessgroup(  837): failed to open /acct/uid_10100/pid_4035/cgroup.procs: No such file or directory
,I/ActivityManager(  837): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4561 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  837): Killing 4166:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10053/pid_4166/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4561): onCreate
W/AppUp4:DB( 4561):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4561):  setFingerPrint start
I/AppUp4:DB( 4561):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4561):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4561):  SDK version = 0
I/AppUp4:DB( 4561):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4561): AppBoxApplication onCreate()
D/AndroidRuntime( 4527): Calling main entry com.android.commands.pm.Pm
,D/AppUp4:PreloadHelper( 4561): removed from Exclude : com.example.hello : 1
,I/ActivityManager(  837): Killing 4225:com.lge.bnr/1000 (adj 15): empty #11
W/PackageSettings(  837): Skipping PackageSetting{29332a3e com.test.thalitest/10316} due to missing metadata
,W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_4225/cgroup.procs: No such file or directory
I/ActivityManager(  837): Force stopping com.example.hello appid=10317 user=0: pkg removed
I/ActivityManager(  837): Killing 4002:com.example.hello/u0a317 (adj 0): stop com.example.hello
I/WindowState(  837): WIN DEATH: Window{1d2cf31c u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  837): Focus left window: Window{1d2cf31c u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  837): Window went away: Window{1d2cf31c u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager(  837): Force removing ActivityRecord{36b799ea u0 com.example.hello/.MainActivity t220}: app died, no saved state
,I/ActivityManager(  837): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
,D/KeyguardModel( 1383): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1851): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1743): Ignoring removeGeofence because network location is disabled.
I/InputReader(  837): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3420): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3420): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3420): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3420): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3420): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3420): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3420): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3420): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3420): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/administrator(  837): Handling package changes for user 0
,I/ActivityManager(  837): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4586 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ActivityManager(  837): Spurious death for ProcessRecord{59a7866 4002:com.example.hello/u0a317}, curProc for 4002: null
I/ActivityManager(  837): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4603 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 1888): [Launcher.java:5203:onStart()]onStart
I/[SystemUI]QSlideListController( 1383): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1888): [Launcher.java:776:onResume()]onResume
,W/ResourcesManager( 4586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4586): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4586): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/[LGHome]LGActivityUtil( 1888): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1888): [Launcher.java:929:onResume()]onResume end
I/Activity( 1888): Activity.onPostResume() called 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1383): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1383): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     ( 1797): CheckpointMarkThreadRoots callback created = 0xaaf1fb80
,I/SystemUI[Framework](  837): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  837): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  837): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  837): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a0e9b95,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  837): Focus entered window: Window{2526e8e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/[LGHome]LGWallpaperInfo( 1888): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1888): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/[LGHome]EVENT( 1888): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1888): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1888): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1888): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/art     ( 1797): CheckpointMarkThreadRoots callback created = 0xb042d6d0
,I/PhoneWindow( 1888): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  837): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  837): Got RemoteException sending setActive(false) notification to pid 4002 uid 10317
,I/LockScreenSettings( 4603): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1383): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1383): createShortcutInfo...
,D/KeyguardModel( 1383): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1383): createShortcutInfo...
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1383): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1383): createShortcutInfo...
,W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/Timeline( 1888): Timeline: Activity_idle id: android.os.BinderProxy@243389fc time:62417
D/KeyguardModel( 1383): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1383): createShortcutInfo...
I/SystemUI[Framework](  837): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PhoneWindowManagerEx(  837): Call!!!getLGSystemUiVisibility. =0x0
W/PackageManager( 1383): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/StatusBarManagerServiceEx(  837): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  837): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a0e9b95,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1383): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1383): createShortcutInfo...
,I/HotwordRecognitionRnr( 1947): Starting hotword detection.
D/KeyguardModel( 1383): handleShortcutListChanged...
I/MicrophoneInputStream( 1947): mic_starting com.google.android.apps.gsa.speech.audio.u@255202d9
V/AudioRecord( 1947): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1947): set(): mSessionId 22
D/KeyguardModel( 1383): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1383): createShortcutInfo...
V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e240)
V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb546e240, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  282): openInput_l() created record thread: ID 23 thread 0xb3a5a000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioSystem(  837): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1383): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1762): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1947): ioConfigChanged() event 3, ioHandle 23
,V/AudioSystem( 3134): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2643): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  282): AudioFlinger's thread 0xb3a5a000 ready to run
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
D/KeyguardModel( 1383): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1383): createShortcutInfo...
V/AudioFlinger(  282): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  282): getOrphanEffectChain_l session 22 index -2
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.android.mms: Resource ID #0x0
V/AudioFlinger(  282): acquiring 22 from 1947, for -1
V/AudioFlinger(  282):  added new entry for 22
V/AudioRecord( 1947): start, sync event 0 trigger session 0
V/AudioRecord( 1947): mAudioRecord->start()
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
V/AudioFlinger(  282): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a5a000
V/AudioFlinger::PatchPanel(  282): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  282): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  282): setParameters(): io 23, keyvalue hotword_active=1, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event, 2
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
D/KeyguardModel( 1383): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1383): createShortcutInfo...
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1383): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1383): createShortcutInfo...
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1383): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1383): createShortcutInfo...
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a5a000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
I/ActivityManager(  837): Killing 4259:com.android.vending/u0a36 (adj 15): empty #11
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb546e240)usecase(7: audio-record)
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
,V/audio_hw_primary(  282): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  282): start_input_stream: exit
I/NotificationService(  837): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  837): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  837): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1383): handleShortcutListChanged...
,I/ActivityManager(  837): Waited long enough for: ServiceRecord{38448810 u0 com.lge.mlt/.MltMonitorService}
W/libprocessgroup(  837): failed to open /acct/uid_10036/pid_4259/cgroup.procs: No such file or directory
D/TaskPersister(  837): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1383): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1383): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1383): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1383):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1383): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1947): mic_started com.google.android.apps.gsa.speech.audio.u@255202d9
I/HotwordWorker( 1947): onReady
,D/BarTransitions( 1383): draw background and invalidate : color = f2000000
D/BarTransitions( 1383): draw background and invalidate : color = f0e7e7e7
I/art     (  837): Explicit concurrent mark sweep GC freed 22762(1401KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.941ms total 465.034ms
,I/AppConfig( 4586): Total System Memory = 906309632
I/GalleryUtils( 4586): Application Heap = 96 MB
,I/AppConfig( 4586): App Tier : NOT_DEF
D/SystemHelper( 4586): region [EU], country [EU], operator [OPEN], sub-operator []
,I/Timeline(  837): Timeline: Activity_windows_visible id: ActivityRecord{1d4ce892 u0 com.lge.launcher2/.Launcher t219} time:62673
D/AndroidRuntime( 4527): Shutting down VM
,W/ResourcesManager(  837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  837): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4629 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  837): Killing 4089:com.google.android.gms/u0a6 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.180ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.881ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 320us total 21.769ms
,W/libprocessgroup(  837): failed to open /acct/uid_10006/pid_4089/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1797): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1797): getDefaultRoute
,W/ResourcesManager( 4629): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4629): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4629): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 4629): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4629): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType(  837): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1888): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/SystemConfig( 4629): BUILD Country: EU
I/SystemConfig( 4629): BUILD Operator: OPEN
,I/LockScreenSettings( 4603): New app installed broadcast received ..
,I/SystemConfig( 4629): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4629): existFile = false
I/SystemConfig( 4629): canReadFile = false
I/SystemConfig( 4629): systemFeature RCS result false
D/SystemConfig( 4629): refreshRcsSupport() :false
I/LockScreenSettings( 4603): Number of installed packages  1
I/ActivityManager(  837): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4657 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
