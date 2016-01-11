#### Test 50242285feafdeb_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/ResourcesManager( 4001): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,--------- beginning of main
D/AndroidRuntime( 4026): 
D/AndroidRuntime( 4026): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4026): CheckJNI is OFF
D/ActivityManager(  835): enqueue in BackgroundQueue #59 Intent=Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 (has extras) }
V/AlarmManager(  835): ELAPSED_WAKEUP set : Alarm{1cf6765a type 2 when 52708 com.android.providers.calendar} when 52708
I/Babel_SMS( 4001): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4001): MmsConfig.loadMmsSettings
I/Babel_SMS( 4001): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4001): MmsConfig.loadFromDatabase
E/Babel_SMS( 4001): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4001): MmsConfig.loadFromResources
E/Babel_SMS( 4001): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4001): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 4001): CheckpointMarkThreadRoots callback created = 0xb042d8d0
I/art     ( 4001): CheckpointMarkThreadRoots callback created = 0xb042d8b0
D/SensorManager( 4001): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4001): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4001): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4001): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4001): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4001): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4001): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4001): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4001): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4001): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4001): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4001): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4001): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4001): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4001): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4001): found sensor: Motion Accel, handle=46
D/AndroidRuntime( 4026): Calling main entry com.android.commands.am.Am
I/ActivityManager(  835): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  835): setTaskToReturnTo : TaskRecord{12481a67 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  835): setTaskToReturnTo : TaskRecord{12481a67 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  835): AppWindowTokenEx init.. 
D/ContextHelper(  835): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  835): Focus left window: Window{3a67a11a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4026): Shutting down VM
W/Settings( 4001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[LGHome]EVENT( 1895): [Launcher.java:986:onPause()]onPause
I/Babel_Crash( 4001): startup - clean
D/SplitWindow(  835): check instance of lgWin Window{28260dac u0 Starting com.example.hello}
I/ActivityManager(  835): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4057 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1895): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1996): Closing mic
I/MicrophoneInputStream( 1996): mic_close com.google.android.apps.gsa.speech.audio.u@1164797c
V/AudioRecord( 1996): stop()
D/AudioRecord( 1996): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
I/Babel   ( 4001): deleted: false for 0
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3868000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/WindowStateAnimator(  835): Starting window displayed
I/SystemUI[Framework](  835): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  835): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  835): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  835): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  835): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@39add8a5,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  835): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1388): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1388):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1388): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1388): draw background and invalidate : color = 6000000
I/[LGHome]EVENT( 1895): [Launcher.java:5214:onStop()]onStop
D/BarTransitions( 1388): draw background and invalidate : color = 8080808
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  280): setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3868000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1996): stop()
V/AudioRecord( 1996): stop()
V/AudioRecord( 1996): stop()
,V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 1996): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 2652): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb3868000 exiting
V/AudioSystem(  835): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1388): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1769): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3139): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1996, calling pid 280
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioFlinger(  280): releasing 16 from 1996 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
I/HotwordRecognitionRnr( 1996): Stopping hotword detection.
I/HotwordRecognitionRnr( 1996): Hotword detection finished
D/ContextHelper( 4057): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
I/WebViewFactory( 4057): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/AudioCapabilities( 4001): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4001): Unsupported mime audio/adpcm
W/AudioCapabilities( 4001): Unsupported mime audio/g726
W/AudioCapabilities( 4001): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4001): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4001): Unsupported mime video/mjpg
W/VideoCapabilities( 4001): Unsupported mime video/theora
I/LibraryLoader( 4057): Time to load native libraries: 2 ms (timestamps 3384-3386)
I/LibraryLoader( 4057): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4057): Binding Chromium to main looper Looper (main, tid 1) {33a6b064}
I/LibraryLoader( 4057): Expected native library version number "",actual native library version number ""
I/chromium( 4057): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/AudioCapabilities( 4001): Unsupported mime audio/evrc
W/AudioCapabilities( 4001): Unsupported mime audio/qcelp
W/VideoCapabilities( 4001): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4001): Unsupported mime audio/amr-wb-plus
I/BrowserStartupController( 4057): Initializing chromium process, singleProcess=true
W/AudioCapabilities( 4001): Unsupported mime audio/qcelp
W/art     ( 4057): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4057): ApplicationContext is null in ApplicationStatus
W/AudioCapabilities( 4001): Unsupported mime audio/evrc
W/chromium( 4057): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/VideoCapabilities( 4001): Unsupported mime video/mp4v-esdp
W/chromium( 4057): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/VideoCapabilities( 4001): Unsupported profile 4 for video/mp4v-es
E/libEGL  ( 4057): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4057): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4057): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4057): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4057): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4057): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4057): Remote Branch: 
I/Adreno-EGL( 4057): Local Patches: 
I/Adreno-EGL( 4057): Reconstruct Branch: 
W/VideoCapabilities( 4001): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4001): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4001): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4001): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4001): onServiceConnected
W/Babel   ( 4001): Attempted to change video mute state without an active call.
V/AudioPolicyService(  280): registerClient() client 0xb3824ca0, uid 10317
D/BluetoothManagerService(  835): Message: 20
D/BluetoothManagerService(  835): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39cdb0ae:true
D/BluetoothAdapter( 4057): 273706704: getState() :  mService = null. Returning STATE_OFF
I/NotificationManager( 4001): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  835): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4091 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  835): Killing 3778:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
W/libprocessgroup(  835): failed to open /acct/uid_10054/pid_3778/cgroup.procs: No such file or directory
,I/Scheduler( 1750): Use legacy PeriodicScheduler
,W/art     ( 4057): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4057): onDetachedFromWindow called when already detached. Ignoring
,W/InstanceID/Rpc( 1750): Found 10006
D/SystemWebViewEngine( 4057): CordovaWebView is running on device made by: LGE
,W/art     ( 4057): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4057): Attempt to remove local handle scope entry from IRT, ignoring
W/ResourcesManager( 4091): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4091): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Activity( 4057): Activity.onPostResume() called 
,D/OpenGLRenderer( 4057): Render dirty regions requested: true
I/OpenGLRenderer( 4057): Initialized EGL, version 1.4
D/OpenGLRenderer( 4057): Enabling debug mode 0
,D/Atlas   ( 4057): Validating map...
,D/SplitWindow(  835): check instance of lgWin Window{a5e756a u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 4057): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/JNIHelp ( 4091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/InputDispatcher(  835): Focus entered window: Window{a5e756a u0 com.example.hello/com.example.hello.MainActivity}
,W/InputMethodManagerService(  835): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  835): Displayed com.example.hello/.MainActivity: +1s128ms
I/Timeline(  835): Timeline: Activity_windows_visible id: ActivityRecord{1368d014 u0 com.example.hello/.MainActivity t220} time:54148
I/Timeline( 4057): Timeline: Activity_idle id: android.os.BinderProxy@8052c00 time:54160
,W/System  ( 4091): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4091): Installed default security provider GmsCore_OpenSSL
W/BindingManager( 4057): Cannot call determinedVisibility() - never saw a connection for the pid: 4057
,I/chromium( 4057): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4057): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4057): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 4091): CheckpointMarkThreadRoots callback created = 0xb042dba0
,I/art     ( 4091): CheckpointMarkThreadRoots callback created = 0xb4958de0
,E/YouTube MDX( 4091): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ResourcesManager( 4091): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4091): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 4091): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4091): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4091): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4146): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2115379534.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads-2115379534.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/WeatherService( 2642): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:48:0
D/WeatherService( 2642): 2 : TimeTick Intent And Screen On
,D/WeatherService( 2642): 2 : SDK version : 21
W/ActivityManager(  835): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2642): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2642): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2642): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2642): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2642): 2 : This is isUpdating : false
D/WeatherService( 2642): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2642): 2 : buildUpdate, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1388): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1388): called onTimeUpdated()
I/[SystemUI]Clock( 1388): called onTimeUpdated()
I/LgeClockWidgetControlView( 1388): called onTimeUpdated()
I/[SystemUI]DateView( 1388): called onTimeUpdated()
,I/[SystemUI]DateView( 1388): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1388): handleTimeUpdate
D/WeatherTheme( 2642): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2642): 2 : Fixed theme : optimus
D/WeatherReflect( 2642): 2 : Map key string is -2
,D/lim     ( 2642): 2 : time = 23:48
I/WeatherReflect( 2642): Model Name : LG-D722
D/WeatherTheme( 2642): 2 : Different view - status_min_formatted : 47 != 48
D/WeatherTheme( 2642): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2642): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2642): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2642): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/sensors_hal_Time(  835): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  835): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  835): tsOffsetIs: Apps: 54943275608; DSPS: 1898635; Offset : -2999726881
,D/Weather4x2_optimus( 2642): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2642): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2642): forecast size is 0
D/Theme   ( 2642): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2642): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2642): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2642): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2642): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2642): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2642): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2642): url is : null
D/Theme   ( 2642): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2642): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2642): 2 : update view, appWidgetId: 2
,D/WeatherService( 2642): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:48:0
D/jxcore_app_log( 4057): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
,I/dex2oat ( 4146): dex2oat took 250.140ms (threads: 4)
,W/jxcore-log( 4057): Initializing JXcore engine
W/jxcore-log( 4057): JXcore engine is ready
,I/NotificationManager( 4091): com.google.android.youtube: cancel(2) by com.google.android.youtube
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1895): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4091): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4091): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/Thread-436( 4170): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6341]" dev="sockfs" ino=6341 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-436( 4170): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-436( 4170): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6482]" dev="sockfs" ino=6482 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-436( 4170): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-436( 4170): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-436( 4170): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21607]" dev="sockfs" ino=21607 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4091): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/jxcore-log( 4057): Starting JXcore engine
,W/InstanceID/Rpc( 4091): Found 10006
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4091): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1895): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/jxcore-log( 4057): Platform android
W/jxcore-log( 4057): 
W/jxcore-log( 4057): Process ARCH arm
W/jxcore-log( 4057): 
,I/jxcore-log( 4057): JXcore Cordova bridge is ready!
I/jxcore-log( 4057): 
W/jxcore-log( 4057): JXcore engine is started
,I/ActivityManager(  835): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4204 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/jxcore-log( 4057): >> LGE-LG-D722
E/jxcore-log( 4057): 
,I/jxcore-log( 4057): Total memory 906309632
I/jxcore-log( 4057): 
I/jxcore-log( 4057): Free memory 21430272
I/jxcore-log( 4057): 
I/jxcore-log( 4057): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4057): 
I/jxcore-log( 4057): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4057): 
I/jxcore-log( 4057): userPath [ 'www', 'www' ]
I/jxcore-log( 4057): 
,I/jxcore-log( 4057): Size 720 1196
I/jxcore-log( 4057): 
I/jxcore-log( 4057): Screen Brightness 255
I/jxcore-log( 4057): 
E/jxcore-log( 4057): Dummy Error Log.
E/jxcore-log( 4057): 
I/NotificationManager( 4091): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  835): Killing 3802:com.lge.lgfota.permission/1000 (adj 15): empty #11
,W/libprocessgroup(  835): failed to open /acct/uid_1000/pid_3802/cgroup.procs: No such file or directory
,W/ActivityManager(  835): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4204): getAccountsCursor
,W/GAV2    ( 4204): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  835): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4204): Error finding the version of the Email provider.....
E/Gmail   ( 4204): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4204): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4204): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4204): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4204): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4204): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4204): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4204): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4204): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4204): getAccountsCursor
V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 4057): getBuffer is called!!!!
I/jxcore-log( 4057): 
,I/art     (  835): Explicit concurrent mark sweep GC freed 17126(831KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 1.967ms total 143.261ms
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  835): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  835): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4204): Observing account changes for notifications
,W/ActivityManager(  835): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  835): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 4204): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2efcd45c that was originally bound here
E/ActivityThread( 4204): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2efcd45c that was originally bound here
E/ActivityThread( 4204): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4204): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4204): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4204): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4204): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4204): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4204): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4204): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4204): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4204): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4204): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4204): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4204): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4204): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4204): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4204): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  835): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ActivityManager(  835): Unbind failed: could not find connection for android.os.BinderProxy@d362ee8
,I/Gmail   ( 4204): notifyAccountChanged
I/Gmail   ( 4204): getAccountsCursor
V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4204): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 4057): Background sticky concurrent mark sweep GC freed 41389(2MB) AllocSpace objects, 17(588KB) LOS objects, 23% free, 8MB/11MB, paused 7.666ms total 43.757ms
I/ActivityManager(  835): Killing 3839:com.lge.hiddenmenu/1000 (adj 15): empty #11
I/Gmail   ( 4204): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  835): failed to open /acct/uid_1000/pid_3839/cgroup.procs: No such file or directory
I/Gmail   ( 4204): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4204): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/[BNRBootReceiver]( 4256): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4256): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4256): End of BootComplted IF
V/[BNRBootReceiver]( 4256): Boot Receiver Return
V/[BNRBootCompletedThread]( 4256): run
W/linker  ( 4286): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4286): BNRD > wait starting [4286-3058102400] <
E/bnrd    ( 4286): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4256): End of BNRProcess
,V/[BNRBootCompletedThread]( 4256): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4256): End of SpriteProcess
V/[BNRBootCompletedThread]( 4256): exit
I/ActivityManager(  835): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4293 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  835): Killing 3861:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/WebViewFactory( 1996): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  835): failed to open /acct/uid_10014/pid_3861/cgroup.procs: No such file or directory
,I/LibraryLoader( 1996): Time to load native libraries: 4 ms (timestamps 6799-6803)
I/LibraryLoader( 1996): Expected native library version number "",actual native library version number ""
,W/art     ( 1996): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager( 1996): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/Gmail   ( 4204): getAccountsCursor
,W/art     ( 1996): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1750): Explicit concurrent mark sweep GC freed 19216(1330KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 12MB/21MB, paused 2.166ms total 105.600ms
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 1750): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1750): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1750): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1750): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  835): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/Auth    ( 1750): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1996): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1996): java.io.IOException: NetworkError
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1996): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/libc-netbsd( 1750): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1750): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/Auth    ( 1750): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1996): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1996): java.io.IOException: NetworkError
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1996): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1996): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1996): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/Finsky  ( 4293): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4293): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4293): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4293): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4293): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Volley  ( 4293): [448] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4293): [441] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 4293): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4293): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3160): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Ads     ( 4293): Skipping gmscore version check
V/DownloadManager( 3160): created cursor android.database.sqlite.SQLiteCursor@2eea30c4 on behalf of 4293
D/Finsky  ( 4293): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4293): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/FileApkUtils( 2290): Spent 47ms computing apk sha1.
,D/FileApkUtils( 2290): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2290): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 2290): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2290): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
W/InstanceID/Rpc( 2290): Found 10006
,I/art     ( 2069): Explicit concurrent mark sweep GC freed 3850(166KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 481us total 38.435ms
,D/GmsModuleFndr( 2290): Beginning GMS chimera module scan
D/GmsModuleFndr( 2290): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 2290): Beginning module configuration check
D/ChimeraCfgMgr( 2290): Module APKs unchanged, check complete
D/ChimeraCfgMgr( 2290): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 2290): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2290): Got an BootCompleted event.
,D/BootCompletedReceiver( 2290): Will NOT schedule AdAttestation signal task because it's disabled.
D/GCM     ( 2290): COMPAT: Multi user not supported
,D/GCM     ( 1750): COMPAT: Multi user not supported
,I/CheckinService( 2290): Checkin interval check for package: unspecified last checkin: 1452528234042 min interval config: 0 actual interval: 24249057
I/GCoreUlr( 2290): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 2290): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 2290): onCreate
,D/SystemUpdateService( 2290): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 2290): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 2290): cancelUpdate (empty URL)
I/SystemUpdateService( 2290): active receiver: disabled
I/NotificationManager( 2290): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 2290): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,D/AuthZenEventHandler( 2290): Handling event: android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 2290): onDestroy
,W/BaseAppContext( 2290): Using Auth Proxy for data requests.
,I/CheckinService( 2290): Checking schedule, now: 1452552483293 next: 1453055482978
I/CheckinService( 2290): active receiver: disabled
,I/art     ( 2069): Explicit concurrent mark sweep GC freed 2903(113KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 974us total 29.105ms
,E/BaseAppContext( 2290): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/AuthZen ( 2290): Fetching signing key...
,I/AuthZen ( 2290): Signing key fetched successfully!
,W/BaseAppContext( 2290): Using Auth Proxy for data requests.
D/a       ( 2290): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2290): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2290): Clearing transaction cache
,D/GCM     ( 1750): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1750): DispatchingService.onCreate()
,D/libc-netbsd( 1750): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1750): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1750): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1750): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  835): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/KeyguardUpdateMonitor( 1388): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1388): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1388): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1388): On Skip Timer : true
D/PowerService( 1821): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
I/GCoreUlr( 1750): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/NotificationManager( 2290): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/Auth    ( 1750): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/GCoreFlp( 1750): No location to return for getLastLocation()
W/FusedLocationProvider( 1750): location=null
V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1750): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/GCoreFlp( 1750): No location to return for getLastLocation()
W/FusedLocationProvider( 1750): location=null
I/GCoreUlr( 1750): Unbound from all location providers
I/GCoreUlr( 1750): Place inference reporting - stopped
I/GCoreUlr( 1750): DispatchingService.onDestroy()
I/GCoreUlr( 1750): Stopping handler for UlrDispSvcFast
,I/ActivityManager(  835): Killing 3882:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  835): failed to open /acct/uid_10069/pid_3882/cgroup.procs: No such file or directory
,I/GCoreUlr( 1750): Unbound from all location providers
I/GCoreUlr( 1750): Place inference reporting - stopped
D/PersistentNotificationBroadcastReceiver( 1750): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/ActivityManager(  835): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4412 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.676ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.456ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.120ms
,I/art     (  835): Explicit concurrent mark sweep GC freed 23213(1134KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 4.122ms total 160.087ms
,W/ResourcesManager( 4412): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/App     ( 4412): [App][onCreate()] 4.40.23
,D/AccountManager( 4412): setSyncFrequency
,W/ContextImpl( 4412): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/ReminderService( 4412): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4412): [connect] Request location client connection.
W/ContextImpl( 4412): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  835): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4439 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  835): Waited long enough for: ServiceRecord{649ac41 u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager(  835): Killing 3910:com.lge.springcleaning/1000 (adj 15): empty #11
D/LocationReminderManager( 4412): location cilent is connected.
,W/libprocessgroup(  835): failed to open /acct/uid_1000/pid_3910/cgroup.procs: No such file or directory
,D/LGDMClient( 4439): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4439): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/art     ( 1750): Explicit concurrent mark sweep GC freed 16432(1135KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 13MB/21MB, paused 1.351ms total 89.501ms
D/LocationReminderManager( 4412): [removeAllReminders]
D/WeatherAncestor( 2642): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 23:48:4
,W/GeofencerStateMachine( 1750): Ignoring removeGeofence because network location is disabled.
D/LocationReminderManager( 4412): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4412): [removeAllReminders] Failed to remove reminder
D/UpdateThreadPoolManager( 2642): 2 : This is isUpdating : false
,D/WeatherAncestor( 2642): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 23:48:4
D/WeatherService( 2642): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/GCoreFlp( 1750): No location to return for getLastLocation()
W/GCoreFlp( 1750): No location to return for getLastLocation()
W/ActivityManager(  835): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2642): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2642): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2642): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2642): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2642): 2 : This is isUpdating : false
D/WeatherService( 2642): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2642): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2642): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2642): 2 : Fixed theme : optimus
V/UserPresentBroadcastReceiver( 1750): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/WeatherReflect( 2642): 2 : Map key string is -2
D/LGDMClient( 4439): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
D/lim     ( 2642): 2 : time = 23:48
,I/WeatherReflect( 2642): Model Name : LG-D722
D/WeatherTheme( 2642): 2 : exactly same view!
D/WeatherTheme( 2642): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  835): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2642): 2 : Utils getTopActivity com.lge.launcher2 / true
D/LGDMClient( 4439): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/WeatherService( 2642): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2642): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  835): Killing 3948:com.google.android.configupdater/u0a3 (adj 15): empty #11
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
W/libprocessgroup(  835): failed to open /acct/uid_10003/pid_3948/cgroup.procs: No such file or directory
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  835): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4473 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  835): Message: 20
D/BluetoothManagerService(  835): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2487b87:true
,D/BluetoothAdapter( 4473): 273706704: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4473): 273706704: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  835): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  835): RTC_WAKEUP set : Alarm{19a74923 type 0 when 1452552458418 com.android.providers.contacts} when 1452552458418
I/ActivityManager(  835): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4494 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  835): ELAPSED_WAKEUP set : Alarm{89b547f type 2 when 53336 com.google.android.talk} when 53336
V/AlarmManager(  835): RTC_WAKEUP set : Alarm{2c42495 type 0 when 1452552484990 com.google.android.gms} when 1452552484990
,V/LGMDMManager( 4473): Create singleton instance
,I/iu.UploadsManager( 2290): End new media; added: 0, uploading: 0, time: 59 ms
,D/UEI.SmartControl( 4494): Quickset Services start...
,I/UEI.SmartControl( 4494): Manufacture = LGE
I/AudioManager( 4473): getMode name:com.lge.qremote
D/UEI.SmartControl( 4494): File observer start...
E/UEI.SmartControl( 4494): IR Port is disabled: false
D/UEI.SmartControl( 4494): Starting file observer...
D/UEI.SmartControl( 4494): Extracting JNI libs...
D/UEI.SmartControl( 4494): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4473): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4494): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4494): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4494): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
I/UEI.SmartControl( 4494): --- Selecting new region: 2
V/MmsSystemEventReceiver( 3139): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3139): ANY_DATA_STATE event received: DISCONNECTED
I/UEI.SmartControl( 4494): -- Running on KitKat(19) and above! JNI will be used.
D/LGDMClient( 4439): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4439): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/UEI.SmartControl( 4494): Platform has CIR...
W/ContextImpl( 4439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/UEI.SmartControl( 4494): NO CIR support, need to check package...
I/UEI.SmartControl( 4494): Model: LG-D722 uses JNI
W/ContextImpl( 4439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/UEI.SmartControl( 4494): QS Service created
D/LGDMClient( 4439): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/AudioManager( 4473): getMode name:com.lge.qremote
D/LGDMClient( 4439): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,I/AudioManager( 4473): getMode name:com.lge.qremote
E/UEI.SmartControl( 4494): QS start get config
,I/ActivityManager(  835): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4516 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/UEI.SmartControl( 4494): Loading JNI Libs...
,D/UEI.SmartControl( 4494):  configuring local db...
,W/ResourcesManager( 4516): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4516): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4516): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 4516): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4516): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/UEI.SmartControl( 4494):  ---- Has DB8: true
D/UEI.SmartControl( 4494): QS start statue = true Error code = 0
,D/UEI.SmartControl( 4494): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4494): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/PackageChangeReceiver( 4516): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
D/UEI.SmartControl( 4494): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4494): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 4494): IrrcClient ++ 
D/irrcClient( 4494): getIrrcService ++ 
D/irrcClient( 4494): getIrrcService -- 
D/irrcClient( 4494): IrrcClient -- 
W/irrc_jni( 4494): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4494): Services init done
I/UEI.SmartControl( 4494): Device manager: loading config....
D/UEI.SmartControl( 4494): Config is loaded...
,I/ActivityManager(  835): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4540 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  835): Killing 3981:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  835): failed to open /acct/uid_1000/pid_3981/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 4494): QS Service init finished
D/UEI.SmartControl( 4494): QS Service version name: 0.1.73
D/UEI.SmartControl( 4494): QS Service version code: 1073
D/UEI.SmartControl( 4494): Service requested: Control
D/UEI.SmartControl( 4494): Internal service binding...
D/UEI.SmartControl( 4494): -----IControl: 11
D/UEI.SmartControl( 4494):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 4494): Caller: com.lge.qremote
I/UEI.SmartControl( 4494): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4494): ------------ IControl registerCallback...
I/UEI.SmartControl( 4494): Registering callback...
,D/UEI.SmartControl( 4494): -----IControl: 19
D/UEI.SmartControl( 4494): Caller: com.lge.qremote
I/UEI.SmartControl( 4494): Registering Services Ready callback...
I/UEI.SmartControl( 4494): Notify client services are ready...
D/UEI.SmartControl( 4494): -----IControl: 8
D/UEI.SmartControl( 4494): Caller: com.lge.qremote
,I/ActivityManager(  835): Killing 4091:com.google.android.youtube/u0a100 (adj 15): empty #11
I/ActivityManager(  835): Killing 4001:com.google.android.talk/u0a61 (adj 15): empty #12
,W/libprocessgroup(  835): failed to open /acct/uid_10100/pid_4091/cgroup.procs: No such file or directory
,W/libprocessgroup(  835): failed to open /acct/uid_10061/pid_4001/cgroup.procs: No such file or directory
D/BluetoothManagerService(  835): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  835): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  835): Message: 2
D/WifiServiceImplEx(  835): setWifiEnabled: false pid=4057, uid=10317, package= com.example.hello, App Lable : HelloWorld
,D/WifiService(  835): setWifiEnabled: false pid=4057, uid=10317
I/jxcore-log( 4057): ****TEST TOOK:  5118  ms ****
I/jxcore-log( 4057): 
I/jxcore-log( 4057): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4057): 
I/ActivityManager(  835): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4561 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  835): Killing 4204:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  835): failed to open /acct/uid_10053/pid_4204/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4561): onCreate
W/AppUp4:DB( 4561):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4561):  setFingerPrint start
I/AppUp4:DB( 4561):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4561):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4561):  SDK version = 0
I/AppUp4:DB( 4561):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4561): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 4561): removed from Exclude : com.example.hello : 1
,I/ActivityManager(  835): Killing 4256:com.lge.bnr/1000 (adj 15): empty #11
D/AndroidRuntime( 4571): 
D/AndroidRuntime( 4571): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4571): CheckJNI is OFF
W/libprocessgroup(  835): failed to open /acct/uid_1000/pid_4256/cgroup.procs: No such file or directory
I/ActivityManager(  835): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4583 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4583): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4583): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/AndroidRuntime( 4571): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  835): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
,I/ActivityManager(  835): Killing 4057:com.example.hello/u0a317 (adj 0): stop com.example.hello
I/WindowState(  835): WIN DEATH: Window{a5e756a u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  835): Focus left window: Window{a5e756a u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  835): Window went away: Window{a5e756a u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  835): Skipping PackageSetting{36bea3d6 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  835): Force removing ActivityRecord{1368d014 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  835): Spurious death for ProcessRecord{339a4967 4057:com.example.hello/u0a317}, curProc for 4057: null
,I/ActivityManager(  835): Force stopping com.example.hello appid=10317 user=0: pkg removed
I/AppConfig( 4583): Total System Memory = 906309632
I/GalleryUtils( 4583): Application Heap = 96 MB
,I/AppConfig( 4583): App Tier : NOT_DEF
D/SystemHelper( 4583): region [EU], country [EU], operator [OPEN], sub-operator []
,D/KeyguardModel( 1388): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1895): [Launcher.java:5203:onStart()]onStart
I/QCNEJ   ( 1858): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1750): Ignoring removeGeofence because network location is disabled.
I/InputReader(  835): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3458): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3458): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3458): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3458): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3458): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3458): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3458): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3458): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3458): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3458): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3458): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3458): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/[LGHome]EVENT( 1895): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  835): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4620 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/administrator(  835): Handling package changes for user 0
,I/[SystemUI]QSlideListController( 1388): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1895): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/LockScreenSettings( 4620): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/ActivityManager(  835): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4641 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  835): Killing 4293:com.android.vending/u0a36 (adj 15): empty #11
I/[LGHome]EVENT( 1895): [Launcher.java:929:onResume()]onResume end
,I/Activity( 1895): Activity.onPostResume() called 
W/libprocessgroup(  835): failed to open /acct/uid_10036/pid_4293/cgroup.procs: No such file or directory
D/KeyguardModel( 1388): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1388): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1895): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1895): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,D/KeyguardModel( 1388): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1388): createShortcutInfo...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/SystemUI[Framework](  835): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  835): Call!!!getLGSystemUiVisibility. =0x0
D/KeyguardModel( 1388): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1388): createShortcutInfo...
D/StatusBarManagerServiceEx(  835): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  835): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  835): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@39add8a5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  835): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 1803): CheckpointMarkThreadRoots callback created = 0xaaf21b50
,W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1388): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1388): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1388): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1388): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1388): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1388): createShortcutInfo...
D/InputDispatcher(  835): Focus entered window: Window{3a67a11a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1388): handleShortcutListChanged...
,D/KeyguardModel( 1388): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1388): createShortcutInfo...
I/art     ( 1803): CheckpointMarkThreadRoots callback created = 0xaaf21f60
I/[LGHome]EVENT( 1895): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1895): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1895): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1895): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1895): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  835): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  835): Got RemoteException sending setActive(false) notification to pid 4057 uid 10317
D/KeyguardModel( 1388): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1388): createShortcutInfo...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1388): createShortcutInfo...
,W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1388): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1388): createShortcutInfo...
,I/NotificationService(  835): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  835): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/JobSchedulerService(  835): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1388): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1388): createShortcutInfo...
,D/PhoneStatusBar( 1388): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  835): removeObsoleteFile: deleting file=220_task.xml
I/art     (  835): Explicit concurrent mark sweep GC freed 19691(1236KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 29.106ms total 335.524ms
I/ActivityManager(  835): Killing 4412:com.lge.qmemoplus/1000 (adj 15): empty #11
W/ResourcesManager( 4641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4641): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4641): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4641): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4641): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/HotwordRecognitionRnr( 1996): Starting hotword detection.
,I/MicrophoneInputStream( 1996): mic_starting com.google.android.apps.gsa.speech.audio.u@4ee7fd1
V/AudioRecord( 1996): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1996): set(): mSessionId 22
V/AudioPolicyManager(  280): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  280): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  280): adev_open_input_stream: exit
V/AudioFlinger(  280): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  280): openInput_l() created record thread: ID 23 thread 0xb42fa000
V/AudioSystem(  280): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  280): AudioFlinger's thread 0xb42fa000 ready to run
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioSystem( 1996): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioSystem( 2652): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3139): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  835): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1388): ioConfigChanged() event 3, ioHandle 23
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioSystem( 1769): ioConfigChanged() event 3, ioHandle 23
,V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioFlinger(  280): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  280): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  280): acquiring 22 from 1996, for -1
V/AudioFlinger(  280):  added new entry for 22
V/AudioRecord( 1996): start, sync event 0 trigger session 0
V/AudioRecord( 1996): mAudioRecord->start()
V/AudioFlinger(  280): RecordHandle::start()
V/AudioFlinger(  280): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  280): startInput() module primary->input primary(23)
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  280): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  280): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  280): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  280): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  280): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  280): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb42fa000
V/AudioFlinger::PatchPanel(  280): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  280): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
,V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  280): setParameters(): io 23, keyvalue hotword_active=1, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
I/SystemUI[Framework](  835): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  835): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  835): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  835): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  835): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@39add8a5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  835): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb42fa000
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): AudioPolicyManager::startInput() input source = 1999
I/Timeline( 1895): Timeline: Activity_idle id: android.os.BinderProxy@38ce7d3e time:61927
V/msm8974_platform(  280): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  280): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  280): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  280): start_input_stream: usecase(7)
E/audio_hw_primary(  280): select_devices: enter and usecase(7)
V/msm8974_platform(  280): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  280): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  280): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  280): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  280): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  280): enable_snd_device: enter  144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  280): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  280): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  280): ACDB -> send_adm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_asm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_audtable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  280): ACDB -> send_audvoltable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  280): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  280): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  280): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  280): enable_audio_route: exit
D/audio_hw_primary(  280): select_devices: done
V/audio_hw_primary(  280): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  280): start_input_stream: exit
,D/AndroidRuntime( 4571): Shutting down VM
D/KeyguardModel( 1388): handleShortcutListChanged...
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1388): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1388):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1388): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup(  835): failed to open /acct/uid_1000/pid_4412/cgroup.procs: No such file or directory
I/MicrophoneInputStream( 1996): mic_started com.google.android.apps.gsa.speech.audio.u@4ee7fd1
D/BarTransitions( 1388): draw background and invalidate : color = ef000000
D/BarTransitions( 1388): draw background and invalidate : color = eee5e5e5
,I/HotwordWorker( 1996): onReady
,W/ResourcesManager(  835): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SystemConfig( 4641): BUILD Country: EU
I/SystemConfig( 4641): BUILD Operator: OPEN
,I/Timeline(  835): Timeline: Activity_windows_visible id: ActivityRecord{3dd46caa u0 com.lge.launcher2/.Launcher t219} time:62179
,W/ResourceType(  835): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/LockScreenSettings( 4620): New app installed broadcast received ..
,I/[LGHome]EVENT( 1895): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/LockScreenSettings( 4620): Number of installed packages  1
,I/ActivityManager(  835): Waited long enough for: ServiceRecord{249ff039 u0 com.lge.mlt/.MltMonitorService}
I/SystemConfig( 4641): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4641): existFile = false
I/SystemConfig( 4641): canReadFile = false
I/SystemConfig( 4641): systemFeature RCS result false
D/SystemConfig( 4641): refreshRcsSupport() :false
I/ActivityManager(  835): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  835): Killing 2290:com.google.android.gms/u0a6 (adj 15): empty #11
D/LCardEmulationManager( 1803): getHceAppCount hostAppNum : 0
W/libprocessgroup(  835): failed to open /acct/uid_10006/pid_2290/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1803): getDefaultRoute
,D/EulaProviderUpdateObserver( 4669): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4669): uri : package:com.example.hello
,I/ActivityManager(  835): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4686 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  835): Killing 4494:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 21.703ms
,W/System.err( 4473): android.os.DeadObjectException
,W/System.err( 4473): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4473): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4473): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4473): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4473): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4473): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4473): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4473): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4473): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4473): android.os.DeadObjectException
W/System.err( 4473): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4473): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4473): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4473): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4473): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4473): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4473): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4473): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4473): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 20.909ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.177ms

```
